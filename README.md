# JavaScript Chaining

In this example, if you want to use more than one jQuery method on the same selection of elements, you can list several methods at a time using dot notation to separate each one, as shown below. In this one statement, three methods act on the same selection of elements: hide() hides the elements, delay() creates a pause, fadeIn() fades in the elements. The process of placing several methods in the same selector is referred to as chaining. As you can see, it results in code that is far more compact.

## Process of chaining

To make your code easier to read, you can place each new method on a new line.
```
$('li[id!="one"]')
.hide()
.delay(500)
.fadeIn(1400);
```

Each line starts with the dot notation, and the semicolon at the end of the statement indicates that you have finished working with this selection. Most methods used to update the jQuery selection can be chained. However the methods that retrieve information from the DOM (or about the browser) cannot be chained.

![0](https://cloud.githubusercontent.com/assets/18538482/16905214/a10242d4-4c70-11e6-9584-ee14649fa1ea.png)

## How to run the app locally?

* In your terminal type:
```
git clone https://github.com/bostonhuman/javascript-chaining
```
* Open `chaining.html` to run the app.
