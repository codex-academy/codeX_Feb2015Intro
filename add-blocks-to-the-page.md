## T8 Add blocks to the page

Now lets's look at how we can add things to the DOM with JavaScript. We'll need this for the next task. Create a page that has has a `div` with the `id` `testresults`. Using TDD, create a function that

* adds a child element of `#testresults` that has the class `fail` (which makes it `10em` wide, with a red background and white text)
    * add the text "Test failed."
* adds a child element of `#testresults` that has the class `pass` (which makes it `10em` wide, with a green background and white text)
    * add the text "Test passed."

Your JavaScript might look something like this:

```javascript
var cb = new CreateBlock("testresult");

cb.addBlockFailed();
// `#testresult` should have a child element with the HTML class "failing", and the text "Test failed.

cb.addBlockPassed();
// `#testresult` should have a child element with the HTML class "passing", and the text "Test passed.
```

Have a look at [The Basics of JavaScript DOM Manipulation](http://callmenick.com/2014/03/27/basics-javascript-dom-manipulation/) to get some ideas.

---

[Go back to Let's Code](lets_code.md) or [go on T9 Display Test Results](display-test-results.md)
