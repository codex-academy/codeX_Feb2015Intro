# Let's code!

Now we are going to write some code outside of Codecademy.

You should have a projects folder in your home directory, it's good practice to create all your different projects in one place on your PC that you can find easily.

In your projects folder:

* create a folder called RedAndGreen
* change into the folder RedAndGreen using `cd RedAndGreen`
* initialize it as a git repository using this command `git init`

In github create a new repository called 'RedAndGreen':

* to do that click on the + sign left from your profile name
* now select 'New repository'
* enter the repository name 'RedAndGreen'
* now click 'Create repository'

You will be presented with a few different setup options, you need to follow the instructions under:

**...or push an existing repository from the command line**

the parameters will be specific to your environment and you can copy and paste them into your RedAndGreen local directory in the terminal.  

The command would look like this, with your own git username:

	  git remote add origin git@github.com:<your_git_username>/RedAndGreen.git

Files:
* as you do each task create the files in the 'RedAndGreen' folder
* after each task remember to add your changes to git


## T1 - Create Red and Green Squares

> This task requires HTML & CSS

In a file called task1.html create two squares that are 300px by 300px with a black border that is 5px thick.
The first square should be red and the second square should be green. Be sure that your HTML file is properly formed - you can use the basic html template from Sublime Text for this as described above.

> For this task create the CSS in a style tag in the head of the html file file

**The HTML should look look something like this**

```html
<!DOCTYPE html>
<html>
<head>
	<title>header!</title>

	<link rel="stylesheet" type="text/css" href="">

	<style type="text/css">
	<!-- CSS goes here -->
	</style>
</head>
<body>
	<!-- HTML goes here -->
</body>
</html>
```

Once you are done add your changes to git by using these commands:

* `git pull` to get any remote changes
* `git status` to see what changed
* `git add .` to add everything to git
* `git commit -m "task 1 is done"` to commit your changes to git
*  `git push -u origin master` to push your changes to github

## T2 Colour the squares

> This task requires HTML, CSS & Javascript

**This task will require you to:**
* add some button click event handlers using Javascript
* manipulate the CSS styling using the browser DOM

**The DOM**

> DOM, stands for Document Object Model - this is an in memory representation of the elements contained in a
> HTML document. One can add behaviour to a web page by writing some Javascript code to interact with a web page's DOM.

**Basic DOM concepts**

 Concept          |   Code snippet     | Link
------------------|--------------------|-----------------
Basic DOM overview | |http://callmenick.com/2014/03/27/basics-javascript-dom-manipulation/
Finding DOM element - like a DIV element based on a ID name | `var element = document.getElementById('id')` |  http://www.w3schools.com/js/js_htmldom_elements.asp
Styling elements from Javascript | `element.style.backgroundColor = 'red';` | http://www.w3schools.com/jsref/dom_obj_style.asp
Styling elements from Javascript | `element.addEventListener('click', function(){});` | http://www.w3schools.com/jsref/prop_style_backgroundcolor.asp
What is the DOM?   | |http://eloquentjavascript.net/13_dom.html

In a file called task2.html create a html page:
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
	<!-- CSS goes here -->
	</style>

</head>
<body>
	<!-- HTML goes here -->
	<script type="text/javascript">
		//javascript code goes here at the bottom to ensure the DOM is loaded...
	</script>
</body>
</html>
```

Once you are done add your changes to git by using these commands:

* `git status` to see what changed
* `git add .` to add everything to git
* `git commit -m "task 2 is done"` to commit your changes to git

## T3 One square changing colours

> This task requires HTML, CSS & Javascript

Create 3 files:
* task3.html - all html in here
* task3.css - all css in here
* task3.js - all javascript in here

Using the above 3 files create a web page:

* that displays a white square that is 300px by 300px with a black border that is 5px thick
* add two buttons under the square: one with text 'Make red' the other with 'Make green'
* when the 'Make red' button is pressed it should make the square red.
* when the 'Make green' button is pressed it should make the square geen.


**The html should look like this**

```html
<!DOCTYPE html>
<html>
<head>
	<title>header!</title>
	<link rel="stylesheet" type="text/css" href="task3.css">
	<script type="text/javascript" src="task3.js"></script>
</head>
<body>
	<!-- HTML goes here -->
</body>
</html>
```

Once done add your changes to git by using the same commands as you used for the tasks above.

## Publish your code to a website

Now let's use github pages to publish (https://pages.github.com/) your work to a website.

You will need to create a branch of your code called `gh-pages`

Before you do that let's explore branching in github... `todo add some info about branching - they covered it in git-it already...`

In your project folder type:

```
git branch
```

You should see a only one branch called `master`

No create a new branch called `gh-pages` by typing this in the terminal:

```
git branch gh-pages
```

To move into that branch type:

```
git checkout gh-pages
```

Any work you commit now will be done in the gh-pages branch. We will be using this branch to publish the work you are doing to github pages, to a page http://username.github.com/RedAndGreen.

To push this branch to github type:

```
git push origin gh-pages
```

After you've done this you should check out the master branch again by doing:

```
git checkout master
```

After the above steps the work you've done so far will be available online at: `http://username.github.com/RedAndGreen`

## T4 One button to change square colours

> This task requires HTML, CSS & Javascript

Using seperate file fon html, css & javascript called task4.html, task4.css & task4.js create a web page:

* that displays a green square that is 300px by 300px with a black border that is 5px thick.
* add one button under the square one with text 'Make red'
* when the buttons is pressed the square should go red
	* and the button text should change to 'Make green'
* when pressed the square should go green
	* and the button text should change to 'Make red'
* when pressed the square goes red again
* this process should be repeated over and over

Once done add your changes to git by using the same commands you used above.

## Let's make navigation easier

TODO - add steps to add a navigation menu that links to all the tasks they did in this project so far.

## T5 Test your function

In all the tasks above we tested our code by running it in the browser and checking if it worked as it should.
What about writing a program to check if things are working as they should or not. This way of programming is called Test Driven Development and it uses a Red & Green coding cycle.

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
* two javascript files calles task5.js & task5_tests.js.

The html file should reference the two seperate javascript files. The one Javascript file will contain our function implementation and the other the test code.

The html file should should reference function implementation file before the test file - as the javascript files are loaded from top to bottom

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
	<! -- style this in the CSS to be 300 x 300 px and to have a red background -->
	<div id="mySquare">
	</div>
</body>
</html>
```

**In the task5_tests.js file**

* We need to check the current color of the background of the 'mySquare' is green. We can use the DOM to do that.
* now call the ```setBackgoundColor('mySquare', 'red');```
* now we check that the background of 'mySquare' is set to red
* Use the alert function to display 'success' if the background color of 'mySquare' is equal to green, otherwise display 'failure'

**It should fail now!**
> Use Chrome developer tools' console to see why it's failing

**In the task5.js file:**

* create an implementation for the `setBackgoundColor` function
    * remember it takes 2 parameters
    * first one the element name
    * second one the color that you will set the background to
    * the function should set the background of the element specified to the color supplied.
* refresh the page and see what happens
* There should be no errors in Use Chrome developer tools'
* and you should see an alert window displaying 'success'

Congratulations! You just created your first function using TDD!

***So TDD (Test Driven Development) works like this:***
* write test code that will fail - it depends on non-existent code
* run the test - it should fail
* write some code that will fix the failing code
* run the test again - it should work now
* make your code better if needed, without changing the actual behaviour (google this: code refactoring)
* start the process again, by adding a new test...

**Remember to commit to GIT**

## T6 Test changing colours

Now using TDD create an Constructor Function (Class) that makes it easy to set the background color of a html element to Red or Green. Call the function RedOrGreen. The constructur function should take the element id as a parameter. It should have two functions called ```makeRed``` and ```makeGreen```

Using it should look like this"

```javascript
var rg = new RedOrGreen("myElement");

rg.makeGreen();
// myElements backgound color should be green now

rg.makeRed();
// myElements backgound should be red now
```

Create these files:
* red_green.js
* red_green_test.js
* red_green.html

**Remember to commit to GIT**

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
------------|-----------------------
tdd.js | The TestMyCode implementation will be in here
tdd_test.js | TestMyCode will be tested in here
tdd.html | Bring all the files together & test executed from here
tdd.css | Make the html look nice
tdd_hello_world.js | the function under test
red_green.js | reuse the function you wrote earlier

So let's use TDD to create this code.

* Copy the code from above into the `tdd_test.js` file
* Create `tdd.html`
 	* reference the html and css files from it.
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
	* if there is an error/exception: display a red square - use `try/catch` exception handling in javascript
* Use an object literal to create this.

**Refresh** `tdd.html` to see what errors you are getting.

In the `tdd_hello_world.js` file create a simple function that returns 'hello world!';

**Refresh** `tdd.html` to see what errors you are getting.

By now you should be close to having a small TDD framework that allows you to test your code.
Do you have a green block yet?
If not change your function to return the expected result, to make the block go green.
Try it with a different function other that the helloWorld one. Make sure that you can get a red block if the function returns an unexpected result.

**Remember to commit to GIT**

##T8 Unit Testing Framework

So you might not realise it, but you have now built a small Unit Testing framework. It has it limitations though - it can only test one function at a time, and it is not telling you what you are testing or how many tests have failed or passed.

**So now**

* Add support to run multiple tests:
	* one can add multiple tests in `tdd_test.js`
	* for each test added, a block should be displayed on the tdd.html screen
		* green for a passing test
		* red for a failing test
	* you will need to dynamically add elements to the DOM. Use this as a reference point: http://callmenick.com/2014/03/27/basics-javascript-dom-manipulation/

* Display which test passed or failed
* If a test fails display the error / exception on the screen in the block for the test
* Display how many tests passed or failed - only display this once.

**Once you think you are done** please review your testing implementation with your Tech Mentor

**Now head over to**

Now head over to [53 functions](https://github.com/codex-academy/53functions/blob/master/README.md) and write some functions. You should be using the Unit testing framework you created in Task 7 & 8 to test the first 5 functions.
