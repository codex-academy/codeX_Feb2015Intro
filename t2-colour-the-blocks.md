## T2 Colour the blocks

> This task requires HTML, CSS & JavaScript

This task will require you to:

* add some button click event handlers using JavaScript
* manipulate the styling by adding classes

### The DOM

DOM stands for Document Object Model. This is an in memory representation of the elements contained in an HTML document. You use HTML for the **content** of your pages and CSS for the **presentation** of your pages. You can add **behaviour** to a web page by writing some JavaScript code to interact with a web page's DOM.

Eloquent JavaScript provides a good introduction to the DOM in [Chapter 13: The Document Object Model](http://eloquentjavascript.net/13_dom.html).

You can find elements in the DOM by their `id` or by their `class`. There are a couple ways of doing this. Have a read about these on the [Mozilla Developer Network](https://developer.mozilla.org/en-US/) about:

* [getElementById](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById)
* [getElementsByClassName](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementsByClassName)
* [querySelector](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector)

To handle clicks on buttons, you can use:

* [addEventListener](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)

For adding and removing classes, have a look at:

  * [className](https://developer.mozilla.org/en-US/docs/Web/API/Element/className)
  * [classList](https://developer.mozilla.org/en-US/docs/Web/API/Element/classList)

## Tasks

In a file called task2.html create an HTML page that:

* displays two blocks that are `10em` wide and have a grey background
* has a `button` underneath each block
    * the `button` text under the first block should be 'Make red'
    * the `button` text under the second block should be 'Make green'
* adds a `class` to the first block that makes the background red when the `button` under the first block is pressed
* adds a `class` to the second block that makes the background red when the `button` under the second block is pressed

The start of your HTML file should look look something like this. This time we're putting our CSS in a different file, and adding some JavaScript in a `script` tag.

```html
<!DOCTYPE html>
<html>
<head>
	<title>header!</title>
   <!-- Your CSS goes in the task2.css file -->
	<link rel="stylesheet" type="text/css" href="task2.css">
</head>
<body>
	<!-- HTML goes here -->
	<script type="text/javascript">
		// JavaScript code goes here at the bottom
	</script>
</body>
</html>
```

Once you are done, add your changes to git by using these commands:

* `git status` to see what changed
* `git add .` to add everything to git
* `git commit -m "task 2 is done"` to commit your changes

---

[Go back to Let's Code](lets_code.md) or [go on T3 One square changing colours](t3-one-square-changing-colours.md)
