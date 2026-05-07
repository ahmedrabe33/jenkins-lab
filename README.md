# Jenkins Scripted Pipeline Lab

This repository contains a simple Jenkins Scripted Pipeline lab using a `Jenkinsfile`.

The goal of this lab is to understand how Jenkins can read a pipeline from GitHub and run different stages such as build and test.

---

## Project Overview

In this lab, Jenkins will:

1. Clone the GitHub repository
2. Run a build stage
3. Handle errors using `try / catch`
4. Run a test stage based on the branch name
5. Skip the test stage if the branch condition is not matched

---

## Tools Used

- Jenkins
- GitHub
- Git
- Ubuntu
- Docker
- Jenkinsfile
- Scripted Pipeline

---

## Repository Structure

```text
.
├── Jenkinsfile
└── README.md