# codeX February 2015

A big welcome to Project codeX! We hope that you will enjoy this journey with us and that you will learn and apply lots of new skills in the process. Arriving at codeX you might wonder where is the class rooms? There are non! It is just you, your fellow coders and us your mentors and the BIG world wide web.

## Assumptions

This introduction assumed that you have completed both the HTML/CRedSS & Javascript courses in Codecademy, if you haven't yet it's not train smash! Just head over there and complete them before you go any further.

## Now what?

After completing all those courses in Codecademy you must be feeling quite chuffed wit yourself and you have good reason too! You put in the hours, you argued your way through the challenges and you have the badges to show. No we are going to remove the side wheels a bit, things might start feeling a bit unstable. You will be unsure what code to use where, but this is all pretty normal. Just to prove to you that you are not alone in [read this quickly](http://www.vikingcodeschool.com/posts/why-learning-to-code-is-so-damn-hard).

So now you know that you are not alone let's get going.

## Overview

### Register

So we would like you to register for a few online  that we will be using at codeX. 

Please register on there and familiarise yourself with these tools.

So quickly go and register at:
* http://www.github.com
* http://stackoverflow.com
* http://twitter.com

## The command line

As a skilled software developer you need to get familiar and comfortable with the command line or terminal as it is called on Ubuntu. The terminal is the big scary black screen with a blinking cursor, waiting for you to tell it what to do. Yes initialy this is a bit scary I know. But once you get more familiar with it and master a few basic commands it will be much less scary. And over time as you learn more and more command you will realise the power of the terminal.

Let's try out the terminal window, open a terminal window and let's try out a few commands.

* type ```pwd``` then press enter - what does it do?
* type ```ls``` then press enter - what does it do?
* type ```mkdir the_terminal``` then press enter - what does it do?
* type ```ls``` then press enter - to see what you just did?
* type ```cd the_terminal``` then press enter
* now try ```pwd``` & ```ls``` again
* you can use the ```touch``` command to create a new file in the folder you created.
* to create a new fille called 'my_file.txt' type ```touch my_file.txt```
* you can now edit that file from the command line using a text editor called nano
* to edit the text file you created type ```nano my_file.txt``` in the terminal
* edit the file - add 'hello cape town' in the file and save the content of the file.
* now exit nano
* you should be back in the terminal now.

Congratulations you are now well on your way on mastering the command line.

Now hop over http://linuxsurvival.com, and complete the first Modules 1 & 2. 

Complete Module 3 & 4 in your own time later, this will help you along even further to deepen your knowledge of the command line.

## Install these software

As you already know the command line allows one to run programs to complete some tasks, one of those tasks is installing new software on your computer. Ubuntu have a utility called ```apt-get``` that allows you to install software on your laptop

Give it a go by typing ```apt-get```

If you type ```apt-get```....

Now let we install some software that we will need using the ```apt-get install command```:

* ```apt-get install git```
* ```apt-get install nodejs-legacy```
* ```apt-get install npm```

## Install these programs:

There will be a flash drive avialable so that you don't need to download these programs.

* Sublime Text
* Eclipse

## Git - Version Control

As a software developer you will be writing your code in files and you will not only be doing that on your own, but with other team members. So you will need some way of keeping track what you have done and what your team mates have done. Have you ever lost your changes in a Word document or text file, because you lots the USB Drive or because you over written some file by accident? These are the kind of things that might start to happen as you start to write code. Luckily there are a categoty of tools called Version Control tools - that allows you to manage the files that you create and change everyday as a software developer. It allows you to manage your own files, but also to share your files and changes to your files with your collegues and even other people on the internet.

The version control software we will be using is called ```git``` and to publish and share your code on ```http://github.com```. You will get to know git and github well in the next few months.

To get a quick introduction to github do the online tutorial at: https://try.github.io

Once you have a better idea of what git is all about try it on you local machine by following the instructions that are here: https://github.com/jlord/git-it

Now you should no alot more about version control using, git. Should you ever have any questions you can refer back to the resources above and the usefull guide at: http://jlord.us/git-it/ or there is always google.

## Let's code

So far most of the code you might have been written inside of Codecademy, that is a about to change. It reality most software is written in text editors or a more adanced text editors called and Integrated Development Environment or IDE for short. We will use a text editor called, Sublime Text and later you will be introduced to an IDE called Eclipse.

### Debugging

As you write software you will make mistakes alot, some times it will be easy to find a problem or bug, some times you will struggle... some times will find it easily. Relax! This is an integral part of programming... It will drive you semi insane, but it is a skill you need to master.

A bug in software development refers to a problem, if a program have a bug it means that it have an issue that stop it from working or that makes it work sub-optimally. Finding bugs in Javascript can sometimes be hard and a bit frustrating to say the least. Luckily the Chrome web browser come with some tools that goes a long way in assisting one in finding problems in ones program.

####The Chrome developer tools include:
* Developer Tools
* Javascript Console

To access them:

* click on the three lines, right of the address bar
* then click 'More tools' 
* 'Developer Tools' and 'Javascript Console' is two of the options that should be available.
* by clicking either one of them a screen will appear at the bottom of the screen in Chrome. 
 
This will allow you to do various usefull things such as:
* Identify HTML Elements by clicking in the browser
* See which CSS tags are affecting a specific element
* Switch of the CSS styling at affects the selected element
* Look at the Javascript source code used by your web page
* Add a breakpoint in Javascript sourcecode

This is just to mention a few of the things you can do in Google Developer tools. Other browsers have similar capabilities, but some times you need to install a browser plugin. In Firefox you can install the excellent Firebug plugin to get developer support. 

### Sublime Text

Sublime Text editor is a text editor with lots of nice features that makes your life as a developer much easier.

A few of those features includes:
* Basic code completion - based on content in your file
* Syntax highligting
* Html tag completion
* Html file basic templates

Let's try some things:

* Create a file called index.html in Sublime text
* At the first line in the file type ```html```
* Now press 'tab'
* What happened?
* Save the file...
* Now in the body tag type ```h1```
* Press press 'tab' again
* What happened?
* In the body of the tag you just created type 'Hello World!'

### Write some code!

Now we are going to write some code outside of Codecademy.

In your projects folder:
* create a folder called RedAndGreen
* change into the folder RedAndGreen using ```cd RedAndGreen```
* initialize it as a git repository using this command ```git init```
* create all the files below in that folder
* after each task remember to add your changes to git

#### Task 1

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

#### Task 2

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

#### Task 3

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

#### Task 4

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

#### Task 5

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



### Javascript on the command line

So far all the Javascript that you wrote was running inside of the web browser, by using node js, or node just for short, you can run javascript programs from the terminal, without the need for a web browser. This allows you to use Javsscript to write some programs that does not depend on the web browser such as accessing data in a database for example.
