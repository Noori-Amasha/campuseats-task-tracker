# campuseats-task-tracker# 🍔 CampusEats Task Tracker

> 🎓 A simple task management project created for the **SE3090 – Software Engineering Frameworks** practical.

---

## 🌟 About the Project

**CampusEats Task Tracker** is a lightweight task management project designed to demonstrate professional software development practices.

The project focuses on:

- 🌿 Git branching and version control
- 🔀 Pull Requests and code reviews
- 🐛 GitHub Issues
- ⚙️ GitHub Actions and CI
- 🔐 Security and code quality
- 📦 Dependency security checks with `npm audit`

---

## 🛠️ Technologies & Tools

| Technology            | Purpose                                |
| --------------------- | -------------------------------------- |
| 🐙 **Git**            | Version control                        |
| 🐱 **GitHub**         | Repository & collaboration             |
| ⚙️ **GitHub Actions** | Continuous Integration                 |
| 🟨 **JavaScript**     | Task management logic                  |
| 📦 **npm**            | Package management & security auditing |

---

## 📁 Project Structure

```text
campuseats-task-tracker/
│
├── 📂 .github/
│   └── 📂 workflows/
│       └── ⚙️ ci.yml
│
├── 📂 src/
│   └── 📄 tasks.js
│
├── 📄 README.md
└── 📄 .gitignore
```

---

## ✨ Key Features

### 📋 Task Management

The project contains a simple task list for managing CampusEats-related tasks.

### 🌿 Git Branching

Development work is organized using feature and chore branches.

Example:

```text
main
 │
 ├── feature/add-task-list
 │
 └── chore/add-ci
```

### 🔀 Pull Requests

Changes are submitted through Pull Requests before being merged into the `main` branch.

This allows the project to demonstrate:

- 👀 Code review
- 💬 Review comments
- ✅ CI checks
- 🔀 Controlled merging

### ⚙️ Continuous Integration

GitHub Actions automatically runs the CI workflow when changes are pushed or a Pull Request is created.

The workflow:

```text
📤 Push / Pull Request
        ↓
⚙️ GitHub Actions
        ↓
📦 Checkout repository
        ↓
📂 List repository files
        ↓
🔍 Check README.md
        ↓
✅ CI Passed
```

---

## 🔐 Security & Code Quality

The project also demonstrates basic secure coding practices.

### ✅ Improvements

- Clear and descriptive variable names
- Constants used instead of magic numbers
- Input validation
- Strict equality (`===`)
- No hard-coded API keys
- Environment variables used for sensitive information

### 🚨 Security Rule

> **Never commit API keys, passwords, tokens, or other secrets to GitHub.**

Sensitive information should be stored using environment variables or a secure secrets-management system.

---

## 🔎 Dependency Security

The project can use:

```bash
npm audit
```

to check installed dependencies for known security vulnerabilities.

Where appropriate, safe fixes can be attempted with:

```bash
npm audit fix
```

---

## 🚀 Git Workflow

The project follows a simple collaborative development workflow:

```text
💻 Create / modify code
        ↓
🌿 Create branch
        ↓
💾 Commit changes
        ↓
📤 Push branch
        ↓
🔀 Create Pull Request
        ↓
👀 Code Review
        ↓
⚙️ CI Checks
        ↓
✅ Merge into main
```

---

## 🎯 Learning Objectives

This project demonstrates practical understanding of:

- 🐙 Git and GitHub
- 🌿 Branching strategies
- 🔀 Pull Requests
- 👥 Code reviews
- 🐛 GitHub Issues
- ⚙️ CI/CD
- 🔐 Secure coding
- 📊 Code quality
- 📦 Dependency security

---

## 👩‍💻 Academic Project

**Module:** SE3090 – Software Engineering Frameworks
**Project:** CampusEats Task Tracker
**Purpose:** Git, Collaborative Development, CI/CD, Security & Code Quality Practical

---

<p align="center">

### 🍔 CampusEats Task Tracker

**Build • Review • Test • Secure • Collaborate 🚀**

</p>
