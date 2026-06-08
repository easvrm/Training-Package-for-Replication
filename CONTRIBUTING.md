# Contributing Guide

Thank you for contributing to the **Training Package for Replication** project!
Please follow this workflow to keep collaboration smooth and organized.

---

## Branching Strategy

We use a simple **feature branch** workflow:

```
master          ← stable, production-ready content
  └── feature/your-topic    ← your working branch
  └── fix/issue-description ← for bug fixes
```

**Never commit directly to `master`.**

---

## Step-by-Step Workflow

### 1. Clone the repository (first time only)
```bash
git clone https://github.com/johnpunzalan-eis/Training-Package-for-Replication.git
cd Training-Package-for-Replication
```

### 2. Always start from an updated master
```bash
git checkout master
git pull origin master
```

### 3. Create your working branch
```bash
# For new content or features
git checkout -b feature/your-topic-name

# For fixes
git checkout -b fix/what-you-are-fixing
```

### 4. Make your changes, then commit
```bash
git add .
git commit -m "Short description of what you changed"
```

> Use clear commit messages. Example:  
> `"Add module 3 slides and facilitator notes"`

### 5. Push your branch to GitHub
```bash
git push origin feature/your-topic-name
```

### 6. Open a Pull Request (PR)
- Go to the repository on GitHub
- Click **"Compare & pull request"**
- Fill in the PR template
- Assign a reviewer (e.g. the other team member)

### 7. Review & Merge
- The reviewer checks the changes and leaves comments if needed
- Once approved, the PR is merged into `master`
- The branch is deleted after merging

---

## Rules

| Rule | Why |
|------|-----|
| One PR per topic/feature | Easier to review and revert |
| No direct commits to `master` | Protects stable content |
| Always pull before starting new work | Avoids merge conflicts |
| Write clear commit messages | Easier to track history |

---

## Need Help?

Open an [Issue](https://github.com/johnpunzalan-eis/Training-Package-for-Replication/issues) and describe your question or problem.
