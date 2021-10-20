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

## Created a new project and clicked "new git repository"
Created a new R Markdown file
Staged R markdown file by checking the box next to the R markdown file in the "Git tab"
Committed R markdown file
