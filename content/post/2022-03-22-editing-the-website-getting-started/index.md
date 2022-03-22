---
title: Editing the Website - Getting Started
author: Hosei Nakajima
date: '2022-03-22'
slug: editing-the-website-getting-started
categories:
  - howto
tags: []
---

## Hey there

Looks like you want to start editing this website huh? Well, the first thing you need to do is install R and Rstudio. \
R: https://www.r-project.org/ \
Rstudio: https://www.rstudio.com/products/rstudio/download/

After you get those installed and ready to go, install git as well. \
https://git-scm.com/downloads

### Setting Rstudio Up
Now, open a fresh Rstudio window and install "[blogdown](https://bookdown.org/yihui/blogdown/)" like this. 
```{r}
install.packages("blogdown")
```

After blogdown is installed, go to the top right where it says "Project" and click on "New Project".\
![rs1](rstudio1.PNG)

You should see a popup like this, and select version control:\
![rs2](rstudio2.PNG)

Then select Git.\
![rs3](rstudio3.PNG)

Now just copy paste the website repository on our Github.\
![rs4](rstudio4.PNG)

Now you're ready to rock on and change the world!

