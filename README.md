# GitHub PR AI Code Review Bot

An AI-powered GitHub Actions workflow that automatically reviews Pull Requests using a Large Language Model (LLM).

---

## Overview

This project was developed as a team project to automate the code review process for GitHub Pull Requests.

When a Pull Request is opened or updated, GitHub Actions automatically executes a Python script. The script analyzes the changed code using an LLM API and generates review comments for developers.

---

## Features

- Automatically triggers on Pull Request events
- Analyzes changed source code
- Generates AI-based review comments
- Integrates with GitHub Actions
- Supports LLM APIs such as Groq and OpenAI

---

## How It Works

1. A Pull Request is created or updated.
2. GitHub Actions starts the workflow.
3. The workflow executes the Python review script.
4. The script extracts changed files from the PR.
5. The changed code is sent to the AI API.
6. The generated review is posted back to the Pull Request.

---

## Tech Stack

- Python
- GitHub Actions
- GitHub API
- Groq API (OpenAI Compatible)

---

## My Contribution

This project was completed as a team project.

My contributions included:

- Configuring the GitHub Actions workflow
- Integrating the AI API for automated code reviews
- Testing the Pull Request review process
- Preparing the project documentation and report

---

## Documentation

A detailed project report is available below.

- [Project Report (PDF)](./GitHub_PR_AI_Review_Report.pdf)

---

## Limitations

The AI review workflow is currently not executable because the API key used during development has been removed for security reasons.

However, the project structure, workflow configuration, and implementation process are documented in the included project report.

---

## What I Learned

Through this project, I learned:

- GitHub Actions workflow automation
- CI/CD concepts
- GitHub API integration
- LLM API integration
- Automating development workflows with AI
