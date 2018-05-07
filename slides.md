# Version Control 

<medium>
Good practices in bioinformatics<br>
May 7th, 2018 - CRG
</medium>

<small style="width: 50%; margin-top: 0.5em; color: grey;">
<span style="float: left;">Emilio Palumbo</span>
<span style="float: right;">Toni Hermoso</span>
</small>


## Objectives

- learn what a version control system is and why it is important


## Outcomes

- learn the main terminology and commands of `Git` and apply them
- create a `GitHub` repository



## What is version control?


management of changes to documents, computer programs and other collections of information

<i style="color: #189acb;" class="fas fa-caret-right"></i> **when**, **who**, **what**


## Why you should you use it


<!-- .slide: data-background-image="images/phd101212s.gif" data-background-size="contain" -->


<!-- .slide: data-background-image="images/phd052810s.gif" data-background-size="contain" -->


## Benefits

- transparency
- change history
- backup and restore
- recovery from errors
- easier collaborative work
- reproducibility


## Uses
(either alone or collaboratively)

- papers
- lectures
- documentation
- scripts (R, Python, whatever else)
- text/tabular files



## Version Control Systems


stand-alone tools that record changes to a file or set of files over time

<i style="color: #189acb;" class="fas fa-caret-right"></i> often referred to as **VCSs**


## Basic concept

<i style="color: #189acb;" class="fas fa-caret-right"></i> `commit`

Save files as logical sets of changes and write a good description of why you changed them 


## What you can do

- review changes made over time
- revert files/the entire project back to a previous state
- see who last modified something
- find out where and how things went wrong
- remove content knowing that you can easily go back
- sandboxing


## Quick history

~ 40 years since first use

<i style="color: #189acb;" class="fas fa-caret-right"></i> three main generations


## local
<i style="color: #189acb;" class="fas fa-caret-right"></i> e.g. <span style="color: #189acb;">`RCS`<span>

![local](images/local.png)<!-- .element: width="54%" -->


## centralized
<i style="color: #189acb;" class="fas fa-caret-right"></i> e.g. <span style="color: #189acb;">`SUBVERSION`<span>

![centralized](images/centralized.png)<!-- .element: width="64%" -->


## distributed
<i style="color: #189acb;" class="fas fa-caret-right"></i> e.g. <span style="color: #189acb;">`GIT`<span>

![distributed](images/distributed.png)<!-- .element: width="43%" -->



## What is Git?


an **open source**, **distributed**, version control system

<i style="color: #189acb;" class="fas fa-caret-right"></i> most used thanks to its simplicity and GitHub 


![git-github](images/Github2.png)

<i style="color: #189acb;" class="fas fa-caret-right"></i> GitHub is a web-based Git repository hosting service, which offers all the functionalities of Git as well as adding its own features


## Git Features

- nearly every operation is local
- integrity, everything is checksummed
- generally only adds data
- every local repository is a backup


## Traditional model

![deltas](images/deltas.png)

Delta based


## Git model

![deltas](images/snapshots.png)

Stream of snapshots


![](images/svngit.png)<!-- .element: width="50%" -->


## Git hosting services

- social coding
- version control as a service
- in-browser editing
- additional collaborative features


[![GitHub](images/github-logo.png)<!-- .element width="40%" -->](https://github.com)
[![BitBucket](images/bitbucket_rgb_darkblue_atlassian_1200x630.png)<!-- .element width="40%" -->](https://bitbucket.org)
[![GitLab](images/gitlab.png)<!-- .element width="40%" -->](https://gitlab.com/)


## Git Clients


[![git](images/git.png)<!-- .element width="35%" -->](https://git-scm.com/downloads)

<i style="color: #189acb;" class="fas fa-caret-right"></i> command line tool


[![GitKraken](images/gitkraken.jpg)<!-- .element width="30%" -->](https://www.gitkraken.com/)
[![SourceTree](images/Sourcetree-blue.svg)<!-- .element width="35%" -->](https://www.sourcetreeapp.com/)
[![GitHub Desktop](images/github-desktop.svg)<!-- .element width="20%" -->](https://desktop.github.com/)

<i style="color: #189acb;" class="fas fa-caret-right"></i> third party graphical user interface (GUI) tools


## References
- [Git Docs](https://git-scm.com/docs)
- [Git Getting Started](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
- [Git GUI Clients](https://git-scm.com/downloads/guis/)
- [Git Introduction for Scientists](http://karthik.github.io/git_intro/)
- [Git Simple Visual Guide](http://rogerdudler.github.io/git-guide/)



<!-- .slide: data-background-color="#000" -->
## Demo 



## Thank You