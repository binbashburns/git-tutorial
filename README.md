# Git & GitHub Tutorial Website

Welcome! This is a beginner-friendly Git and GitHub tutorial designed to help my friends learn the essentials of version control using real workflows.

This site is automatically published via [GitHub Pages](https://pages.github.com) whenever a change is merged into the `main` branch.

GitHub Page is hosted at https://themattburns.com

![gitflow](/src/gitflow.png)

---

## 🔧 What You'll Learn

- How to configure Git on your computer
- How to clone a repository
- How to create a new branch
- How to make and commit changes
- How to push code and open a Pull Request (PR)
- How to merge changes to `main` and trigger a deployment

---

## 📁 Project Structure

```plaintext
.
├── index.html               # Landing page linking to each user's tutorial
├── style.css                # Shared styling for the site
├── users/                   # Each user's working tutorial page
│   ├── travis.html
│   ├── ryan.html
│   └── matt.html
├── examples/                # Pre-made user pages (to be copied into users/)
│   ├── travis.html
│   ├── ryan.html
│   └── matt.html
├── src/                     # Image assets for each user
│   ├── travis.jpg
│   ├── ryan.jpg
│   └── matt.jpg
└── .github/
    └── workflows/
        └── deploy.yml       # GitHub Actions CI/CD for GitHub Pages
```
## 📦 Additional Resources

The `resources` directory has some useful stuff, including a [handy dandy Git reference sheet](/resources/git_command_reference.pdf)