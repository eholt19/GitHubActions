# GitHub Actions CI/CD Demo

This project demonstrates the use of GitHub Actions for Continuous Integration and Continuous Deployment (CI/CD) with Render.

## Project Overview

- **Frontend:** React (Vite)
- **Testing:** Cypress (component tests)
- **CI/CD:** GitHub Actions
- **Deployment:** [Render](https://githubactions-d5f5.onrender.com)

## Live Site

[View the deployed app on Render](https://githubactions-d5f5.onrender.com)

## 🛠️ GitHub Repository

[View this project on GitHub](https://github.com/eholt19/GitHubActions)

## 🏗️ How CI/CD Works

- **Cypress Tests on PR:**  
  When a Pull Request is made to the `develop` branch, GitHub Actions runs Cypress tests automatically.
- **Deploy on Main:**  
  When code is pushed or merged to the `main` branch, GitHub Actions triggers a deploy on Render via a deploy hook.  
  This ensures that the latest version is always live.

## 🖼️ Screenshots

*Successful GitHub Actions Workflow:*

![GitHub Actions Success Screenshot](./assets/github-actions-success.png)

*Render Deploy Hook Event:*

![Render Deploy Success Screenshot](./assets/render-deploy-success.png)

> Replace these image links with your actual screenshot files if you have them!

## 🧑‍💻 How to Run Locally

1. Clone the repo
   ```bash
   git clone GITHUB_REPO_URL_HERE
   cd <repo-folder>
2. Install dependencies and run the frontend:
    cd client
    npm install
    npm run dev
3. Open http://localhost:5173 in your browser.

## Technologies Used

* React

* Vite

* Cypress

* GitHub Actions

* Render

## CI/CD Pipeline Summary

* Test on PRs: Cypress tests are triggered for every pull request to develop.
* Automatic Deployment: On merge or push to main, a GitHub Actions workflow calls the Render deploy hook to redeploy the app.

## Licence

* MIT