# Git Branch & Workflow Guide

## 1. What is a Git Branch?

A `branch` is a separate working version of your project in Git.

Each branch can contain different code without affecting the main branch (`main`).

Example:

- `main` → stable code
- `feature/dark-mode` → dark mode feature

---

# Why do we use branches?

If you code directly on `main`:

- you can accidentally break the project
- fixing bugs becomes harder
- teamwork becomes messy

In real companies:

- every new feature is developed on a separate branch
- after testing, it is merged into `main`

---

# Standard Workflow

```bash
main
 ├── feature/dark-mode

 
```

Each developer works on a separate branch → no code conflicts.

---

# 2. View Branches

## Command

```bash
git branch
```

## Example

```bash
git branch
```

## Output

```bash
* main
  feature-navbar
```

The `*` shows the current branch.

You are currently on `main`.

---

# 3. Create a New Branch

## Command

```bash
git branch branch-name
```

## Example

```bash
git branch feature/dark-mode
```

This command only creates the branch.
It does NOT switch to it.

---

# 4. git checkout -b

## Purpose

- create a new branch
- switch to the new branch immediately

## Syntax

```bash
git checkout -b branch-name
```

## Example

```bash
git checkout -b feature/dark-mode
```

Git will:

1. create `feature/dark-mode`
2. switch to that branch

---

# Check Current Branch

```bash
git branch
```

Output:

```bash
  main
* feature/dark-mode
```

Now you are working in your own branch.

---

# 5. Work on a Feature Branch

Example:

- edit CSS
- add dark mode
- commit your changes

```bash
git add .
git commit -m "Add dark mode"
```

This code only exists inside `feature/dark-mode`.

`main` is still safe.

---

# 6. git checkout

## Purpose

Switch between branches.

## Example

```bash
git checkout main
```

Switch back to the `main` branch.

---

# 7. git merge

## Purpose

Combine code from another branch into the current branch.

---

# Example: Merge Dark Mode into Main

## Step 1: Switch to main

```bash
git checkout main
```

## Step 2: Merge

```bash
git merge feature/dark-mode
```

Git takes all code from `feature/dark-mode`
and combines it into `main`.

---

# After Merge

```bash
main
 └── now includes dark mode
```

---

# 8. git pull

## Purpose

Download the latest code from GitHub.

---

# Syntax

```bash
git pull
```

---

# Example

Before starting work:

```bash
git pull
```

This ensures your local project is up to date.

---

# git pull Actually Means

```bash
git fetch + git merge
```

---

# 9. git log --oneline

## Purpose

View commit history in a short format.

---

# Command

```bash
git log --oneline
```

## Example Output

```bash
a1b2c3 Add dark mode
d4e5f6 Create navbar
g7h8i9 First commit
```

- left side → commit ID
- right side → commit message

---

# 10. Real Company Workflow

## Step 1

Pull the latest code

```bash
git pull
```

---

## Step 2

Create a feature branch

```bash
git checkout -b feature/navbar
```

---

## Step 3

Develop the feature

```bash
git add .
git commit -m "Create navbar"
```

---

## Step 4

Merge into main

```bash
git checkout main
git merge feature/navbar
```

---

# 11. Complete Example

## Create a branch

```bash
git checkout -b feature/dark-mode
```

---

## Commit your work

```bash
git add .
git commit -m "Add dark mode"
```

---

## Switch back to main

```bash
git checkout main
```

---

## Merge the branch

```bash
git merge feature/dark-mode
```

---

# 12. Important Git Mindset

## main

- stable code
- production-ready code
- do not edit directly

---

## feature branches

- experiment safely
- add new features
- fix bugs

---

# 13. Best Practices

✅ One feature = one branch

✅ Write small and clear commits

✅ Always pull before coding

✅ Never code directly on `main`

✅ Merge only after testing

---

# 14. Important Commands

| Command | Purpose |
|---|---|
| `git branch` | view branches |
| `git branch name` | create branch |
| `git checkout name` | switch branch |
| `git checkout -b name` | create + switch branch |
| `git merge name` | merge branch |
| `git pull` | get latest code |
| `git log --oneline` | view commit history |

---

# 15. Practice Exercise

## Dark Mode Workflow

### Create a branch

```bash
git checkout -b feature/dark-mode
```

### Add CSS

```css
body {
  background: black;
  color: white;
}
```

### Commit changes

```bash
git add .
git commit -m "Add dark mode"
```

### Merge into main

```bash
git checkout main
git merge feature/dark-mode
```

This is the same workflow used in real companies.