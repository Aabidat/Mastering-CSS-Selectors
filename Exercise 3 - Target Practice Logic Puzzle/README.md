# Exercise 3
## Target Practice Logic Puzzle
1. I used the pseudo class to target the second `<li>` to make `item 2` grey.
2. I  targeted the second `<p>` using `.container p:nth-child(3)` pseudo-class selector and it worked because the second `<p>` was the third child in the container class.

3. Since every `<p>` lives inside `<body>`, using the descendant selector, I first targeted the `<body>` then the `<p>` to give them a line height of 1.6.

4. you can't target the `<p:nth-chlid(1)> ` in this html structure because the `<h2>` comes before the `<p>` hence the `<h2>` is the first child. It is looking for the first child as a `<p>`. but in this case the `<p>` is not the first child.