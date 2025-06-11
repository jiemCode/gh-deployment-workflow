# 🚀 GitHub Actions Deployment Workflow

### Project: [github-actions-deployment-workflow](https://roadmap.sh/projects/github-actions-deployment-workflow)  
### Author: [jiemCode](https://github.com/jiemcode)

---

## 📖 Description

This project demonstrates the basic principles of **Continuous Integration (CI)** and **Continuous Deployment (CD)** using **GitHub Actions**.

The goal is to deploy a simple static website to **GitHub Pages** every time the `index.html` file is modified and pushed to the `main` branch.

---

## 🌐 Live Site

🔗 [https://jiemcode.github.io/gh-deployment-workflow/](https://jiemcode.github.io/gh-deployment-workflow/)

---

## 📁 Project Structure

```plain
.
├── .github
│   └── workflows
│       └── deploy.yml
├── index.html
└── README.md
```

---

## 🛠 Requirements

- Create a GitHub repository named **`gh-deployment-workflow`**.
- Add a simple `index.html` file (e.g. “Hello, GitHub Actions!”).
- Create a GitHub Actions workflow file: `.github/workflows/deploy.yml`.
- Workflow should:
  - Trigger **only** when `index.html` is modified.
  - Deploy the site to **GitHub Pages** automatically.
- Ensure the site is live at: `https://<your-username>.github.io/gh-deployment-workflow/`