# GitHub Guide

**Manage your code and present your work professionally.**

[← Help Home](README.md)

---

## 1. Repository Organization

Use a clear structure for your Java projects.

Example:

```text
inventory-management-system/
├── src/
│   ├── main/
│   │   ├── java/
│   │   └── resources/
│   └── test/
├── docs/
├── .gitignore
├── pom.xml
└── README.md
```

The exact structure depends on the project and framework.

## 2. Essential Git Workflow

A typical workflow:

```bash
git status
git add .
git commit -m "Add product management feature"
git push
```

Useful commands:

| Command | Purpose |
|---|---|
| `git clone` | Clone a repository |
| `git status` | Check working tree status |
| `git add` | Stage changes |
| `git commit` | Save a snapshot |
| `git pull` | Retrieve remote changes |
| `git push` | Upload local commits |
| `git branch` | List or manage branches |
| `git switch` | Switch branches |
| `git log` | View commit history |

## 3. Commit Message Examples

Use clear messages that describe the change:

```text
Add user registration endpoint
Implement product search
Fix order validation
Add integration tests for authentication
Update API documentation
```

Avoid vague messages such as:

```text
update
changes
final
test
```

## 4. Suggested Branch Strategy

For individual learning projects, a simple structure is sufficient:

- `main`: stable application version.
- `feature/...`: new features.
- `fix/...`: bug fixes.

Example:

```bash
git switch -c feature/product-management
```

You do not need a complicated branching strategy for every small project.

## 5. Repository Quality Checklist

Before publishing a repository:

- [ ] Add a descriptive repository name.
- [ ] Write a professional README.
- [ ] Include setup and run instructions.
- [ ] Add a suitable `.gitignore`.
- [ ] Exclude build output and IDE-specific files when appropriate.
- [ ] Never commit passwords, tokens, or secrets.
- [ ] Use meaningful commit messages.
- [ ] Keep the default branch stable.
- [ ] Include tests where appropriate.
- [ ] Document API endpoints and configuration.

## 6. Useful GitHub Features

Explore these features as your projects grow:

- Issues.
- Pull Requests.
- Branches.
- Releases.
- GitHub Actions.
- Repository README.
- Project Boards.

---

**Your GitHub profile should demonstrate what you can build and how clearly you can explain your work.**

[← Help Home](README.md)
