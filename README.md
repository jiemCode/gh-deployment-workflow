The goal of this project is to help you learn the notion of continuous integration and continuous deployment. You will write a simple GitHub Actions workflow to deploy a static website to GitHub Pages.

Requirements
You are required to write a GitHub action that deploys any changes made to the index.html file to GitHub Pages. It should only deploy the file when the index.html file is changed.

Here are the steps to get you started:

Create a GitHub repository for the project called gh-deployment-workflow for example.
Repository should contain a simple index.html file saying “Hello, GitHub Actions!”
It should also have a README.md file explaining the project.
There should also be a deploy.yml file in the .github/workflows directory which contains the GitHub Actions workflow to deploy the website to GitHub Pages.
Every push to the main branch that changes the index.html file should trigger the workflow to run and deploy the website to GitHub Pages.
Website and any changes you make should be accessible at the GitHub pages URL for the repository e.g. https://<username>.github.io/gh-deployment-workflow/.
