---
layout: default
title: Software Setup
parent: Setup
nav_order: 1
---

# Software Setup Guide

This guide covers all the essential and recommended software you should to install and configure to work effectively in the Gentzkow Lab. We store our project repositories in GitHub, and individual repositories declare specific software requirements. Below are software that we use across many projects and recommend lab members to be familiar with.

## Version Control and Task Management: Git, GitHub, and git-lfs

### Overview

We use the Git version control system, augmented with git-lfs, to organize our code and data. We use issues on GitHub to manage tasks and structure communication around projects. We use GitHub wikis to store supplemental information related to our projects.

### Resources

**Basic (take about 20 minutes total and well worth it):**
- [Git Handbook](https://guides.github.com/introduction/git-handbook/)
- [Understanding the GitHub Flow](https://guides.github.com/introduction/flow/)
- [Mastering Issues](https://guides.github.com/features/issues/)
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

**Detailed:**
- [Pro Git](https://git-scm.com/book/en/v2)
- [Version Control with Git](https://git-scm.com/book/en/v2), Chapters 4-9

### Setup

1. Create a GitHub account and install the Git desktop / command line clients
2. Install [Git LFS](https://git-lfs.com/). Note that you only need to do step 1 under "Getting Started" at this point
3. Give your GitHub ID to a lab member who can give you permissions to the appropriate repositories

## Large File Storage: Dropbox and Google Drive

We use Dropbox or Google Drive to store files that are too big for GitHub (even with LFS) or are not project-specific.

### Setup

1. Install Dropbox and Google Drive
2. Ask a lab member to give you access to any Dropbox directories or Shared Drives you will need for your project(s)

## Programming Languages

### Python

**Resources:**
- [Software Carpentry](https://software-carpentry.org/lessons/)
- [Learning Python](https://docs.python.org/3/tutorial/)
- [DataCamp](https://www.datacamp.com/)

**Setup:** Check for install by typing `python` at terminal. If not installed, install [here](https://www.python.org/downloads/).

### R

**Resources:**
- [Analysis and Programming tutorials from Software Carpentry](https://software-carpentry.org/lessons/)
- [R for Data Science](https://r4ds.had.co.nz/)
- [DataCamp](https://www.datacamp.com/)

**Setup:** Install [R](https://cran.r-project.org/). Install [R Studio](https://www.rstudio.com/products/rstudio/download/).

### Stata

**Resources:**
- [UNC Population Center Tutorial](https://www.cpc.unc.edu/research/tools/data_analysis/statatutorial/)
- [A Little Bit of Stata Programming Goes a Long Way](https://www.stata.com/bookstore/little-bit-stata-programming/)

**Setup:** Install Stata, typically licensed via your university.

## Mathematical Writing

### LyX

**Setup:** Install [LyX](https://www.lyx.org/Download)

### TeX Live

**Setup:** Install [TeX Live](https://www.tug.org/texlive/)

## Development Environment

### Visual Studio Code

We recommend using Visual Studio Code as your primary code editor. It provides excellent support for:

- Python, R, and Stata syntax highlighting
- Git integration
- Remote development capabilities
- Extensions for various programming languages and tools

**Setup:**
Download and install [Visual Studio Code](https://code.visualstudio.com/)


### Terminal and Command Line

Familiarity with the command line is essential for working with Git, running scripts, and managing your development environment.

**Resources:**
- [Command Line Crash Course](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Command_line)
- [Bash Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/)

## Environment Configuration

### Python Environment Management

We recommend using conda or virtual environments to manage Python packages and dependencies.

**Setup:**
1. Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/products/distribution)
2. Create separate environments for different projects
