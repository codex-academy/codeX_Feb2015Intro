---
layout: default
---

# Software to install

## Installing from the command line, using a package manager

As you already know, the command line allows us to run programs to complete some tasks. One of those tasks is installing new software on your computer.

Ubuntu has a package manager called `apt-get` which allows you to easily install software on a server or PC. 'Package' refers to all the files in the program you install on the computer.

In a terminal window on Ubuntu type `apt-get` and press enter. What do you see?

> Using `sudo` we can install software as administrator. It will prompt you for a password

Before you do anything else, execute this command:

```
sudo apt-get update
```

This tells `apt-get` to `update`: get information on the newest versions of packages.

Now let's use `apt-get` to install some software that we will need using the `apt-get install <package-to-install>`:

* `sudo apt-get install git`
* `sudo apt-get install nodejs-legacy`
* `sudo apt-get install npm`

## Installing binaries:

Sometimes we need to download and install programs directly, rather than using `apt-get`. On Ubuntu these files normally have a `.deb` extension.

Note: There will be a flash drive available so that you don't need to download these programs.

Install [Google Chrome browser](https://www.google.co.za/chrome/browser/desktop/index.html). It has great developer tools that we'll be using.

Now let's install the [Atom Editor](http://atom.io/).

[How to install Atom editor in Ubuntu 14.04](https://codeforgeek.com/2014/09/install-atom-editor-ubuntu-14-04/) has instructions for the best way to do this. They are:

1. Add the repository

```
sudo add-apt-repository ppa:webupd8team/atom
```

2. Update the repository

```
sudo apt-get update
```

3. Install Atom

```
sudo apt-get install atom
```
