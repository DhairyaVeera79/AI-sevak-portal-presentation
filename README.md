# AI Sevak Portal — Presentation Site

Single-page static presentation site for GitHub Pages submission.

## Files
- `index.html`
- `styles.css`

## Local Preview
From this folder, run:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## GitHub Pages Deploy

1. Create a GitHub repository and push this folder as its root.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
4. Save and wait for Pages to publish.
5. Open the generated URL and verify all 5 required sections are visible.

## Quick Push Commands

```bash
git add .
git commit -m "Build one-page AI Sevak Portal presentation site"
git branch -M main
git remote add origin <YOUR_GITHUB_REPO_URL>
git push -u origin main
```
