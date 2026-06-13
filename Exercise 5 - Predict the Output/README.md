# Exercise 5
## Predict the Output
### Scenario A
- The text inside the `<p>` is orange.
-  Yes the universal selector applies since it targets every element on the page including the `<p>` so the `<p>` gets the `color: orange` from the universal selector. Since target wins over inheritance,  the universal selector wins since it targets the element directly and element selector uses inheritance.

### Scenario B
- Green
- In this scenario, both rules directly targets the `<p>` but the class selector has higher specificity than the universal selector, hence the text will be green. It demonstarates the principle of specificity when two rules directly targets the same element.