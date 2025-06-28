---
layout: default
title: Task 2 - Sherlock Extension
nav_order: 4
---

# Task 2: Sherlock Extension

## Overview

This task introduces you to high-performance computing using Stanford's Sherlock cluster. You'll learn how to set up your environment, transfer files, and submit jobs for computation-intensive tasks.

---

## 1. Review Sherlock Documentation

Thoroughly review the purpose and features of Sherlock [here](https://github.com/gslab-econ/ra-manual/wiki/Research-Clusters). You may refer to the same link throughout this task to read further instructions.

---

## 2. Access Sherlock

Log on to Sherlock following the instructions [here](https://www.sherlock.stanford.edu/docs/getting-started/). Ensure you have access to the correct partitions (`$OAK`, `$HOME`, `$GROUP_HOME`, `$SCRATCH`, and `$GROUP_SCRATCH`) with the `sh_part` command. If you do not have access to `$OAK`, ask a lab member for access.

---

## 3. Setup Your Environment

Set up your personal directory under `$OAK`. Set up `Dropbox` and `Rclone` on Sherlock. You can follow the instructions [here](https://www.sherlock.stanford.edu/docs/storage/data-transfer/) and [here](https://www.sherlock.stanford.edu/docs/software/using/rclone/).

Initialize GitHub usage on Sherlock by [generating](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) a new SSH key and [adding](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) it to Sherlock.

---

## 4. Clone and Test Repository

Clone your remote template repository to your personal directory in `$OAK`. Make sure the repository is working by running `run_all.sh` and confirming all the outputs are generated correctly. You should see the standard output appear in your `$OAK` directory. 

**Note**: You will not need to set up command line usage on Sherlock - simply load the relevant applications with the module spider and ml <application/version> commands. For more on this, see Setting up the environment in the [Research Clusters](https://github.com/gslab-econ/ra-manual/wiki/Research-Clusters) section of the manual.

---

## 5. Create Analysis Issue

Create a new issue to change the highway fuel economy analysis to use logs. Follow similar steps as you did previously. Add the new figure to the slides.

---

## 6. Submit Job

Submit a job to run the full repository with these edits, following the instructions [here](https://www.sherlock.stanford.edu/docs/getting-started/submitting/).

---

## 7. Complete with Pull Request

Open a PR as before to merge your changes.

---

## Key Learning Objectives

- Understanding high-performance computing environments
- File transfer and synchronization between local and cluster systems
- Job submission and management on Sherlock
- Maintaining version control across different computing environments 