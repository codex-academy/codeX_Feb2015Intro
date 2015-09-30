# Let's code!

Now we are going to write some code outside of Codecademy.

You should have a projects folder in your home directory, it's good practice to create all your different projects in one place on your PC that you can find easily.

In your projects folder:

* create a folder called RedAndGreen
* change into the folder RedAndGreen using `cd RedAndGreen`
* initialize it as a git repository using this command `git init`

In GitHub create a new repository called 'RedAndGreen':

* to do that click on the + sign left from your profile name
* now select 'New repository'
* enter the repository name 'RedAndGreen'
* now click 'Create repository'

You will be presented with a few different setup options, you need to follow the instructions under:

> ...or push an existing repository from the command line

the parameters will be specific to your environment and you can copy and paste them into your RedAndGreen local directory in the terminal.  

The command would look like this, with your own git username:

```
git remote add origin git@github.com:<username>/RedAndGreen.git
```

As you do each task create the files in the 'RedAndGreen' folder.

After each task remember to commit your changes using git.

## RedandGreen Tasks  

We'll be making some web pages with HTML, CSS, and JavaScript. Have a quick look at [the web triangle](the-web-triangle.md) for some information about the structure of web pages.

Your first task is to create red and green blocks using HTML and CSS, and push your work to GitHub. For task 2 you'll write some JavaScript to colour the squares when you click buttons. For task 3, you'll build on that by using two buttons and having just one square changing colours.

* Task 1: [create red and green blocks](create-red-and-green-blocks.md)
* Task 2: [colour the block](colour-the-blocks.md)
* Task 3: [colour the block with buttons](colour-the-block-with-buttons.md)
* Task 4: [one block changing colours](one-block-changing-colours.md)

### Short break from the JavaScript

Let's [publish your code to a website](publish-your-code-to-a-website.md) using GitHub Pages, so that you can easily demo your work.

Add a file called `index.html`. Inside it, make a list of links to the pages you made from task 1, 2, 3, and 4. Add some CSS to make it look more interesting. You might want to look at [list-style](https://developer.mozilla.org/en-US/docs/Web/CSS/list-style) and  [list-style-type](https://developer.mozilla.org/en-US/docs/Web/CSS/list-style-type). Add a link to `index.html` at the bottom of each html file.

Let's learn a bit more about another part of git: [ignoring files](gitignore.md).

### Back to the JavaScript!

For task 5, you're going to use one button to change the square's colours back and forth. For task 6, you're going to (by writing more code!). For task 7, you're going to write JavaScript in a slightly different way, and test changing colours.

* Task 5: [one button to change the blocks's colours](one-button-to-change-block-colours.md)
* Task 6: [test your function](test-your-function.md)
* Task 7: [test changing colours](test-changing-colours.md)

### Short break from the JavaScript

Update your `index.html` to link to your task 5, 6, and 7 pages. Add a link to `index.html` at the bottom of each html file.  

Now let's [republish your work to the web](republish-your-work-to-the-web.md) using GitHub Pages.

### Back to the JavaScript!

In task 8 you'll be adding blocks to the page using JavaScript. For task 9, you're going to start writing a framework to make testing your code easier, and you'll write code that lets you display test results. For task 10, you'll expand on your framework and end up with your own Unit Testing Framework.

* Task 8: [add blocks to the page](add-blocks-to-the-page.md)
* Task 9: [display test results](display-test-results.md)
* Task 10: [Unit Testing Framework](unit-testing-framework.md)

## Bite-sized Code Challenges

Now head over to [53 functions](https://github.com/codex-academy/53functions/blob/master/README.md) and write some functions. You should be using the Unit testing framework you created above to test the first 5 functions.
