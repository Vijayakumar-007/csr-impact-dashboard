# ImpactSphere — CSR Impact Dashboard Demo

A responsive, frontend-only CSR impact analysis dashboard built with HTML, CSS, and vanilla JavaScript. No build step or backend is required.

## Features
- Overview dashboard with KPI cards and visual charts
- CSR project cards with search and category/status filters
- Impact analysis metrics and measurement framework
- Beneficiary summary table
- Report library with working CSV exports
- Workspace settings demo
- Responsive desktop/mobile sidebar
- All sample figures are fictional

## Run locally
Open `index.html` in a browser. Or run a local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish on GitHub Pages
1. Create a new public repository on GitHub, for example `csr-impact-dashboard`.
2. Upload `index.html` and `README.md` to the repository root, or push them using Git.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish. Your URL will look like:
   `https://YOUR-GITHUB-USERNAME.github.io/csr-impact-dashboard/`

## Push with Git
```bash
git init
git add index.html README.md
git commit -m "Add CSR impact dashboard demo"
git branch -M main
git remote add origin https://github.com/YOUR-GITHUB-USERNAME/csr-impact-dashboard.git
git push -u origin main
```

Then enable GitHub Pages as described above.

## Notes
This is a UI prototype only. Buttons that imply saving a new project show demo notices because there is no backend. Report export buttons download sample CSV files. Replace fictional metrics with verified data before using this for real reporting.
