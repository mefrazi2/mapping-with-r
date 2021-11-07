---
layout: default
title: The Challenger
parent: Demonstration
nav_order: 5
---

### **The Challenger**
> If you want to push your R skills to the limit, let's use another popular data visualization package called `ggplot2`. 

> For this challenge, we'll try creating another map of average household income for Chicago communities, but instead of classifying our data into bins, or ranges, we will visualize it as a continous variable. 

> The code below is an example of what you'll work with in the R markdown file. 

> `ggplot(data = define_data, aes(fill = define_variable)) + 
  geom_sf() + 
  scale_fill_distiller(palette = "RdPu", 
                       direction = 1) + 
  labs(title = "Give your map a nice header title here",
       caption = "Add a data source here",
       fill = "Add a legend title") + 
  theme_void()`
