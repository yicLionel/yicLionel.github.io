# Yichen YAN Personal Blog

Static CV-style personal website prepared for GitHub Pages.

## Local Preview

```bash
npm run dev
```

Open `http://localhost:3001`.

## Deploy to GitHub Pages

### Option A: project site

Use the current repository, for example `Personal_CV_BLOG`. After pushing to GitHub, open the repository settings:

1. Go to `Settings` -> `Pages`.
2. Under `Build and deployment`, choose `Deploy from a branch`.
3. Set branch to `main` and folder to `/ (root)`.
4. Save.

The site URL will be similar to:

```text
https://yicLionel.github.io/Personal_CV_BLOG/
```

### Option B: user site

If you want the root URL `https://yicLionel.github.io/`, create or use a repository named exactly `yicLionel.github.io`, then push this site into that repository.

## Files

The site uses `index.html`, `styles.css`, `assets/profile.jpg`, blog pages in `blog/`, and PDFs in `docs/`.
