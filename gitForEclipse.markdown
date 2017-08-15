---
layout: default 
title: "Using Git in Eclipse"
---


**Git** is a widely used version control system. (You most likely heard of [GitHub](https://github.com/).) This page guides you through setting up Ecplise so that it can work with projects hosted on GitHub. 

**[EGit](http://www.eclipse.org/egit/)** plugin comes bundled with the latest versions of [Ecplise](http://www.eclipse.org/). It allows you to use **git** with the projects created in Eclipse.

<br>

There is a great tutorial with lots of details at the Vogella tutorials site: 
[Git version control with Eclipse (EGit)](http://www.vogella.com/tutorials/EclipseGit/article.html).

<br>

---

<br>


Here are just some quick points on how to get started with using the EGit plugin in Eclipse.

# Help documentation for EGit

Open an instance of Eclipse and go to *Help* &#8594; *Help  Contents*  &#8594; *EGit Documentation*. 

# Configure Eclipse and Git 

You need to configure Eclipse and Git so that the version control system knows who you are when you are making changes to the repositories. In Eclipse go to *Windows*  &#8594; *Preferences* &#8594; *Team* &#8594; *Git* &#8594; *Configuration*. You should be looking at the screen that looks as follows:

<img src="{{site.baseurl}}/resources/figures/gitForEclipse/configuration.png" name="Configuration Screen" border="0px" width="400px"> 

- Modify the value of the *email* field to match the email address you have associated with your GitHub account. 
- Modify the value of the *name* field to match your GitHub username. 
- Hit *Apply* 

You can read more about configuring git in general at [Getting Started - First Time Git Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup).

# Place for your repositories

Eclipse keeps a lot of files in addition to the source code files for the project that we are working on. We want a different location for the repositories that should contain the source code (and optional README files) only. 

To set this up, go to *Windows*  &#8594; *Preferences* &#8594; *Team* &#8594; *Git* and change the directory name for *Default repository folder*. Some good locations might be your home directory, a directory in which you store course related materials, etc. In my case, it is `/home/asia/Data/NYU_Teaching/csci102/git` (in Linux, `/home/asia` is my home directory). 

 
 
<br>
<br>
		
