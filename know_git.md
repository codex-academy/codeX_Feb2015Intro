---
layout: default
unitstandard: 115362-SO1-AC1, 115362-SO1-AC2, 115362-SO2-AC1, 115362-SO2-AC3
---

## Git - Version Control

As a software developer you will be writing code not only on your own, but with other team members. You will need some way of keeping track of what you have done, and what your teammates have done, and making sure that you don't overwrite each other's changes.

Have you ever lost your changes in a Word document or text file, because you lost the USB Drive or because you saved over a file by accident? These are the kind of things that might start happening as you start to write code.

Luckily there's a category of tools called VCS (Version Control Software) which allows you to manage the files that you create and change everyday as a software developer. You can manage your own files, share your files and changes with your colleagues, and even share them other people on the internet.

* The Version Control Software we will be using is called git. This program will run on your laptop. Git is a distributed VCS. That means that everyone working on the code keeps a copy of it on their own machine. There's often a copy in a central, shared, location too.
  * Create a new folder called `Projects` in your home directory, using the terminal. Each new project you start should live in its own directory inside of your `Projects` folder. In git terminology, the code for each project is called a repository.
* [GitHub](http://github.com) is the site where you will publish and share your code on the web. Your code will live at `http://github.com/<your-github-user-name>/<your-repository-name>`.

You will get to know git and GitHub well in the next few months!

### Some Exercises

To get a quick introduction to GitHub, do the online tutorial [Try GitHub](https://try.github.io).

Once you have a better idea of what git is all about, try it on your local machine by following the instructions at [Git It](https://github.com/jlord/git-it). The steps there will show you how to get code from GitHub to your machine, how to update code using git, and many other things.

<!--codex ignore refer back-->
Now you should know a lot more about version control using `git`. You'll always follow the same cycle for updating your code:

  * Make changes to your file(s);
  * `git add` the changed files;
  * `git commit` the changes, with a message;
  * `git push` the commited changes from your machine to GitHub.

Should you ever have any questions you can refer back to the info on this page, as well as the useful Git It guide... or there is always Google!

### SSH Key

Are you still typing in your username and password when you `git push` to GitHub? If so, let's fix that by [Adding a new SSH key to your GitHub account](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/#platform-linux). Once that's done, you can `git push` and your code will fly from your machine to the internet.
