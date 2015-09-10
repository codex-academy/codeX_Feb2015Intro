## T5 Test your function

In all the tasks above we tested our code by running it in the browser and checking if it worked as it should.
What about writing a program to check if things are working as they should or not? This way of programming is called Test Driven Development and it uses a Red & Green coding cycle.

In this Task you need to write a function called setBackgoundColor. It takes two parameters: the id of the element whose background color is to be set, and then the color it should be set to.

Calling this function looks like this: `setBackgoundColor('mySquare', 'orange');`

TDD starts like this:

* write some code that uses the code that you would like to write
* run this code
* everything should fail horribly - the code you are calling doesn't exist yet!
* the state of the test is 'red'

**Ok let's do that quickly:**

Create files called:

* task5.html
* task5.css
* two JavaScript files calles task5.js & task5_tests.js.

The HTML file should reference the two separate JavaScript files. The one JavaScript file will contain our function implementation and the other the test code.

The HTML file should should reference function implementation file before the test file - as the JavaScript files are loaded from top to bottom.

```html
<!DOCTYPE html>
<html>
<head>
	<title>header!</title>
	<link rel="stylesheet" type="text/css" href="task5.css">
	<script type="text/javascript" src="task5.js"></script>
	<script type="text/javascript" src="task5_tests.js"></script>
</head>
<body>
	<!-- HTML goes here -->
	<!-- style this in the CSS to be 300 x 300 px and to have a red background -->
	<div id="mySquare">
	</div>
</body>
</html>
```

**In the task5_tests.js file**

* We need to check the current color of the background of the 'mySquare' is green. We can use the DOM to do that.
* now call the `setBackgoundColor('mySquare', 'red');`
* now we check that the background of 'mySquare' is set to red
* Use the alert function to display 'success' if the background color of 'mySquare' is equal to green, otherwise display 'failure'

**It should fail now!**
> Use Chrome Developer Tools console to see why it's failing

**In the task5.js file:**

* create an implementation for the `setBackgoundColor` function
    * remember it takes 2 parameters
    * first one the element name
    * second one the color that you will set the background to
    * the function should set the background of the element specified to the color supplied.
* refresh the page and see what happens
* There should be no errors in Chrome Developer Tools'
* and you should see an alert window displaying 'success'

Congratulations! You just created your first function using TDD!

***So TDD (Test Driven Development) works like this:***

* write test code that will fail - it depends on non-existent code
* run the test - it should fail
* write some code that will fix the failing code
* run the test again - it should work now
* make your code better if needed, without changing the actual behaviour (google this: code refactoring)
* start the process again, by adding a new test...

**Remember to commit to Git**

---

[Go back to Let's Code](lets_code.md) or [go on T6 Test changing colours](t6-test-changing-colours.md)
