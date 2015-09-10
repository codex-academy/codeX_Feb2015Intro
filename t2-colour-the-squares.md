## T2 Colour the squares

> This task requires HTML, CSS & JavaScript

**This task will require you to:**

* add some button click event handlers using JavaScript
* manipulate the CSS styling using the browser DOM

**The DOM**

> DOM stands for Document Object Model - this is an in memory representation of the elements contained in a
> HTML document. One can add behaviour to a web page by writing some JavaScript code to interact with a web page's DOM.

**Basic DOM concepts**

 Concept          |   Code snippet     | Link
------------------|--------------------|-----------------
Basic DOM overview | Basic DOM overview | [The Basics of JavaScript DOM Manipulation](http://callmenick.com/2014/03/27/basics-javascript-dom-manipulation/)
Finding DOM element - like a DIV element based on a ID name | `var element = document.getElementById('id')` |   [JavaScript HTML DOM Elements](http://www.w3schools.com/js/js_htmldom_elements.asp)
Styling elements from JavaScript | `element.style.backgroundColor = 'red';` | [HTML DOM Style Object](http://www.w3schools.com/jsref/dom_obj_style.asp)
Styling elements from JavaScript | `element.addEventListener('click', function(){});` | [Style backgroundColor Property](http://www.w3schools.com/jsref/prop_style_backgroundcolor.asp)
What is the DOM?   | | [The Document Object Model](http://eloquentjavascript.net/13_dom.html)

In a file called task2.html create a HTML page:

* That displays two white squares that are 300px by 300px with a black border that is 5px thick.
* create a button underneath each square.
* the button text under the first square should be 'Make red' and 'Make green' under the second square.
* when the button under the first square is pressed it should make the first square red.
* when the button under the second square is pressed it should make the second square green.

**The HTML should look look something like this**

```html
<!DOCTYPE html>
<html>
<head>
	<title>header!</title>

	<link rel="stylesheet" type="text/css" href="">
	<style type="text/css">
	/* CSS goes here */
	</style>

</head>
<body>
	<!-- HTML goes here -->
	<script type="text/javascript">
		//JavaScript code goes here at the bottom to ensure the DOM is loaded...
	</script>
</body>
</html>
```

Once you are done add your changes to git by using these commands:
* `git status` to see what changed
* `git add .` to add everything to git
* `git commit -m "task 2 is done"` to commit your changes to git

---

[Go back to Let's Code](lets_code.md) or [go on T3 One square changing colours](t3-one-square-changing-colours.md)
