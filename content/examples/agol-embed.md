---
layout: default
title: Reading-In Data
parent: Demonstration
nav_order: 3
---


### **Reading Data**
> 1. Make sure your data folder is unzipped. 
> 2. We will define our object (aka .shp) using the `<-` operation. 
> <img src="https://raw.githubusercontent.com/mefrazi2/mapping-with-r/main/img/reading_in_data.jpg">
  
### **Checking Projections**
> We already have an idea of what our projection is from reading in our shapefile. But let's say we didn't. In this case, we would use the function `st_crs` to help us define it. 

### **Attribute Table**
> To get attribute information, we simply execute the function `View(chi_comm)`. A table opens up in our source window. We can clearly see how many attributes, or variables, and associated observations there are. 
> <img src="https://raw.githubusercontent.com/mefrazi2/mapping-with-r/main/img/view.jpg">
