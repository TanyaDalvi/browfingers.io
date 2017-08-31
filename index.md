# Django Tutorial by Brownfingers

Welcome to the Django Tutorial by BrownFingers! We are happy to see you here :smiley:.In this tutorial, we will take you on a journey under the hood of web technologies, offering you a glimpse of all the bits and pieces that need to come together to make the web work as we know it.
As with all unknown things, this is going to be an adventure - but no worries, since you already worked up the courage to be here, you'll be just fine :v:

## Introduction

Have you ever felt that the world is more and more about technology to which you cannot (yet) relate? Have you ever wondered how to create a website but have never had enough motivation to start? Have you ever thought that the software world is too complicated for you to even try doing something on your own?
Well, we have good news for you! Programming is not as hard as it seems and we want to show you how fun it can be.

This tutorial will not magically turn you into a programmer. If you want to be good at it, you need months or even years of learning and practice. But we want to show you that programming or creating websites is not as complicated as it seems. We will try to explain different bits and pieces as well as we can, so you will not feel intimidated by technology.

We hope that we'll be able to make you love technology as much as we do!

### What will you learn during the tutorial:exclamation::question:

Once you've finished the tutorial, you will have a simple, working web application: your own blog. We will show you how to put it online, so others will see your work!

#### What is Django and why use it?:thought_balloon:

Django is a web framework built with the Python programming language. Django's official description claims that it enables developers to build high-performing, elegant web applications quickly. But what does that mean to you? That question is what we'll answer here.

**A framework like Django does two primary things:**
1. It provides functionality that web applications:computer: perform over and over again. Let’s take look at user management as an example. There are various housekeeping chores that a program or app performs every time someone logs in: authentication, database permissions, password management, and displaying pre-built forms.
Of course you can rewrite this functionality for every web application :nerd:, but why reinvent the wheel? Most web applications require user authentication, so why not use an authentication system that's already been built?:sunglasses: You'll save an enormous amount of time and can focus your efforts on the parts of the application that make it unique.:sparkles:
    Django offers tools for lots of functions, not just user management. It provides pre-built tools for database management, URL    design, forms, templates, and much more.

2. The **second** thing the framework does is to provide_ a methodology for completing tasks._ If you want to create a web form to gather user data, there's a very specific place that you put the code that creates the forms, and there's a very specific way that you code them.

The value in this is apparent on projects that go beyond a few pages or are functionally complex. Knowing how to write code, where to put code, and where to find code in larger projects can make the maintenance and evolution of the code much easier as time goes by.

**In summary, Django is a web framework that provides a significant amount of pre-built functionality, reducing the time it takes you to complete projects. It prescribes a certain methodology for building applications, which is helpful in deciphering complex applications.**

##### Installation

In the workshop you will be building a blog, and there are a few setup tasks in the tutorial which would be good to work through beforehand so that you are ready to start coding on the day.

-**Python Installation**
According to its website, python.org, "Python is a programming language that lets you work quickly and integrate systems more effectively." It is the programming language that Django is based on, and is therefore used to create the CRM Easy application.
This course requires a _**2.7 version of Python. **_

-**Install Python On a Mac**
Below are the steps to install Python on a Mac.

Step 1: Verify Which Version of Python is Installed

Macs come with Python pre-installed. Again, this course uses the 2.7.x (e.g. 2.7.5 or 2.7.6) version of Python. Some Mac OS X releases have a different version of Python installed. Therefore the first step is to verify what version of Python is installed on your computer. If it isn't in the 2.7.x range then it will need to be updated.

To check which version of Python is installed open a terminal window by going into Spotlight (the magnifier in the upper right corner) and typing 'terminal'.

Once the terminal is open, type python into it. This will start the Python interpreter, which will also show you the version number. In the following example the Python version is 2.7.5.

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/TanyaDalvi/browfingers.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
