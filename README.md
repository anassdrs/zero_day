[

](https://intranet.alxswe.com/)

-   [
    
    My Planning
    
    ](https://intranet.alxswe.com/planning/me)
-   [
    
    Projects
    
    ](https://intranet.alxswe.com/projects/current)
-   [
    
    QA Reviews I can make
    
    ](https://intranet.alxswe.com/corrections/to_review)

___

-   [
    
    Curriculums
    
    ](https://intranet.alxswe.com/dashboards/my_curriculums)
-   [
    
    Concepts
    
    ](https://intranet.alxswe.com/concepts)
-   [
    
    Conference rooms
    
    ](https://intranet.alxswe.com/dashboards/video_rooms)
-   [
    
    Servers
    
    ](https://intranet.alxswe.com/servers)
-   [
    
    Sandboxes
    
    ](https://intranet.alxswe.com/user_containers/current)
-   [
    
    Video on demand
    
    ](https://intranet.alxswe.com/dashboards/videos)

___

-   [
    
    Peers
    
    ](https://intranet.alxswe.com/users/peers)
-   [
    
    Captain's Logs
    
    ](https://intranet.alxswe.com/dashboards/my_captain_log)

___

-   [
    
    Slack
    
    ](https://alx-students.slack.com)
    
    [
    
    Discord
    
    ](https://discord.com/app)
    
    [
    
    My Profile
    
    ](https://intranet.alxswe.com/users/my_profile)
    

**We're moving to Discord!** In a few days, we will be leaving Slack in favor of Discord 🎉 [Click here for more information](https://intranet.alxswe.com/concepts/100033)

# \[Optional\] Vagrant

DevOpsVirtual machine

-   By: Julien Barbier
-   Weight: 1
-   Project will start Sep 25, 2023 6:00 AM, must end by Sep 30, 2023 6:00 AM
-   Checker was released at Sep 25, 2023 6:00 AM
-   An auto review will be launched at the deadline

### Concepts

_For this project, we expect you to look at this concept:_

-   [Using Vagrant on your personal computer](https://intranet.alxswe.com/concepts/81)

## Vagrant - or - how to code in your local computer

Sandboxes are great, but you can also do your ALX assessments on your local computer - having a virtual machine (VM) is the perfect tool for that.

Let’s dig into **Vagrant** today!

Also:

-   This project is **100% optional**
-   This project **can’t be done in Sandboxes** - it can be done only in your local computer.

## Resources

**Read or watch**:

-   [Virtual machine](https://intranet.alxswe.com/rltoken/eoV8V_5fgzW_UhJ3PtVyWw "Virtual machine")
-   [man uname](https://intranet.alxswe.com/rltoken/Z4MowYniH5YJoZo4jZgIBw "man uname")

## Learning Objectives

At the end of this project, you are expected to be able to [explain to anyone](https://intranet.alxswe.com/rltoken/g5OVhHRsT0jjsvUI1Y8jgw "explain to anyone"), **without the help of Google**:

### General

-   What is a virtual machine
-   What is Vagrant
-   Who wrote Vagrant
-   What is Ubuntu
-   What does “Ubuntu” mean
-   How to use VMs with Vagrant
-   What does the command `uname` do

### Copyright - Plagiarism

-   You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
-   You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
-   You are not allowed to publish any content of this project.
-   Any form of plagiarism is strictly forbidden and will result in removal from the program.

## Requirements

### General

-   A `README.md` file at the root of the repo, containing a description of the repository
-   A `README.md` file, at the root of the folder of _this_ project (i.e. `0x00-vagrant`), describing what this project is about

## More Info

### Install `git`

If `git` is not already installed on your terminal:

```
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
```

### Basic usage

At the end of this project you should be able to reproduce and understand these command lines:

```
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main
```

### Warning

This project **can’t be done in Sandboxes** - it can be done only in your local computer. Please refer to our concept pages for your operating system.

### Quiz questions

**Great!** You've completed the quiz successfully! Keep going! (Hide quiz)

#### Question #0

Ubuntu is a \_\_\_\_ distribution.

-   Linux
    
-   Windows
    
-   MacOS
    

#### Question #1

What is a virtual machine?

-   A system for developing virtual reality
    
-   A set of servers for software development
    
-   An emulation of a computer system
    

## Tasks

### 0\. Create and setup your Git and GitHub account

#advanced

You will need Git for this project, you might have to [install it](https://intranet.alxswe.com/rltoken/7kPsched1VMPOY2bdvZvGQ "install it") on your computer if it’s not done yet.

-   Configure your basic info (name, email) on your local machine – they will be part of your commits. [Tips](https://intranet.alxswe.com/rltoken/oAAqmPJ1ftZZhUjaw7FvjA "Tips")

On [GitHub.com](https://intranet.alxswe.com/rltoken/4vp5Qze3WATHKtytzT2_UA "GitHub.com"):

-   Using the graphic interface on the website, create the repository (if it’s not done yet)
    -   Description: `This is my first repository as a full-stack engineer`
    -   Public repo: `zero_day`
    -   No `README`, `.gitignore`, or license

On your computer, open a terminal and do the following:

-   Navigate to your home directory. [Tips](https://intranet.alxswe.com/rltoken/YeOwsN-vhfSCbNjgE01Gag "Tips")
-   Create a directory `zero_day`. [Tips](https://intranet.alxswe.com/rltoken/hWrqqlilEv8L6yqpyt1TTA "Tips")
-   Navigate to this new directory. [Tips](https://intranet.alxswe.com/rltoken/za58mq537U6U775osQ8bfQ "Tips")
-   Initialize git and add the remote origin
-   Create a file `README.md` with Emacs (or other command line editors) and write a small [Markdown](https://intranet.alxswe.com/rltoken/VV79mKOEf5mXVbKpH4i63Q "Markdown") text to present this project. **This file is mandatory in projects**
-   Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin (Note: You will probably need to set your login/password to push to the remote server)

Good job!

You pushed your first file in your **first repository** of the **first task** of your **first School project**.

**Repo:**

-   GitHub repository: `zero_day`
-   File: `README.md`

Done?! Help

×

#### Learners who are done with "0. Create and setup your Git and GitHub account"

Check your code

×

#### Correction of "0. Create and setup your Git and GitHub account"

Start a new test Close

Requirement success

Requirement fail

Code success

Code fail

Efficiency success

Efficiency fail

Text answer success

Text answer fail

Skipped - Previous check failed

### 1\. Hello Ubuntu

#advanced

Inside the `zero_day` repo, create a new directory called `0x00-vagrant`. Add a `README.md` file to this directory.

`ssh` into your Ubuntu VM. What does the command `uname` print when you run it without any option?

Type your answer into a file in the `0x00-vagrant` directory and push it to GitHub. Name your file accordingly as shown below.

**Repo:**

-   GitHub repository: `zero_day`
-   Directory: `0x00-vagrant`
-   File: `0-hello_ubuntu`

Done?! Help

×

#### Learners who are done with "1. Hello Ubuntu"

Check your code

×

#### Correction of "1. Hello Ubuntu"

Start a new test Close

Requirement success

Requirement fail

Code success

Code fail

Efficiency success

Efficiency fail

Text answer success

Text answer fail

Skipped - Previous check failed

Copyright © 2023 ALX, All rights reserved.
