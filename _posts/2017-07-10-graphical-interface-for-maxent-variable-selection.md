---
layout: post
published: true
title: Graphical Interface for MaxEnt Variable Selection
date: '2017-07-10'
---
## GIMVS - Graphical Interface for MaxEnt Variable Selection

The [MaxentVariableSelection](https://github.com/alj1983/MaxentVariableSelection) package is useful to identify the most important set of uncorrelated environmental variables on a **MaxEnt** Model and also helps tune **MaxEnt** settings. Sometimes is hard, or just tedious, to manually put the file names and directories of the data to process. If you are using a Windows OS computer you have to be even more careful to make sure that the paths are using the forward slash "**/**" or the double backwards slash "**\\\\**". 

I wrote the **GIMVS** R script that uses the wonderful [**Shiny**](http://shiny.rstudio.com/) package to create a simple but useful GUI to simplifies the task. So you don't have to manually copy and paste the paths or change the slash. Also you can set the **MaxEnt** parameters using **Shiny** wodgets. The final product works as **RStudio** gadget. It also helps with the creation of input files in SWD format.

Please check out **GIMVS** at [github](https://github.com/geoabi/gimvs) and feel free to comment or provide feedback about the script.

If your are interested in learn more about **MaxEnt**, you can get the last version and documentation [here](http://biodiversityinformatics.amnh.org/open_source/maxent/).

![Running Maxent Variable Selection]({{site.baseurl}}/img/run_MaxentVariableSelection.png)

![SWD Convertion]({{site.baseurl}}/img/swd_convertion.png)



