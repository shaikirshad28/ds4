# Student Management System

A simple Student Management System developed using HTML, CSS and JavaScript.  
Git and GitHub are used for version control, branching and merging.

## Technologies Used

- HTML
- CSS
- JavaScript
- Git
- GitHub
- VS Code

## Project Features

- Student Registration
- Student Search
- Git Branching
- Git Merging
- GitHub Repository

---

# Git Commands Used

## 1. Check Git Version

```bash
git --version
```

Checks whether Git is installed on the system.

---

## 2. Initialize Git Repository

```bash
git init
```

Creates a new Git repository in the project folder.

---

## 3. Check Repository Status

```bash
git status
```

Shows modified, untracked and staged files.

---

## 4. Add Files to Staging Area

```bash
git add .
```

Adds all project files to the staging area.

---

## 5. Create Initial Commit

```bash
git commit -m "Initial commit"
```

Creates the first version of the project in Git.

---

## 6. Rename Branch to Main

```bash
git branch -M main
```

Renames the current branch to `main`.

---

# Creating Student Registration Branch

## 7. Create Student Registration Branch

```bash
git branch student-registration
```

Creates a new branch for the Student Registration feature.

---

## 8. Switch to Student Registration Branch

```bash
git switch student-registration
```

Moves from the `main` branch to the `student-registration` branch.

---

## 9. Check Current Branch

```bash
git branch
```

The `*` shows the branch currently being used.

Example:

```text
  main
* student-registration
  student-search
```

---

## 10. Add Registration Changes

```bash
git add .
```

Adds the registration changes to the staging area.

---

## 11. Commit Registration Feature

```bash
git commit -m "Added student registration feature"
```

Saves the Student Registration feature in Git history.

---

# Creating Student Search Branch

## 12. Switch Back to Main

```bash
git switch main
```

Moves back to the main branch.

---

## 13. Create Student Search Branch

```bash
git branch student-search
```

Creates a new branch for the Student Search feature.

---

## 14. Switch to Student Search Branch

```bash
git switch student-search
```

Moves to the Student Search branch.

---

## 15. Add Search Changes

```bash
git add .
```

Adds the Student Search changes to the staging area.

---

## 16. Commit Student Search Feature

```bash
git commit -m "student search"
```

Saves the Student Search feature in Git history.

---

# Merging Branches

## 17. Switch to Main Branch

```bash
git switch main
```

Moves back to the main branch before merging.

---

## 18. Merge Student Registration

```bash
git merge student-registration
```

Merges the Student Registration feature into `main`.

---

## 19. Merge Student Search

```bash
git merge student-search
```

Merges the Student Search feature into `main`.

---

## 20. Check Branches

```bash
git branch
```

Shows all available branches.

Example:

```text
* main
  student-registration
  student-search
```

---

## 21. View Commit History

```bash
git log --oneline
```

Displays the commit history in a short format.

---

# GitHub Commands

## 22. Add GitHub Remote Repository

```bash
git remote add origin https://github.com/USERNAME/student-management.git
```

Connects the local Git repository to the GitHub repository.

Replace `USERNAME` with your GitHub username.

---

## 23. Check Remote Repository

```bash
git remote -v
```

Shows the GitHub repository connected to the project.

---

## 24. Push Main Branch to GitHub

```bash
git push -u origin main
```

Uploads the `main` branch to GitHub.

The `-u` connects the local `main` branch with the remote `main` branch.

---

# Future Changes

Whenever changes are made to the project:

```bash
git add .
git commit -m "Updated project"
git push
```

---

# Clone Repository

To download the project from GitHub to another computer:

```bash
git clone https://github.com/USERNAME/student-management.git
```

Then enter the project folder:

```bash
cd student-management
```

---

# Complete Git Workflow

The complete workflow used in this project is:

```bash
git init

git status

git add .

git commit -m "Initial commit"

git branch -M main

git branch student-registration

git switch student-registration

git add .

git commit -m "Added student registration feature"

git switch main

git branch student-search

git switch student-search

git add .

git commit -m "student search"

git switch main

git merge student-registration

git merge student-search

git branch

git log --oneline

git remote add origin https://github.com/USERNAME/student-management.git

git remote -v

git push -u origin main
```

## Branch Structure

```text
main
│
├── student-registration
│
└── student-search
```

Both feature branches are finally merged into the `main` branch.

## Conclusion

This project demonstrates how Git can be used to create separate branches for different features, develop them independently, and merge them into the main project.
