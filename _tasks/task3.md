---
layout: default
title: Task 3 - Python-based Archived Template
parent: Tasks
nav_order: 4
---

# Task 3: Python-based Archived Template

## Overview

The previous version of the lab template was based in `python` instead of `shell`. Even though most projects don't currently use this template, it is useful to get some experience with it.

---

## 1. Repository Setup

Create your own public repository from the [archived template](https://github.com/gentzkow/template_archive) and invite the practice task assigner as a collaborator. Make sure you [fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repository, do not click "Use this template".

---

## 2. Test the Repository

Run the repository from beginning to end to replicate the output.

---

## 3. Modify the Analysis

Open a new issue to modify the code in the data folder so that the histogram in `output/chips_sold.pdf` displays percentages instead of counts. To update the data folder with your new histogram as an output, you should run `data/make.py`. Then, to make sure your changes are reflected in the paper, you should run `paper_slides/make.py`. Commit this file with a helpful message.

---

## 4. Complete with Pull Request

Open a PR to close the issue as usual.

---

## Key Learning Objectives

- Understanding the differences between shell-based and Python-based templates
- Working with Python-based build systems
- Adapting to different project structures and conventions
- Maintaining consistency across different template versions 