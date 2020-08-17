# Front-End Mod 1 Pre-work Guide

This repository will guide you through the Mod 1 Pre-work for the Front-End program at Turing.

Each day has a folder containing a `README.md` file with instructions for the day, exercises, and questions. You must complete all the exercises and questions.

## Pre-work Index

* [Section 1 - SUPER LEARNERS, Terminal and JavaScript Foundations](section1)
* [Section 2 - ASKING QUESTIONS, Conditionals and Functions](section2)
* [Section 3 - GROWTH MINDSET, Arrays and Iteration](section3)
* [Section 4 - Objects and Classes](section4)

## Materials

📒The only material, outside of your computer and an internet connection that you need to complete your pre-work is the `JAVASCRIPT & JQUERY: Interactive Front-End Web Development` book by John Duckett. You can [download it for free here](https://www.pdfdrive.com/javascript-and-jquery-interactive-front-end-web-development-e184606066.html) or [purchase a hard copy here](https://www.amazon.com/Web-Design-HTML-JavaScript-jQuery/dp/1118907442/ref=sr_1_2?ie=UTF8&qid=1541193719&sr=8-2&keywords=duckett) (or elsewhere).

>Please be aware, when page numbers for this book are referenced, it is the page number in the printed book. They don't quite match up with the ways the pages in the PDF are numbered, so make sure to reference the printed page number in the bottom corner of a page in the book.

Read this page thoroughly to find the instructions for getting your computer setup and getting started.

## Environment

### Install Node.js and NPM using homebrew

Before we're able to write JavaScript that can be run from the command line (you'll be doing this in Mod 1), we need to install `Node.js` and `NPM` and it'll be expected that you've run through these instructions.

These setup instructions assume that you have completed the setup for Mod 0, like installing Atom, xcode-select, Homebrew, git, and Chrome. If you haven't done that yet, please see [the mod-0 environment setup instructions](http://mod0.turing.io/setup-instructions).

### Install Node.js:

JavaScript was originally intended to be run in the browser (i.e., Chrome). But over time there were a lot of good reasons to allow it to be run server side. Node.js is a framework that allows us to to do just that.

Additionally, there's some very useful "packages" we use while writing code and we cannot install without first installing `node`.

#### Installation

Open a terminal with Spotlight search (`Command + Space`) and enter these commands:

```
$ brew update
```
Wait a few moments for `brew` to check its current version and make sure it is ready to be used.

```
$ brew install node
```
Wait again, as brew installs node.


Now enter:

```
$ node -v
```

This shows us what version of Node.js we are running. You should see _something_ like:

```
v12.8.0
```

That same install also installed `npm` for us which will allow us to download useful packages down the line.

Now enter:

```
$ npm -v
```

This shows us what version of NPM we are running. You should see something like:

```
6.10.3
```

## Terminal

We will be referencing many terminal commands throughout the pre-work. It is recommended that you practice using terminal commands before getting started. See the `terminal.md` lesson located in the `part1` directory.

### Forking the Module 1 Pre-work Repository

Next, we are going to *fork this repository that you're reading right now*. Forking is when you copy a GitHub repository to your GitHub account to make your own changes.

In this scenario, the [Turing GitHub account](https://github.com/turingschool) owns this `frontend-mod-1-prework-2008b` repository. You do not have permission to change anything in this repository, so you need your own copy to work on. In order to fork the repository, follow these steps:

####  1. Make sure you are logged in to GitHub (if you are not logged in, log in and come back to this page)

####  2. Scroll to the top of [*this* page that you're reading right now](https://github.com/turingschool-examples/frontend-mod-1-prework-2008b).

####  3. Click on `Fork` in the upper right corner of the screen and select your account as the destination

![click on 'fork' button, confirm fork to your account](/images/fork_01.jpg)

####  4. On the new page, confirm that it says it's the "forked" copy of this repository, with mentions of your username in the URL and repository name.

![confirm new repository belongs to _your_ github account](/images/fork_02.jpg)

## Clone down this new repository

Now that you have forked this repository, the next thing to do is *clone your forked repository*.

Cloning is when you copy a remote GitHub repository to your local computer.

#### 1. In YOUR `frontend-mod-1-prework-2008b` repository that your just forked, click on `Clone or Download`

![clone down your copy](/images/fork_03.jpg)

#### 2. If you see `Clone with HTTPS` click on `Use SSH`

#### 3. Click on the copy icon to copy the SSH link to your clipboard.

#### 4. Use your terminal to copy down this repository

1. Open your terminal

```
$ cd .
// This is a shortcut for `cd ~`, which is "change into the home directory"
$ mkdir turing
$ cd turing
$ mkdir 0module
$ cd 0module
$ git clone <ctrl-v to paste ssh link here >
Cloning into 'frontend-mod-1-prework-2008b'...
remote: Enumerating objects: 678, done.
remote: Total 678 (delta 0), reused 0 (delta 0), pack-reused 678
Receiving objects: 100% (678/678), 237.94 KiB | 851.00 KiB/s, done.
Resolving deltas: 100% (332/332), done.

$ cd frontend-mod-1-prework-2008b
$ git status .
// If everything worked correctly, you should see:
On branch master
nothing to commit, working tree clean
```

From here on out, all the work you do will be in your copy of this repository. Other text you read here might refer to this as the "prework repository" or "frontend prework", and they all refer to your forked copy of this `frontend-mod-1-prework-2008b` repository.

## Get Started

Each day's `README` will walk you through the steps you need to take to save your work.

To start, in your terminal, `cd` into the `section1` directory. Follow the instructions contained in the `README.md` file, and have a great time learning and exploring!
