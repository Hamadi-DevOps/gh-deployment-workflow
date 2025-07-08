# GitHub Pages Deployment Workflow

This repository demonstrates how to automatically deploy changes to the `index.html` file to GitHub Pages using GitHub Actions.

## How It Works

- The repository contains a simple `index.html` file displaying "Hello, GitHub Actions!"
- A GitHub Actions workflow (`.github/workflows/deploy.yml`) runs on every push to the `main` branch.
- The workflow **only triggers deployment when the `index.html` file is changed**.
- When triggered, the workflow deploys the site to GitHub Pages, making it available at:  
  `https://<your-username>.github.io/gh-deployment-workflow/`

## Files

- `index.html` — The main web page.
- `README.md` — This file explaining the project.
- `.github/workflows/deploy.yml` — The GitHub Actions workflow for deployment.

## Usage

To update the website, simply modify the `index.html` file and push changes to the `main` branch. The workflow will automatically deploy the updated site.

---

*This project is a simple example of continuous deployment using GitHub Actions and GitHub Pages.*
