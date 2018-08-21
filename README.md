# bunqDesktop Templates
A collection of templates for categories and category rules for [bunqDesktop](https://github.com/bunqCommunity/bunqDesktop)

The `categories.json` and `category-rules.json` file are used to setup bunqDesktop with an initial set of useful categories and rules. You are free to suggest changes through pull requests or an issue if you don't know how.

## Contribute categories
Below is a description of what the different values mean for a category.

### Id
This is just a value that can be used to reference this category. It isn't required but we recommend you set one so you can directly link to this category from a category-rule. 

### Label
The label that users will see next to the icon.

### Color
Colors are done by using basic HEX codes. There are plenty of sites online to test and modify these values. ([Google's color picker](https://www.google.com/search?q=color+picker))

### Icon
The icons are based on the most recent [Material Icons](https://material.io/tools/icons/?style=baseline) and [Fontawesome 5.2.0](https://fontawesome.com/icons?d=gallery). 

For the material icons you can simply click on them and copy the value displayed on the left. For the icon in the image it is "accessible".
![Material icons example](https://i.imgur.com/fkSkZoq.png)

With Fontawesome you'll have click the icon and copy the value displayed below like seen in this image. For this example the icon name that you'll need to copy is `fab fa-accessible-icon`.
![https://i.imgur.com/ucBoUO8.png](https://i.imgur.com/ucBoUO8.png)

### Priority
Right now this just changes which category is shown first in the list. Later on this value might be used to sort payments by priority but it isn't that important as of now.
