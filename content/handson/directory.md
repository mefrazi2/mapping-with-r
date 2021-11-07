---
layout: default
title: Working Directory
parent: The Basics
nav_order: 4
---
### **Working Directory**

> Working directories tell R where to call up data, store exports, and save associated project files. Let's check out what our current working directory is by typing the function `getwd()`: 

> <img src="https://raw.githubusercontent.com/mefrazi2/mapping-with-r/main/img/getwd.jpg">

> I can see that my working directory isn't what I want it to be (and yours might not be either). Let's try changing our working directory to a random folder on our desktop instead. The easiest way to do this is to open up your file explorer and copy your desktop file path. In my example I'll be using our folder we'll be downloading for the example. Once you've copied your file path, type the function `setwd` followed by the appropriate file path with *forward* slashes (you may have to fix these manually). 

> <img src="https://raw.githubusercontent.com/mefrazi2/mapping-with-r/main/img/setwd.jpg">

> Don't forget the quotation marks - this is part of R's **syntax**, which allows the application to compile and execute your code correctly. 

> Let's check what our working directory is now: 

> <img src="https://raw.githubusercontent.com/mefrazi2/mapping-with-r/main/img/cwd.jpg">

> This is an important step, and one we will use in our demostration. 
