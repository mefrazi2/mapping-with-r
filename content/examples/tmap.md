---
layout: default
title: Tmap Package
parent: Demonstration
nav_order: 4
---


### **tmap Package**
> We'll be using the package `tmap` heavily in this demonstration. Documentation on tmap can be found [here](https://www.rdocumentation.org/packages/tmap/versions/3.3-2), but also remember the `help(package = "tmap")` command.

> Try playing around with some of the functions found within this package (some are listed in our demo). You might try visualizing the Chicago map with different colors, titles, or variables. Perhaps even challenge yourself to making a categorical map of Chicago communities with a legend! 

> #### Hint: Run this code. 
> 
> `tm_shape(chi_comm) + tm_polygons("community") + tm_layout(legend.outside = TRUE, legend.outside.position = "right")` 
> 
> What feedback message do we get? What do you think it means? 
> ##### It's telling us two things: 1) The maximum number of colors it can display is capped at 30 (unless we manipulate it), so 2) it's re-using the color scheme to visulize different neighborhoods (that's why we see duplicate colors and community names linked in the legend).
