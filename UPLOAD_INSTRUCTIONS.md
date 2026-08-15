# Uploading the RAISE-HE Observatory to a different GitHub account

## Files to upload

Extract the supplied ZIP package first. Upload these files—not the ZIP itself—to the repository root:

1. `index.html`
2. `.nojekyll`
3. `README.md`
4. `FULL_RECREATION_PROMPT.md`
5. `UPLOAD_INSTRUCTIONS.md`

## Method 1: GitHub website

### Step 1 — Create the repository

1. Sign in to the new GitHub account.
2. Select **New repository**.
3. Repository name: `raise-he-policy-observatory`
4. Suggested description: `Interactive RAISE-HE Policy Observatory and Responsible GenAI Integration Readiness prototype.`
5. Select **Public**. GitHub Pages availability can depend on the account plan when a repository is private.
6. You may leave **Add README**, `.gitignore`, and licence unchecked because the package already contains a README.
7. Select **Create repository**.

### Step 2 — Upload the files

1. In the empty repository, select **uploading an existing file**, or select **Add file → Upload files**.
2. Drag the five extracted files into the upload area.
3. Confirm that `index.html` is in the repository root—not inside another folder.
4. Commit message: `Add RAISE-HE Policy Observatory`
5. Select **Commit directly to the main branch**.
6. Select **Commit changes**.

### Step 3 — Enable GitHub Pages

1. Open the repository's **Settings** tab.
2. In the left menu, select **Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Under **Branch**, select `main` and `/(root)`.
5. Select **Save**.
6. Wait approximately 1–5 minutes and refresh the Pages settings screen.

Your website should appear at:

`https://YOUR-GITHUB-USERNAME.github.io/raise-he-policy-observatory/`

Replace `YOUR-GITHUB-USERNAME` with the new account username.

## Method 2: Git command line

Create the empty GitHub repository first, then run the following commands inside the extracted package folder. Replace `YOUR-GITHUB-USERNAME` before running them.

```bash
git init
git add index.html .nojekyll README.md FULL_RECREATION_PROMPT.md UPLOAD_INSTRUCTIONS.md
git commit -m "Add RAISE-HE Policy Observatory"
git branch -M main
git remote add origin https://github.com/YOUR-GITHUB-USERNAME/raise-he-policy-observatory.git
git push -u origin main
```

Then enable Pages using **Settings → Pages → Deploy from a branch → main → /(root) → Save**.

## Updating the website later

1. Edit `index.html` locally or on GitHub.
2. Commit the revised file to `main`.
3. GitHub Pages will redeploy automatically.
4. If the old page remains visible, wait a few minutes and refresh using `Ctrl + F5`.

## Common problems

### The page shows only the README

Check that the website URL contains the repository name and that `index.html` is at the repository root.

### GitHub Pages says 404

Confirm that:

- the repository is public;
- Pages source is `main` and `/(root)`;
- the deployment has completed under the **Actions** tab;
- the URL spelling matches the GitHub username and repository name.

### The page looks unchanged after an edit

Wait for the Pages deployment to finish, then use `Ctrl + F5` or open the site in a private/incognito window.

### The map or controls are missing

Upload the complete supplied `index.html`. Do not paste only the visible HTML body, because the same file also contains all CSS, JavaScript, SVG icons and map code.

