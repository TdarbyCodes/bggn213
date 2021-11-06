---
title: "Lab 7: GitHub"
class: "BGGN213 Bioinformatics class at UCSD"
author: "Taylor Darby"
date: "10/20/2021"
output: github_document
---

# Created a Github account using username "TDarbyCodes"

## Connect RStudio to Github account:
install.packages("usethis")
library(usethis)
create_github_token()

## Save Github credentials:
install.packages("gitcreds")
library(gitcreds)
gitcreds_set()

## Configure Git in the Terminal tab
First tell Git who you are:
>git config --global user.name "TDarbyCodes"
>git config --global user.email "tdarby@ucsd.edu"

## Created a new repository in Github
copied the URL and created a new project linked to the new repository

## Created a new project and clicked "new git repository"
Clicked "version control"
Entered URL in first field

## Learned how to update each of the locations
1) Add/save
2) Stage
3) Commit
4) Push
5) In other source "Pull"

## Learned to add other local files to repository
1) Move files into working folder on local computer
2) Files will show up on Git tab
3) Stage files, Commit, Push
4) On GitHub.com refresh and they should show up