## T8 Unit Testing Framework

So you might not realise it, but you have now built a small Unit Testing framework. It has it limitations though - it can only test one function at a time, and it is not telling you what you are testing or how many tests have failed or passed.

**So now**

* Add support to run multiple tests:
    * one can add multiple tests in ```tdd_test.js```
    * for each test added, a block should be displayed on the tdd.html screen
        * green for a passing test
        * red for a failing test
    * you will need to dynamically add elements to the DOM. Use this as a reference point: [The Basics of JavaScript DOM Manipulation](http://callmenick.com/2014/03/27/basics-javascript-dom-manipulation/)
* Display which test passed or failed
* If a test fails display the error / exception on the screen in the block for the test
* Display how many tests passed or failed - only display this once.

**Once you think you are done** please review your testing implementation with your Tech Mentor

---

[Go back to Let's Code](lets_code.md)
