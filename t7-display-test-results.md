## T7 Display Test Results

In this task we would like to make it much easier to write code using TDD. What we need is a place to write the code under test and a way to see whether the test passed or not by displaying a red or green block.

We need something like this:

```javascript
TestMyCode.run("testing hello world function", function(assert){
	var result = helloWorld();
	// is the result as we expected?
	assert.equals("hello world!", result);
});
```

For this task you will need to create these files:

  File name | What this file is for
--- | ---
tdd.js | The TestMyCode implementation will be in here
tdd_test.js | TestMyCode will be tested in here
tdd.html | Bring all the files together & test executed from here
tdd.css | Make the HTML look nice
tdd_hello_world.js | the function under test
red_green.js | reuse the function you wrote earlier

So let's use TDD to create this code.

* Copy the code from above into the `tdd_test.js` file
* Create `tdd.html`
    * reference the HTML and CSS files from it.
    * Create a 300x300px square
* Once done open tdd.html in Chrome and check the Developer tools to see what errors you are getting.

You might notice that the `TestMyCode` object is non existent.

There are a few things to think about:
* a `run` method for the TestMyCode class: it takes two parameters - the name of the test and a function that should be executed
* the `assert` function: it's passed into the test function
    * it checks the test was successful, if the expected result was returned or not
* Ensure that:
    * if the expected result was returned: display a green square
    * if the expected results was not returned: display a red square
    * if there is an error/exception: display a red square - use `try/catch` exception handling in JavaScript
* Use an object literal to create this.

**Refresh** `tdd.html` to see what errors you are getting.

In the `tdd_hello_world.js` file create a simple function that returns 'hello world!';

**Refresh** `tdd.html` to see what errors you are getting.

By now you should be close to having a small TDD framework that allows you to test your code.
Do you have a green block yet?
If not change your function to return the expected result, to make the block go green.
Try it with a different function other that the helloWorld one. Make sure that you can get a red block if the function returns an unexpected result.

**Remember to commit to Git**

---

[Go back to Let's Code](lets_code.md) or [go on T8 Unit Testing Framework](t8-unit-testing-framework.md)
