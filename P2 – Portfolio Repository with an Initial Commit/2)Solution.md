
# P2: Portfolio Repository with an Initial Commit

## Objective
To create a portfolio website, initialize a Git repository, configure user details, track project files, and create the initial commit.

## Commands Used
- mkdir: Creates a directory.
- cd: Changes directory.
- touch: Creates files.
- code: Opens files in VS Code.
- git init: Initializes a Git repository.
- git config: Configures user details.
- git add: Stages files.
- git commit: Creates a commit.
- git log: Displays commit history.

## Steps

### 1. Created a portfolio project folder:

```bash
mkdir MyPortfolio
cd MyPortfolio
```

### 2. Created the starter files:

```bash
touch index.html style.css script.js
```

### 3. Opened the HTML and CSS files in VS Code:

```bash
code index.html style.css
```

### 4. Added HTML content to index.html and CSS content to style.css using the VS Code editor.

### 5. Initialized the Git repository:

```bash
git init
```

### 6. Configured Git user details:

```bash
git config user.name "Aditya Kumar"
git config user.email "YOUR_GITHUB_EMAIL"
```

### 7. Checked repository status:

```bash
git status
```

### 8. Added all project files to the staging area:

```bash
git add .
```

### 9. Created the initial commit:

```bash
git commit -m "Initial commit for portfolio"
```

### 10. Checked commit history:

```bash
git log --oneline
```

### 11. Connected the GitHub repository:

```bash
git remote add origin YOUR_REPOSITORY_URL
```

### 12. Pushed the project to GitHub:

```bash
git branch -M main
git push -u origin main
```

Note: If working inside an already cloned repository, skip git init and git remote add origin.

## Result
Successfully created a portfolio website, initialized Git, configured user details, staged project files, created the initial commit, and pushed the repository to GitHub.
