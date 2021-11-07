---
layout: default
title: Packages
parent: The Basics
nav_order: 3
---

### **Packages**
> When you download and install R for the first time, you are installing the Base R software. Base R will contain most of the functions you’ll use on a daily basis like mean() and hist(). However, only functions written by the original authors of the R language will appear here. If you want to access data and code written by other people, you’ll need to install it as a package. An R package is simply a bunch of data, from functions, to help menus, to vignettes (examples), stored in one neat package.

### **Installing Packages**
> Installing packages is easy! Use the function `install.packages()` to add any package not inherent to R. 

#### **library() function**
> Once you've installed a package, R will cache the package until you decide to uninstall or the package is no longer supported. However, you will need to "call up" your package each time you start a new session with R. You'll do this by using the `library()` function.  
