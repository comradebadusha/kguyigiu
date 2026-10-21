# Badusha VC portfolio

Static site: `index.html` plus an `assets/` folder. No build step.

## Put it on GitHub
1. Create a new repository on github.com (for example `portfolio`).
2. Click "uploading an existing file" and drag in everything from this folder: `index.html`, `vercel.json`, `README.md` and the whole `assets` folder.
3. Commit the changes.

## Host it on Vercel
1. Sign in at vercel.com with your GitHub account.
2. Click Add New, then Project, and import the repository.
3. Leave Framework Preset as "Other", leave the build command and output directory empty, and click Deploy.
4. Every later commit to GitHub redeploys the site automatically.

## Editing
- Swap a poster by replacing its file in `assets/posters/` with the same name.
- Reel links, contact details and text are all in `index.html`.
