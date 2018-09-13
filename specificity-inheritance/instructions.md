### Instructions to demonstrate inheritance
1. Write your style in the `style` tag in the `head` section for this
2. Create style for the selector `ul` with property `color` purple
  * Notice the `li` will become purple as well
  * When you style the `ul` and the `li` was indirectly changes and it inherited that color from the parent element
---

3. Add a `p` tag with content `Hello <your_name>`
4. Remove the `styles` for element `ul`
5. Create a style for tag `body` with property `color` red
6. Notice all the elements on the page has the color of red
7. This demonstrate the concept of inheritance where if we set the property on a parent element, it also affect the child elements


### Instructions to demonstrate specificity
* Create a style for tag `ul` with property `color` blue
* Notice the ul and li turns blue because of inheritance
* Another idea to demonstrate here is also specificity
  * There are multiple styles impacting the same element such as `li`
  * It could the color red coming from `body` or color blue coming from `ul`
  * Look at chrome inspector
  * Whatever style closest to `li` element will win

#### Specificity is this idea in CSS that we can have multiple styles targeting one element and CSS has to decide which one wins
* Create a style for tag `li` with property `color` orange
* Notice the `li` tag is now orange as this style is the closest and CSS determines it's the winner

### Classes in specificity
* Add a `class` to the first and last `li` in the `ul` called `highlight`
* Create a style for the class `.highlight` with property `color` yellow
* Who will win in this case?
* This shows that class will win over direct element

### IDs in specificity
* Add an `id` to the first `li` in the `ul` called `unique`
* Create a style for the id `#unique` with property `color` pink
* In this case the `id` wins over the rest

### Calculation in deciding which styles wins in specificity
* Use this calculator link [Specificity link](https://specificity.keegan.st)

