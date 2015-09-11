## T6 Test changing colours

Now using TDD to create a Constructor Function (also called a Class) that makes it easy to set the Test Colour. Call the function FailOrPass. The constructor function should take the element id as a parameter. It should have two functions called `testFailed` and `testPassed`

Using it should look like this:

```javascript
var fp = new FailOrPass("testresult");

fp.makeFailed();
// testresult should have the HTML class "failing" now

fp.testPassed();
// testresult should have the HTML class "passing" now
```

Create these files:

* fail_pass.js
* fail_pass_test.js
* fail_pass.html

**Remember to commit to Git**

---

[Go back to Let's Code](lets_code.md) or [go on T7 Display Test Results](t7-display-test-results.md)
