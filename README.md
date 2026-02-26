
```
# 🚀 Task 4 - Build a Version-Controlled DevOps Project with Git

## 📌 Project Overview

This project demonstrates how to manage a DevOps project using Git best practices.  
It follows an industry-standard branching strategy and version control workflow.

The objective of this task is to understand how real-world DevOps teams use Git for:
- Code version control
- Branching strategy
- Feature development
- Pull requests
- Merging process
- Version tagging
- Documentation

---

## 🛠️ Tools Used

- Git
- GitHub
- Linux (Ubuntu EC2)
- Markdown Documentation

---

## 🌿 Branching Strategy Used

This project follows a structured branching model:

```

main
└── dev
└── feature/*

```

### 🔹 main Branch
- Contains stable, production-ready code.
- Only tested and approved changes are merged here.
- Represents the live version of the application.

### 🔹 dev Branch
- Used for integration and testing.
- All feature branches are merged into dev first.
- Acts as a staging branch before production.

### 🔹 feature Branch
- Used to develop new features independently.
- Example:
  - feature/add-login
  - feature/version2-upgrade

---

## 🔄 Workflow Followed

1. Initialize Git repository
2. Create main branch
3. Create dev branch
4. Create feature branch
5. Develop feature
6. Commit changes
7. Push feature branch
8. Create Pull Request (feature → dev)
9. Merge into dev
10. Merge dev → main
11. Create version tag

---

## 🧱 Project Structure

```

devops-git-project/
│
├── app.py
├── README.md
├── VERSION
├── .gitignore
├── docs/
│   └── tasks.md
└── screenshots/

```

---

## 🧑‍💻 Application Description

### Version 1.0
- Basic project structure
- Initial application setup
- Login feature added

### Version 2.0
- Added logging functionality
- Added VERSION tracking file
- Improved documentation
- Structured branching workflow

---

## 🏷️ Version Control (Tags)

Tags created in this project:

- v1.0 → Initial stable release
- v2.0 → Upgrade with logging and improvements

Tags help in tracking application releases.

---

## 📂 .gitignore Usage

The `.gitignore` file is used to prevent unnecessary files from being committed.

Example:
```

**pycache**/
*.log
.env

```

This ensures clean repository management.

---

## 🧠 Key Git Concepts Practiced

- git init
- git branch
- git checkout
- git add
- git commit
- git merge
- git push
- git pull
- git tag
- Pull Requests
- Merge Conflict Handling
---

## 👨‍💻 Author

**Nityam Raj**  
DevOps Enthusiast  
AWS | Git | Linux | CI/CD
