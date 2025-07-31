# 🚀 How to Host Your Project on GitHub Using Git

This guide walks you through hosting any local project on GitHub using Git.

---

## ✅ Prerequisites

- Git installed → [Install Git](https://git-scm.com/downloads)
- A GitHub account → [Create an account](https://github.com)

---

## 📁 Step 1: Create a Repository on GitHub

1. Go to [GitHub](https://github.com)
2. Click on the **+** icon → **New repository**
3. Fill in:
   - **Repository name** (e.g., `my-project`)
   - Optional: description
   - Visibility: **Public** or **Private**
4. (Optional) Check “Initialize with a README”
5. Click **Create repository**

---

## 🧑‍💻 Step 2: Set Up Git in Your Local Project

### If your project already exists:

```bash
cd path/to/your/project
```
### If you're starting fresh:
```bash
mkdir my-project
cd my-project
git init
```
### 🔗 Step 3: Link Local Project to GitHub
Get the GitHub repo URL:

For HTTPS:
```bash
git remote add origin https://github.com/your-username/my-project.git
```
For SSH:
```
git remote add origin git@github.com:your-username/my-project.git
```
### 📦 Step 4: Add, Commit, and Push Your Code
```bash
git add .
git commit -m "Initial commit"
git push -u origin main
```

## 🧰 Useful Git Commands

| 🧱 Task             | 💻 Command                        |
|--------------------|-----------------------------------|
| Check status        | `git status`                     |
| Add all changes     | `git add .`                      |
| Commit changes      | `git commit -m "message"`        |
| Push to GitHub      | `git push`                       |
| Pull from GitHub    | `git pull`                       |
| Clone a repo        | `git clone <repo-url>`           |


---

You can save this as `README.md` and upload or push it along with your project.

Let me know if you want this customized for your own project (e.g. with your repo name, username, etc.).

