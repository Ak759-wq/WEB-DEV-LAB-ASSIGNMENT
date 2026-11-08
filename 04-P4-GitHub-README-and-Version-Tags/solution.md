
# P4: GitHub README and Version Tags

## Objective
To create project documentation using README.md, understand Git version tagging, and publish a version tag to GitHub.

## Commands Used
- touch: Creates a file.
- code: Opens files in VS Code.
- git add: Stages files.
- git commit: Saves changes.
- git tag: Creates a version tag.
- git push: Pushes commits and tags.
- git log: Displays commit history.

## Steps

### 1. Created the README file:

```bash
touch README.md
```

### 2. Opened README.md in VS Code:

```bash
code README.md
```

### 3. Added project documentation using the VS Code editor and saved the file.

### 4. Checked the repository status:

```bash
git status
```

### 5. Staged the README file:

```bash
git add README.md
```

### 6. Committed the documentation:

```bash
git commit -m "Add project README"
```

### 7. Pushed the changes to GitHub:

```bash
git push origin main
```

### 8. Created an annotated version tag:

```bash
git tag -a v1.0.0 -m "First stable release"
```

### 9. Pushed the version tag to GitHub:

```bash
git push origin v1.0.0
```

### 10. Verified available tags:

```bash
git tag
```

### 11. Checked commit history:

```bash
git log --oneline
```

## Expected Output

v1.0.0

## Result
Successfully created project documentation, committed the README file, created an annotated version tag v1.0.0, and pushed the tag to GitHub.
