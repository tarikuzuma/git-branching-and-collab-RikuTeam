# Git Branching and Collaboration Workshop

Welcome to the Git Branching and Collaboration Workshop! In this workshop, you will learn the fundamentals of Git, branching, and collaborating on projects with a team. The goal is to work together to create a simple personal portfolio webpage using Git workflows.

## Workshop Overview

In this repository, you will find the following files:

- **`index.html`**: The main HTML structure for the personal portfolio page.
- **`style.css`**: The basic CSS styles for the portfolio page.

### What's Editable?

Everything in this repository is **editable**! You can freely modify the HTML structure and CSS to make the page your own. Feel free to:

- Update content in the HTML (e.g., personal bio, project descriptions).
- Modify styles in `style.css` to improve the design.
- Add new sections or features as needed.

## Steps to Get Started

### 1. Fork the Repository

To make changes to the website, you'll first need to **fork** it. Here's how:

- Go to the top-right corner of this repository page.
- Click the **Fork** button to create a personal copy of the repository under your GitHub account.

### 2. Clone the Repository

Once you've forked the repository, you need to clone it to your local machine. Follow these steps:

1. On your forked repository page, click on the green **Code** button.
2. Copy the URL provided (HTTPS or SSH).
3. Open your terminal (or Git Bash) and run the following command to clone the repository:

```bash
git clone <your-repo-url>
```

Example:
```bash
git clone https://github.com/your-username/git-branching-workshop.git
```
This will create a local copy of the repository to your computer.

### 3. Create New Branch
Before making any changes, create a new branch to work your features. DO NOT immediately push on main

```bash
git checkout -b <your-branch-name>
```

Example:
```bash
git checkout -b ui/header
```

### 4. Make Changes and Push When Needed
Edit the files (eg: `index.html` or `styles.css`) as needed. Be sure to commit your changes frequently.

Example:
```bash
git add .
git commit -m "ui: updated hero section with new content"
```

After making changes, **PUSH** your changes. In this example, we'll be using the branch name `ui/header`
```bash
git push origin ui/header
```

This will effectively push all the changes you made to the ui/header branch.

### 5. Create a Pull Request
Once you are satisfied with your changes, go to your GitHub repository and create a pull request (PR) to merge your branch into the `main` branch of your group's original repository.

- Navigate to the "Pull Requests" tab on the top of your repo's page.
- Click "New Pull Request"
- Select your branch and submit the PR for review.

### 7. Review and Merge
- Review each other's PR, resolve any conflicts, and merge them into the `main` branch
- Once merged, the changes will be reflected on the live project.

---
### Useful Resources:
- Git branching: https://learngitbranching.js.org/
- Git from MS Learn: https://learn.microsoft.com/en-us/training/modules/intro-to-git/