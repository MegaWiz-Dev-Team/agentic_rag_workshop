---
description: Git workflow — สร้าง Issue + PR ก่อน commit ทุกครั้ง
---

# Git Workflow Rules

เมื่อต้อง commit code changes ให้ทำตามขั้นตอนนี้ **ทุกครั้ง** ห้ามข้าม:

## ขั้นตอน

1. **สร้าง GitHub Issue** — อธิบายปัญหาหรือ feature ที่ต้องทำ
   - ใส่ label ที่เหมาะสม (`bug`, `enhancement`, `docs`)

2. **สร้าง Branch** จาก `main`
   - ใช้ format: `fix/issue-description` หรือ `feat/issue-description`
   ```bash
   git checkout -b fix/day2-syntax-error
   ```

3. **Commit + Push** ไปที่ branch
   - Message ต้องอ้างอิง issue: `Fixes #XX`
   ```bash
   git add .
   git commit -m "fix: description. Fixes #XX"
   git push origin branch-name
   ```

4. **สร้าง Pull Request** — link กับ Issue
   - Body ต้องมี `Fixes #XX`

5. **Merge PR** — ใช้ squash merge

6. **Pull main** — sync local
   ```bash
   git checkout main && git pull origin main
   ```

## ⚠️ ห้ามทำ

- ❌ **ห้าม push ตรงไป main** โดยไม่ผ่าน PR
- ❌ **ห้าม commit โดยไม่สร้าง Issue ก่อน**
- ❌ **ห้ามลืม link Issue ใน commit message**
