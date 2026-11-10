# P4: GitHub README and Version Tags

## Objective

To understand how to create project documentation using README.md, manage changes using Git, create annotated version tags, and publish releases to GitHub.

## Tools Used

- Git
- GitHub
- Visual Studio Code
- macOS Terminal

## Commands Used

| Command | Purpose |
|---|---|
| `touch README.md` | Creates a README file |
| `code README.md` | Opens README in VS Code |
| `git status` | Checks repository status |
| `git add` | Stages changes |
| `git commit` | Saves changes |
| `git push` | Uploads commits to GitHub |
| `git tag -a` | Creates an annotated version tag |
| `git push origin v1.0.0` | Publishes the version tag |
| `git tag` | Lists available tags |
| `git log --oneline` | Displays commit history |

## Procedure

### 1. Create the README file

```bash
touch README.md
```

### 2. Open the README file

```bash
code README.md
```

### 3. Add project documentation

Added the objective, tools, commands, procedure, and expected results to the README file.

### 4. Check repository status

```bash
git status
```

### 5. Stage the README file

```bash
git add README.md
```

### 6. Commit the documentation

```bash
git commit -m "Add P4 README documentation"
```

### 7. Push changes to GitHub

```bash
git push origin main
```

### 8. Create an annotated version tag

```bash
git tag -a v1.0.0 -m "First stable release"
```

### 9. Push the version tag

```bash
git push origin v1.0.0
```

### 10. Verify available tags

```bash
git tag
```

### 11. Check commit history

```bash
git log --oneline
```

## Expected Output

```text
v1.0.0
```

## Result

Successfully created project documentation using README.md, committed and pushed the documentation to GitHub, created an annotated version tag v1.0.0, and verified the tag and Git commit history.