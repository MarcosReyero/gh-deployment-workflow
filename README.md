## Project Roadmap

This project is part of the [DevOps Roadmap](https://roadmap.sh/projects/github-actions-deployment-workflow)


# GitHub Pages Deployment with GitHub Actions

This project demonstrates how to automate the deployment of a static website to **GitHub Pages** using **GitHub Actions**. The workflow ensures that any updates made to the `index.html` file are automatically deployed.

## 📌 Features

- 🚀 **Automated Deployment**: Changes to `index.html` in the `main` branch trigger an automatic deployment.
- 📄 **Static Website**: A simple HTML page hosted on **GitHub Pages**.
- ⚙️ **CI/CD Workflow**: Uses **GitHub Actions** to automate deployment.

## 📂 Project Structure

gh-deployment-workflow/ │── .github/ │ └── workflows/ │ └── deploy.yml # GitHub Actions workflow for deployment │── index.html # Static HTML file for the website │── README.md # Project documentation


## 🚀 How It Works

1. **Push Changes**: When you modify `index.html` and push to the `main` branch.
2. **GitHub Actions Triggered**: The workflow in `.github/workflows/deploy.yml` runs.
3. **Deployment to GitHub Pages**: The updated website is published automatically.

