---
description: Git workflow — always create Issue + PR before committing
---

# Git Workflow Rules

**Always** follow these steps when committing code changes. No exceptions.

## Steps

// turbo-all

1. **Create GitHub Issue** — describe the bug or feature
   - Add appropriate label (`bug`, `enhancement`, `documentation`)

2. **Create Branch** from `main`
   - Format: `fix/issue-description`, `feat/issue-description`, `docs/...`, `style/...`
   ```bash
   git checkout -b fix/day2-syntax-error
   ```

3. **Commit + Push** to the branch
   - Commit message must reference issue: `Fixes #XX`
   ```bash
   git add .
   git commit -m "fix: description. Fixes #XX"
   git push origin branch-name
   ```

4. **Create Pull Request** — link to Issue
   - PR body must include `Fixes #XX`

5. **Merge PR** — use squash merge

6. **Pull main** — sync local
   ```bash
   git checkout main && git pull origin main
   ```

## ⚠️ Never Do

- ❌ **Never push directly to main** without a PR
- ❌ **Never commit without creating an Issue first**
- ❌ **Never forget to link the Issue** in commit message
