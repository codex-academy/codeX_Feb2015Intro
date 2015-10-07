## T5 Test your function

In all the previous tasks we checked our code by running it in the browser and checking if it worked as it should. What about writing a test (in code) to check if things are working instead?

When we write the test before we write the code, it's called Test-Driven Development (or TDD for short). It uses a Red & Green coding cycle that goes like this:

* Add a test for the code you want to write.
* Run the test. It will fail because you haven't written your code yet!
	* The status of the test is **failing**, so we make it **red**.
* Write (just enough) code to make the test pass.
* Run the test again. It should pass!
	* The status of the test is now **passing**, so we make it **green**.
* Make your code better, without changing the behaviour. This is called code refactoring.

### Tasks

In this task you need to write a function called `setTestStatus`. It takes two parameters: the id of an element and the test status. Calling this function should like this: `setTestStatus('testresult', 'passing');`.

Create files called:

* `task5.html`
* `task5.css`
* `task5.js` and `task5_tests.js`

The HTML file should reference the two separate JavaScript files: the one JavaScript file will contain our function implementation and the other will contain the test code. The HTML file should should reference the function implementation file before the test file because JavaScript files are loaded from top to bottom.

The start of your HTML file should look look something like this.

```html
<!DOCTYPE html>
<html>
<head>
	<title>header!</title>
	<link rel="stylesheet" type="text/css" href="task5.css">
</head>
<body>
	<!-- HTML goes here -->
	<!-- Use classes to style #testresult to be 10em wide and have a red background -->
	<div id="testresult">
	</div>
	<script type="text/javascript" src="task5.js"></script>
	<script type="text/javascript" src="task5_tests.js"></script>
</body>
</html>
```

The web page should:

* display the div `#testresult` `10em` wide and have a grey background
* have one `button` under the block that says 'Make red'

In the `task5_tests.js` file:

* Check that the div with id `testresult` doesn't have the class `failing` or `passing`. Use `console.log` to display a message that tells you what the result of the check was.
* Check that the `button` has the text 'Make red'.
* Call `setTestStatus('testresult', 'failing');`.
* Check that `#testresult` has the class `failing`. The CSS should give it a red background.
* Check that the `button` has the text 'Make green'.
* Call `setTestStatus('testresult', 'passing');`.
* Check that `#testresult` has the class `passing`. The CSS should give it a green background.
* Check that the `button` has the text 'Make red'.
* Display 'success' if `testresult` has the class `passing`, otherwise display 'failure'.

It should fail because we haven't written the `setTestStatus` function yet! Use Chrome Developer Tools console to see the why it's failing.

In the `task5.js` file:

* Create an implementation for the `setTestStatus` function.
    * Remember that it takes 2 parameters: the id of an element and the test status.
* Refresh the page and see what happens.
* There should be no errors in Chrome DevTools.
* You should see a console message displaying 'success'.

Congratulations! You just created your first function using TDD!

**Remember to commit to Git**

### Recap

So TDD (Test Driven Development) works like this:

* Add a test for the code you want to write.
* Run the test. It will fail because you haven't written your code yet!
	* The state of the test is **red**: it's **failing**.
* Write (just enough) code to make the test pass.
* Run the test again. It should pass!
	* the state of the test is now **green**: it's **passing**.
* Make your code better, without changing the behaviour. This is called code refactoring.

---

[Go back to Let's Code](lets_code.md) or [go on T6 Test changing colours](t6-test-changing-colours.md)
