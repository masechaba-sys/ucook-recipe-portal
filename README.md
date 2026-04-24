# UCook Recipe Portal — UX Redesign Spec

Annotated design mockups for the UCook Recipe Portal redesign. Prepared for development handoff.

---

## Deploy to GitHub Pages (5 min)

### Step 1 — Create the repository

1. Go to [github.com/new](https://github.com/new)
2. Name it something like `ucook-recipe-portal-spec`
3. Set visibility to **Private** (recommended — internal design doc)
4. **Do not** initialise with a README (you already have one)
5. Click **Create repository**

### Step 2 — Push these files

Open a terminal in this folder and run:

```bash
git init
git add .
git commit -m "Initial: UCook Recipe Portal UX spec"
git branch -M main
git remote add origin https://github.com/YOUR-ORG/ucook-recipe-portal-spec.git
git push -u origin main
```

> Replace `YOUR-ORG` with your GitHub username or organisation name.

### Step 3 — Enable GitHub Pages

1. In the repo, go to **Settings → Pages**
2. Under **Source**, select **Deploy from a branch**
3. Branch: `main` · Folder: `/ (root)`
4. Click **Save**

GitHub will build and publish the site. After ~60 seconds your spec will be live at:

```
https://YOUR-ORG.github.io/ucook-recipe-portal-spec/
```

Share that URL directly with the developer — no login required if the repo is public, or use GitHub's **collaborator** invite for a private repo.

---

## Files in this project

| File | Purpose |
|---|---|
| `index.html` | The full annotated design spec (self-contained, no dependencies) |
| `.nojekyll` | Tells GitHub Pages to serve the HTML directly without Jekyll processing |
| `README.md` | This file |

---

## Updating the spec

Edit `index.html` locally, then push:

```bash
git add index.html
git commit -m "Update: describe your change here"
git push
```

GitHub Pages will re-deploy automatically within ~60 seconds.
