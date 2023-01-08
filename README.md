## afya resources and setup

Welcome to the Afya consortium Github organisation. This page is to orient you to some of the computing resources and overview of the varius Github repositories and codebases that we have currently for mortality estimation. 

### Overview

This is an overview of the current (as of 20 December 2022) different repositories:

* [mortality_small_area_estimation](https://github.com/francescochecchi/mortality_small_area_estimation) - Original and current codebase for conducting small area -estimation of mortality
* [mast](https://github.com/afyac/mast) - Package for cleaning and collating data needed for conducting mortality analysis.
* [samrat](https://github.com/afyac/samrat) - Package for conducting small area-estimation analysis of mortality. Currently analysis is conducted still using scripts from "mortality_small_area_estimation", but eventually we will want to rewrite this code into an R package to help with running analysis and extending approaches used more flexibly.
* [posh](https://github.com/afyac/posh) - Package of plotting and shiny tools - Not yet created and name open for discussion :)
* [parade](https://github.com/afyac/parade) - Package for results and dissemination. This repository is for keeping track of analysis for each report.

### Mortality Overview

The eventual goal is to have a series of packages that ingest different data sources to produce data for mortality estimation models. These models produce outputs that can then be used to create plots and interactive tools for policy makers as well as for our own reports during the project.

![image](https://user-images.githubusercontent.com/15249565/208780293-c18daa2a-ca2a-42a4-aefd-f7c4823f1463.png)

### Resources

We will centralise learning resources and other important documents through Google Drive. This is where all Google Docs and other learning resources will be stored and shared.

[Root Directory](https://drive.google.com/drive/folders/135rgRb-_3ud13VSmyYGjMrlstZF7aWbC?usp=sharing)

## Other Help

### GitHub is sending too many emails

Go to https://github.com/settings/notifications and:

* Untick **Automatically watch repositories**
* Untick **Email** under **Watching**
* Set up an email filter to collect all emails from `notifications@github.com` to be routed to a folder separate from your inbox (but still keep an eye on it)

