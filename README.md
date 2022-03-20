# First Contributions

| <img alt="RStudio" src="assets/rstudio-logo.png" width="300"> | RStudio Edition |
| ------------------------------------------------------------- | --------------- |

This repo is a chopped-up, trimmed-down, and customised-for-RStudio version of the amazing [first contributions](https://github.com/firstcontributions/first-contributions) repo (and is not officially affiliated with RStudio). Check out the original repo for instructions using other tools and language translations.

---

## Before You Start

You can choose you preferred language to learn more about RStudio and this project.

-   [German](https://github.com/forwards/first-contributions/blob/master/Languages/German.md)
-   [Italian](https://github.com/forwards/first-contributions/blob/master/Languages/Italian.md)
-   [Spanish](https://github.com/forwards/first-contributions/blob/master/Languages/Spanish.md)

---

## Introduction

It's hard. It's always hard, when you do something for the first time. Especially when you are collaborating, making mistakes isn't a comfortable thing. But open source is all about collaboration & working together. We wanted to simplify the way new open-source contributors learn & contribute for the first time.

Reading articles & watching tutorials can help, but what comes better than actually doing the stuff without messing up anything. This project aims at providing guidance & simplifying the way rookies make their first contribution. Remember the more relaxed you are the better you learn. If you are looking for making your first contribution just follow the simple steps below. We promise you, it will be fun.

---

## What this will teach you

-   How to fork a repo
-   How to make a branch
-   How to submit a pull request to the original repo

---

## What this won't teach you

-   How to build R packages
-   Open source etiquette

---

## Assumptions

I have made a number of assumptions in writing this guide:

-   You have a GitHub account
-   You have [RStudio](https://www.rstudio.com/products/rstudio/download/#download) installed.
-   You have [git](https://git-scm.com/downloads) installed and your [identity configured](http://happygitwithr.com/hello-git.html). If you can push to GitHub, you've already done this :)
-   You are comfortable using git with RStudio. If you want to improve your knowledge, I'd recommend working through ['Happy Git and GitHub for the useR'](http://happygitwithr.com/) first.

OK, let's get started!

---

## Fork this repository

Fork this repo by clicking on the fork button on the top of this page.

---

<img width="300" src="assets/fork.png" alt="fork this repository" style = "display: inline;"  />
<br/>

This will create of copy of this repository in your account and you will be redirected to this version of the repo.

You now need to get the URL for your repo. Click "Clone or download" and copy the URL in the box.

<img width="300" src="assets/rstudio-gh-clone.png" alt="clone the repo" style = "display: inline;"  />
<br/>

---

## Create a new project

In RStudio, go to File -> New Project

Select "Version Control" and then "Git".

In the New Project dialog, paste the URL you copied from GitHub into the "Repository URL" box.

Choose the name you want the directory on your computer to be called, and put it in the "Project directory name" box. By default, this is the name of the repo.

Finally, choose where you want the cloned repo to be stored by clicking the "Browse" button.

Once you have finished, click "Create Project" to clone the repo and set up the project.

<img width="300" src="assets/rstudio-clone.png" alt="Git"  style = "display: inline;"  />
<br/>

The repo will now be cloned into whichever folder you specified.

---

## Create a branch

In the "Git" tab in the top-right panel, click the "new branch" button.

<img width="500" src="assets/git-tab-location.jpg" alt="Git tab"  style = "display: inline;"  />
<br/>
<img width="300" src="assets/rstudio-new-branch-button.png" alt="Create a new branch"  style = "display: inline;"  />
<br/>

Name your branch "add-your-name", for example: "add-nic-crane"

<img width="300" src="assets/rstudio-new-branch-button2.png" alt="name your branch"  style = "display: inline;"  />
<br/>

Make sure that "Sync branch with remote" is checked and click "Create". You may be asked to enter your GitHub username and password.

---

## Make necessary changes and commit those changes

Now open the `Contributors.md` file in RStudio and add your name to it, then save the file.

You will see that the file has an 'M' next to it. Check the box next to it and then click "Commit".

<img width="300" src="assets/rstudio-add.png" alt="name your branch"   style = "display: inline;"  />
<br/>

You'll see a diff file showing the changes you've made to the file. Add a commit message - a summary of changes you've made, and then click "Commit". A box will pop up to confirm the commit; click "close".

<img width="400" src="assets/rstudio-commit-message.png" alt="name your branch"   style = "display: inline;"  />
<br/>

---

## Push changes to GitHub

Congratulations, you've committed all the changes to your local copy of your branch of your fork of first-contributions. Now click "Push" to sync your commit to the remote repo.

<img width="500" src="assets/rstudio-push1.png" alt="name your branch"   style = "display: inline;"  />
<br/>

You'll see a box like this if your changes have been pushed successfully. Click "Close".

<img width="400" src="assets/rstudio-push2.png" alt="name your branch"   style = "display: inline;"  />
<br/>

---

## Submit your changes for review

If you go to your repository on github, you'll see a "Compare & pull request" button. Click on that button.

<img width="500"  style = "display: inline;" src="assets/compare-and-pull.png" alt="create a pull request"   />
<br/>

Make sure that you are comparing across forks. On the left should be the master branch of the original repo, and on the right should be the new branch you've made in your repo. Once you've got the correct options selected and have written a quick summary of the changes made, submit the pull request by clicking "Create pull request".

<img width="500" style = "display: inline;" src="assets/submit-pull-request.png" alt="submit pull request"   />
<br/>

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged!

Congrats! You have just completed the standard _fork -> clone -> edit -> PR_ workflow that you'll encounter often as a contributor!
