## T9 Unit Testing Framework

You might not realise it, but you have now built a small Unit Testing framework. Well done! It has its limitations though: it can only test one function at a time, and it is not telling you **what you are testing** or **how many tests have failed or passed**.

### Multiple tests

* Add support to run multiple tests. You'll need to dynamically add elements to the DOM. Use this as a reference point: [The Basics of JavaScript DOM Manipulation](http://callmenick.com/2014/03/27/basics-javascript-dom-manipulation/). Write code so that
    * you can add multiple tests in `tdd_test.js`
    * for each test added, a block is displayed in `tdd.html` whic is
        * green for a passing test
        * red for a failing test
* Display the name of the that test passed or failed.
* If a test fails display the error / exception on the screen in the block for the test.
* Display how many tests passed or failed. Only display this once.

**Once you think you are done** please review your testing implementation with a mentor.

---

[Go back to Let's Code](lets_code.md)
