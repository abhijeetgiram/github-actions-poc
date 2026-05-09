# GitHub Actions Proof of Concept (PoC)

This repository serves as a functional demonstration of **GitHub Actions**, showcasing how to automate workflows directly within a GitHub repository.

Created a Proof of Concept (PoC) for GitHub Actions to demystify Actions Tab.

GitHub Actions is just a way to tell GitHub: "When X happens, run these specific commands on a clean virtual machine."

## Overview

The goal of this PoC is to understand the core components of CI/CD (Continuous Integration / Continuous Deployment) by triggering automated tasks on every code push.

**Quick Link:** [View Live Execution Logs](https://github.com/abhijeetgiram/github-actions-poc/actions)

## Repository Structure

```text
.github/
└── workflows/
    └── hello-world.yml    # The main workflow configuration
README.md                  # Project documentation
```

## The Core Concepts

Before touching the code, keep these three terms in mind:

- **Workflow**: The entire automated process (the .yml file).

- **Event**: The "trigger" (like pushing code or opening a Pull Request).

- **Runner**: The server (hosted by GitHub) where your commands actually execute.

## The Workflow Folder

In your repository, you must use a specific folder structure for GitHub to recognize your automation:

- Create a folder named .github at the root.

- Inside that, create a folder named workflows.

- Inside that, create a file named hello-world.yml.

## How to Test It

- **The "Actions" Tab**: Click the Actions tab at the top of your GitHub repository page.
