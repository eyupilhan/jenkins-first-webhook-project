# Jenkins First Webhook Project

## Overview

This project demonstrates a basic Jenkins and GitHub webhook integration.

The main goal of this project is to automatically trigger a Jenkins job whenever code is pushed to a GitHub repository. A simple Python script is used to verify that the Jenkins build is triggered and executed successfully.

---

## Technologies Used

* Jenkins
* GitHub
* GitHub Webhooks
* Python
* CI/CD

---

## Repository Structure

```text
.
├── hello-world.py
└── README.md
```

---

## Project Workflow

```text
GitHub Push
      │
      ▼
GitHub Webhook
      │
      ▼
Jenkins Job Trigger
      │
      ▼
Run Python Script
      │
      ▼
Build Result
```

---

## Project File

* `hello-world.py` – A simple Python script used to verify Jenkins job execution.

---

## Purpose

This project was created to practice the fundamentals of Continuous Integration (CI) using Jenkins and GitHub Webhooks.

It demonstrates how a code change pushed to GitHub can automatically trigger a Jenkins build without manual intervention.

---

## Learning Outcomes

Through this project, I gained practical experience with:

* Configuring GitHub Webhooks
* Connecting GitHub repositories to Jenkins
* Automatically triggering Jenkins jobs after Git pushes
* Understanding the basic Continuous Integration (CI) workflow
* Executing Python scripts as part of a Jenkins build process
