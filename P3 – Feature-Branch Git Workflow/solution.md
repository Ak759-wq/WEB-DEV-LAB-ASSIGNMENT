
# P3: Feature-Branch Git Workflow

## Objective
To understand Git branching by creating a feature branch, making changes, committing them, pushing the branch, and merging it into the main branch.

## Commands Used
- git branch: Lists branches.
- git switch -c: Creates and switches to a new branch.
- touch: Creates files.
- code: Opens files in VS Code.
- git status: Checks repository status.
- git add: Stages changes.
- git commit: Saves changes.
- git push: Uploads changes.
- git merge: Merges branches.

## Steps

### 1. Checked the existing branches:

```bash
git branch
```

### 2. Created and switched to a feature branch:

```bash
git switch -c feature/about-section
```

### 3. Created the About page and CSS file:

```bash
touch about.html style.css
```

### 4. Opened the files in VS Code:

```bash
code about.html style.css
```

### 5. Added HTML content to about.html and CSS content to style.css using the VS Code editor.

### 6. Checked the repository status:

```bash
git status
```

### 7. Staged the changes:

```bash
git add .
```

### 8. Committed the feature:

```bash
git commit -m "Add about section"
```

### 9. Pushed the feature branch to GitHub:

```bash
git push -u origin feature/about-section
```

### 10. Switched back to the main branch:

```bash
git switch main
```

### 11. Updated the main branch:

```bash
git pull origin main
```

### 12. Merged the feature branch:

```bash
git merge feature/about-section
```

### 13. Pushed the updated main branch:

```bash
git push origin main
```

### 14. Verified the branches:

```bash
git branch
```

## Expected Branch Structure

main
└── feature/about-section

## Result
Successfully created a feature branch, added and committed new features, pushed the branch to GitHub, and merged the changes into the main branch.
