# Git Conflict Resolution Lab

A hands-on project demonstrating Git branching, merge conflicts, conflict resolution, and GitHub integration.

---

## 📌 Objective

This lab demonstrates how to:

- Create and manage Git branches
- Modify the same file in different branches
- Generate a merge conflict
- Resolve the merge conflict
- Use `.gitignore`
- Push the project to GitHub

---

## 🛠️ Tools Used

- Git
- Git Bash
- GitHub
- Visual Studio Code

---

## 📁 Project Structure

```
Git-Conflict-Resolution-Lab/
│── hello.xml
│── readme.txt
│── .gitignore
│── README.md
```

---

## 🚀 Workflow

1. Initialized a Git repository.
2. Created the initial commit.
3. Created a branch named `GitWork`.
4. Added `hello.xml` in the branch.
5. Switched to the `master` branch.
6. Added different content to `hello.xml`.
7. Compared both branches.
8. Merged `GitWork` into `master`.
9. Resolved the merge conflict.
10. Added `.gitignore`.
11. Deleted the merged branch.
12. Renamed the branch to `main`.
13. Pushed the project to GitHub.

---

## 💻 Git Commands Used

```bash
git init
git status
git add .
git commit -m "Initial commit"

git checkout -b GitWork

git checkout master

git diff master GitWork

git merge GitWork

git add hello.xml
git commit -m "Resolved merge conflict"

git branch -d GitWork

git branch -M main

git remote add origin https://github.com/harini106/Git-Conflict-Resolution-Lab.git

git push -u origin main
```

---

## 📂 Files

- `hello.xml`
- `readme.txt`
- `.gitignore`
- `README.md`

---

## ✅ Learning Outcome

- Learned Git branching.
- Understood merge conflicts.
- Resolved merge conflicts successfully.
- Used `.gitignore`.
- Uploaded a project to GitHub.

---

## 👩‍💻 Author

**T Harini**

GitHub: https://github.com/harini106
