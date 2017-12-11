# [Contribute To This Project](https://syknapse.github.io/Contribute-To-This-Project/) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Contribute%20To%20This%20Project%20by%20@Syknapse&url=https://github.com/Syknapse/Contribute-To-This-Project&hashtags=100DaysofCode)

## Introduction

This is a tutorial to help first-time contributors to participate in a simple and easy project.

### Objectives

+ Make a contribution to an open source project.
+ Get more comfortable using GitHub.

### Who is this for?

+ This is for absolute beginners. If you know how to write and edit an anchor tag `<a href="" target=""></a>` then you should be able to do it.
+ It is for those with a little more experience but who want to make their first open source contribution, or get more contributions for more experience and confidence.

### Why do I need to do this?

Any web developer, aspiring or experienced needs to use Git version control, and GitHub is the most popular Git hosting service used by everyone. It is also the heart of the Open Source community. Getting comfortable using GitHub is an essential skill. Making a contribution to a project boosts your confidence and gives you something to show on your GitHub profile.

## What am I going to contribute?

![Contributor Card](readme-only/card.PNG "Contributor Card")

You are going to contribute a card just like this one to this project's web page. It will include your name, a photo, your Twitter handle, a short description, and 3 links to useful resources for web developers that you recommend.

You will make a copy of the card template inside the HTML file and customise it with your own information.

## Setup

First let's get setup to do the work

1. Login to your GitHub account. If you don't yet have an account then [join GitHub](https://github.com/join). I recommend that you do the [GitHub Hello World tutorial](https://guides.github.com/activities/hello-world/) before you continue.
1. Download [GitHub Desktop app](https://desktop.github.com/).
    + Alternatively if you are comfortable using Git on the command line you can do so (here's [first-contributions](https://github.com/Syknapse/first-contributions), a similar project that can serve as a guide for the commands needed). OR 
    + If you use VS Code it comes with integrated Git and allows you to do what we need straight from the editor.
    + However the simplest and easiest way to follow this tutorial is using GitHub Desktop.

Now that you are all setup let's get on with the business of contributing to the project.

---

---

## Contribute

Become an open source contributor in 10 easy steps.

_Estimated time: Less than 30 minutes_.

### Step 1: Fork this repository

+ The objective here is to make a copy of this project and place it in your account.
+ A repository (repo) is how a project is called on GitHub and a fork is a copy of it.
+ Make sure you are on the [main page](https://github.com/Syknapse/Contribute-To-This-Project "https://github.com/Syknapse/Contribute-To-This-Project") of this repo.

| <li>Click on _Fork_ at the top left of the page</li> | ![Fork](readme-only/fork.PNG "click on 'Fork'") |
|:---|---:|

+ You now have a complete copy of the project in your own account

---

### Step 2: Clone the repository

+ Now we want to make a local copy of the project. That is a copy saved on your own machine.
+ Open the GitHub desktop app.

| <li>At the top left corner, click on _File_ then _Clone repository_</li> | ![Clone](readme-only/clone.PNG "click clone repository") |
|:---|---:|

| <ul><li>You will see a list of your projects and forks on GitHub.</li><li>Select `<your-github-username>/Contribute-To-This-Project`.</li><li>Your fork will have your own GitHub user name.</li><li>Then click _Clone_</li></ul> | ![Clone project](readme-only/clone-project.PNG "click on <your-github-username>/Contribute-To-This-Project") |
|:---|---:|

+ This will take a moment as the project is copied to your hard disk. I recommend that you keep the default path which is usually `..\Documents\GitHub`.
+ Now you have a local copy of the project.

---

### Step 3: Create a new branch

+ Once the repo has been cloned and you have it open in GitHub desktop it is time to create a new branch.
+ A branch is a way to keep your changes separate from the main part of the project called `Master`. For example if things go wrong and you are not happy with your changes you can simply delete the branch and the main project won't be affected.

| <ul><li>Click on _Current branch_ at the top center</li><li>Then click on _New_</li></ul> | ![Create branch](readme-only/branch-new.PNG "Click on 'Branch', then 'New'") |
|:---|---:|

| <ul><li>Give your branch a name</li><li>You can name it whatever you want, but since this is a branch to add a card with your name to the project, calling it `your-name-card` is good practice to make the intention of this branch clear</li></ul> | ![Name branch](readme-only/branch-name.PNG "Name your branch") |
|:---|---:|

+ Now you have created a new branch separate from the master.
+ For the next steps make sure you are working in this branch. You will see the name of the branch you are on at the top center of the GitHub desktop app.

---

### Step 4: Open the index.html file

+ Now we need to open the file we are going to add code to with your favourite code editor.
+ Find the project folder on your computer. If you have kept the default this should be something like `your-computer > Documents > GitHub > Contribute-To-This-Project`

| <ul><li>Open your code editor (Sublime, VS Code, Atom..etc) and use the `Open file` command and locate the index.html file in the main directory of the project</li><li>Alternatively you can locate the file on your hard drive, right click, and open with your editor</li></ul> | ![Open index file](readme-only/index-open.PNG "Open index.html in your text editor") |
|:---|---:|

+ Now you have the file you are going to edit open in your editor and you are ready to start making changes to it. 

---

### Step 5: Copy the card template

+ We will make a copy of the card template to start working on it

| <ul><li>Scroll down towards the end of the file where you will find the section labeled `== TEMPLATE ==`</li><li>Copy everything within the red square in the image, from the `Contributor card START` comment to the `Contributor card END` comment</li></ul> | ![Copy card template](readme-only/card-copy.PNG "Copy the card template") |
|:---|---:|

| <ul><li>Paste the whole thing directly above the comment indicating it</li><li>Make sure there is a single line of space between your card start and the last card end. It's good practice to keep our code as clear as possible</li><li>Make sure your indentation is correct and matches the template</li></ul> | <img src="readme-only/card-paste.PNG" alt="Paste card template" style="width: 2500px" title="Paste above the indicated line"/>  |
|:---|---:|

+ This now is **your** card for you to customise and edit.

---

### Step 6: Apply your changes

+ We will now start changing the customizable fields in our card

|  | ![Change image]() |
|:---|---:|

| instructions | ![Change name](readme-only/change-name.PNG "Type your name") |
|:---|---:|

| instructions | ![Change contact](readme-only/change-contact.PNG "Insert a link to your Twitter account and type your handle") |
|:---|---:|

| instructions | ![Change about](readme-only/change-about.PNG "Write a sentence about you") |
|:---|---:|

| <ul><li>item1</li><li>item2</li></ul> | ![Change resources](readme-only/change-resources.PNG "Insert link, write a short description, and type the name of the resource") |
|:---|---:|

---

### Step 7: Commit your changes

| instructions | ![Commit changes](readme-only/commit.PNG "The changes you've added should appear in green on the right side of GitHub desktop app. The commit button is on the buttom left") |
|:---|---:|

| instructions | ![Write commit message and commit](readme-only/commit-message.PNG "Write a brief commit message in the 'summary' input, and click 'commit'") |
|:---|---:|

---

### Step 8: Push your changes to GitHub

| instructions | ![Push to GitHub](readme-only/push.PNG "Push your changes to GitHub, click on the 'Push' button") |
|:---|---:|

---

### Step 9: Submit a PR

| instructions | ![Submit a Pull Request](readme-only/#####.PNG "////////////") |
|:---|---:|

---

### Step 10: Celebrate!

That's it. You have done it! You have now contributed to open source on GitHub.

You have added code to a live web page: https://syknapse.github.io/Contribute-To-This-Project

Your changes **won't be visible immediatly**, first they have to be merged by the project maintainer. Once they are merged your card should be visible and live on the page. I will try to make the merges as soon as possible but a couple of days delay might be expected sometimes.

---

---

## Next Steps

+ Come back in a while to check for your merged Pull Request.
+ If you found this project useful please give it a star at the top of the page and Tweet about it to help spread the word [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Contribute%20To%20This%20Project%20by%20@Syknapse&url=https://github.com/Syknapse/Contribute-To-This-Project&hashtags=100DaysofCode)
+ You can follow me and get in touch on [Twitter](https://twitter.com/Syknapse "@Syknapse") or [using any of these other options](https://syknapse.github.io/Syk-Houdeib/#contact "My contact section | Portfolio")
+ This is an open source project so apart from contributing your card you are welcome to help fix bugs, improvements, or new features. Open an [issue](https://help.github.com/articles/creating-an-issue/ "Mastering Issues | GitHub Guides") or send a new [pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/ "Creating a pull request from a fork | GitHub Help")
+ Thanks for contributing to this project. Now you can go ahead and try contributing to other projects; look for the first-contribu?? label

## Acknowledgements

This project is heavily influenced by [Peter Lazar's](https://github.com/peterlazar1993) great [first-contributions](https://github.com/Syknapse/first-contributions) project with it's excellent tutorial.

It is also particularly inspired by the great community around [#GoogleUdacityScholars](https://twitter.com/hashtag/GoogleUdacityScholars?src=hash) The Google Challenge Scholarship: Front-End Web Dev, class of 2017 Europe. 

## Licence

[MIT License](https://github.com/Syknapse/Contribute-To-This-Project/blob/master/LICENSE)