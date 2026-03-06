---
description: Release workflow — version, changelog, tag, release
---

# 🏷️ Release Workflow

Follow these steps for every new release:

## 1. Determine Version (Semantic Versioning)

```
v MAJOR.MINOR.PATCH

PATCH  → Bug fixes only, no new features         e.g. v1.0.1
MINOR  → New features, backward compatible       e.g. v1.1.0
MAJOR  → Breaking changes                        e.g. v2.0.0
```

// turbo-all

## 2. Create Issue

```bash
gh issue create --title "release: vX.Y.Z — [summary]" --label "documentation"
```

## 3. Create Branch

```bash
git checkout -b release/vX.Y.Z
```

## 4. Update CHANGELOG.md

Add a new section at the top (above previous version):

```markdown
## [X.Y.Z] - YYYY-MM-DD

### 🎉 [Headline]

[Release summary]

### 🐛 Fixed
- [Bug description] (#issue_number)

### ✨ Added / Improved
- [Feature or improvement] (#issue_number)

### 📝 Documentation
- [Doc changes]
```

Follow [Keep a Changelog](https://keepachangelog.com/) format.

## 5. Commit + Push + PR

```bash
git add CHANGELOG.md
git commit -m "release: vX.Y.Z — [summary]

Fixes #ISSUE_NUMBER"
git push origin release/vX.Y.Z
```

Create PR → Review → Merge

## 6. Create Git Tag

```bash
git checkout main
git pull origin main
git tag -a vX.Y.Z -m "vX.Y.Z: [summary]"
git push origin vX.Y.Z
```

## 7. Create GitHub Release

```bash
gh release create vX.Y.Z \
  --title "vX.Y.Z — [title]" \
  --notes "[release notes in markdown]"
```

Or use GitHub UI: **"Draft a new release"** → select tag → write notes

## Summary

```
Issue → Branch → CHANGELOG → Commit → PR → Merge → Tag → Release
```

> ⚠️ **Never** create a tag/release without updating CHANGELOG.md first.
