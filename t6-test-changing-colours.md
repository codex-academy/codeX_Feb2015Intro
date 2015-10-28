## T6 Test changing colours

Now use TDD to create a Constructor Function (also called a Class) that makes it easy to set the Test Colour of a block. Call the function `SetTestStatus`. The constructor function should take the element id as a parameter. It should have two functions called `testFailed` and `testPassed`

Using it should look like this:

```javascript
var fp = new SetTestStatus("testresult");

fp.testFailed();
// `#testresult` should have the HTML class "failing" now
// set the text in the block to 'Failed'

fp.testPassed();
// ``#testresult` should have the HTML class "passing" now
// set the text in the block to 'Passed'
```

Create these files:

* fail_pass.js
* fail_pass_test.js
* fail_pass.html

Remember to test that the methods of the `SetTestStatus` function are changing the DOM elements as expected.

**Remember to commit to Git**

---

Time for another [Short break from the JavaScript](lets_code.md#short-break-from-the-javascript-1).
