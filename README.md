# DevOps Git Task – Version-Controlled Project

##  Objective
To build a version-controlled DevOps project using **Git** and **GitHub** following best practices.

---

##  Tools Used
- Git
- GitHub

---

##  Project Structure
- `main` branch – Production-ready code.
- `dev` branch – Development integration.
- `feature-*` branches – New features are built here.

---

##  Git Workflow
1. Initialize Git in local project.
2. Push to GitHub remote repository.
3. Create `dev` and `feature-*` branches.
4. Make changes in `feature-*` branch.
5. Create Pull Request to merge `feature` into `dev`.
6. Merge `dev` into `main` after testing.
7. Use `.gitignore` to ignore unnecessary files.
8. Use Git **tags** for marking releases (e.g., `v1.0`).

---

##  Files and Folders
- `.gitignore` – To exclude unnecessary files like logs, cache, etc.
- `README.md` – This file.
- `login.txt` – Example feature file.

---

##  Tags
- `v1.0` – Initial stable version

---

##  How to Use
```bash
# Clone the repository
git clone https://github.com/<Satyaranjan-07>/devops-git-task.git

# Switch to dev branch
git checkout dev

# Create a new feature branch
git checkout -b feature-new

# Make changes, commit, and push
git add .
git commit -m "Your message"
git push origin feature-new

