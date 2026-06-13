# Exercise 1
## The Specificity Showdown
1. ID selectors has higher specificity than class and element selectors. That means the ID-based rule overrides both the class-based and element-based rule on the same element, even if the rule appears at the bottom of the stylesheet. 

2. I used the ID selector to make the paragraph green, by adding a line of code at the bottom of the already existing code, and this overrides the other rules inluding the previous ID-based rule because of the top to down effect in CSS `(The cascade effect)`. Which gives the last rule more specificity over the other rules on the same element.

3. I can make the paragraph green by combining selectors to make one rule which makes the makes the specificity of the combined selectors higher than an ID selector. And in testing this rule I combined the class and ID selector.