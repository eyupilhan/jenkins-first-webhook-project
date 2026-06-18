# Jenkins First Webhook Project

## Overview

This project demonstrates a basic Jenkins and GitHub webhook integration.

The main goal of this project is to automatically trigger a Jenkins job when a change is pushed to the GitHub repository. A simple Python script is used to validate that the Jenkins job runs successfully.

## Technologies Used

* Jenkins
* GitHub
* GitHub Webhooks
* Python
* CI/CD

## Project Workflow

```text
GitHub Push
    ↓
GitHub Webhook
    ↓
Jenkins Job Trigger
    ↓
Run Python Script
    ↓
Build Result
```

## Project File

* `hello-world.py`: A simple Python script used to test the Jenkins job execution.

## Purpose

The purpose of this project is to practice Continuous Integration basics using Jenkins and GitHub. It demonstrates how Jenkins can be triggered automatically through GitHub webhooks.

## What I Learned

* How to connect GitHub with Jenkins using webhooks
* How to trigger Jenkins jobs automatically after a GitHub push
* How CI/CD automation works at a basic level
* How to use a simple Python script as part of a Jenkins job
