# QAAgility ROI Calculator

Static site containing `qaagility-roi-calculator.html`.

## Files added for deployment

- `index.html` - root entrypoint (redirects to `qaagility-roi-calculator.html`)
- `vercel.json` - serves `/` from `qaagility-roi-calculator.html`
- `.gitignore` - ignores local deployment/system files

## Deploy to GitHub

1. Create a new GitHub repository.
2. Upload/push these files from this folder:
   - `qaagility-roi-calculator.html`
   - `index.html`
   - `vercel.json`
   - `.gitignore`
   - `README.md`

Example commands (run inside this folder):

```bash
git init
git add .
git commit -m "Prepare QAAgility ROI calculator for GitHub and Vercel deployment"
git branch -M main
git remote add origin <YOUR_GITHUB_REPO_URL>
git push -u origin main
```

## Deploy to Vercel

### Option A: From GitHub (recommended)
- In Vercel, import your GitHub repository.
- Framework preset: `Other`.
- Root directory: repository root (this folder).
- Build command: leave empty.
- Output directory: leave empty.
- Deploy.

### Option B: Vercel CLI

```bash
npm i -g vercel
vercel
vercel --prod
```
