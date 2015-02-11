#Let's code!

Now we are going to write some code outside of Codecademy.

In your projects folder:
* create a folder called RedAndGreen
* change into the folder RedAndGreen using ```cd RedAndGreen```
* initialize it as a git repository using this command ```git init```
* create all the files below in that folder
* after each task remember to add your changes to git

## Task 1

> This task requires HTML & CSS

In a file called task1.html create two squares that is 300px by 300px with a black border that is 5px thick.
The first square should be green and the second square should be red. Be sure that your HTML file is properly formed, you can use the basic html template from Sublime Text for this as described above.

> For this task create the CSS in a style tag in the head of the html file file

**The HTML should look look something like this**

```
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
* ```git status``` to see what changed
* ```git add .``` to add everything to git
* ```git commit -m "task 1 is done"``` to commit your changes to git

## Task 2

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
Finding DOM element - like a DIV element based on a ID name | ```var element = document.getElementById('id')``` |  http://www.w3schools.com/js/js_htmldom_elements.asp
Styling elements from Javascript | ```element.style.backgroundColor = 'red';``` | http://www.w3schools.com/jsref/dom_obj_style.asp
Styling elements from Javascript | ```element.addEventListener('click', function(){});``` | http://www.w3schools.com/jsref/prop_style_backgroundcolor.asp
What is the DOM?   | |http://eloquentjavascript.net/13_dom.html

In a file called task2.html create a html page:
* That display two white squares that is 300px by 300px with a black border that is 5px thick.
* create a button underneath each square. 
* the button text under the first square should be 'Make green' and 'Make red' under the second square. 
* when the button under the first square is pressed it should make the  first square green. 
* when the button under the 2nd square is pressed the 2nd square it should make the button green.

**The HTML should look look something like this**
```
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
* ```git status``` to see what changed
* ```git add .``` to add everything to git
* ```git commit -m "task 2 is done"``` to commit your changes to git

## Task 3

> This task requires HTML, CSS & Javascript

Create 3 files:
* task3.html - all html in here	
* task3.css - all css in here
* task3.js - all javascript in here

Using the above 3 files create a web page:

* that display a white square that is 300px by 300px with a black border that is 5px thick
* add two buttons under the square one with text 'Make green' the other with 'Make red' 
* when the respective buttons are pressed they should make the square their respective colors.

**The html should look like this**
```
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

Once done add your changes to git by using the same commands as you used for the tasks above

## Task 4

> This task requires HTML, CSS & Javascript

Using seperate file fon html, css & javascript called task4.html, task4.css & task4.js create a web page:

* that displays a green square that is 300px by 300px with a black border that is 5px thick.
* add one button under the square one with text 'Make red' 
* when the buttons is pressed the square should go red
* the button text should change to 'Make green'
* when pressed the square should go green
* only for the button text to change to 'Make red'
* upon which pressed the square goes red
* this process should be repeated over and over

Once done add your changes to git by using the same commands you used above.

## Task 5

In all the tasks above we tested our code by running it in the browser and seeing if it worked as it should have.
I will introduce you now to a better way - you will help the computer to decide if things are working as they should od not. This way of programming is called Test Driven Development and it use a Red & Green coding cycle.

In this Task you need to write a function called, setBackgoundColor it takes two parameters the id of the element who's background color is to be set and then the color it should be set too.

Calling this function looks like this: ```setBackgoundColor('mySquare', 'orange');```

TDD starts like this:

* write some code that use the code that you would like to write
* run this code
* everything should fail horribly the code you are calling doesn't exist yet!
* the state of the test is 'red'

**Ok let's do that quickly:**

Create files called:
* task5.html
* two javascript files calles task5.js & task5_tests.js.

The html file should reference the two seperate javascript files. The one Javascript file will contain our function implementation and the other the test code.

The html file should should reference function implementation file before the test file - as the javascript files are loaded from top to bottom

```
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

** In the task5_tests.js file **
* we need to check the current color of the background of the 'mySquare' is green, we can use the DOM to do that
* now call the ```setBackgoundColor('mySquare', 'red');```
* now we check that the background of 'mySquare' set to red
* Use the alert function to display 'success' if the background color of 'mySquare' is equal to green, otherwise display 'failure'

**It should fail now!**
> Use Chrome developer tools' console to see why it's failing

**In the task5.js file:**
* create an implementation for the ```setBackgoundColor``` function
	* remember it takes 2 parameters
	* first one the element name
	* second one the color to set the background to
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
