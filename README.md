# .github

## MkDocs Documentation Site

This repository contains the MkDocs documentation site for the Zoning for Zero Foundation, automatically deployed to GitHub Pages.

### Features

- **Material Theme**: Modern, responsive design with teal color palette
- **LaTeX Support**: Mathematical equations rendered with MathJax
- **Auto-deployment**: Automatically deploys to GitHub Pages on merge to main branch

### Local Development

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Serve the documentation locally:
   ```bash
   mkdocs serve
   ```

3. Build the documentation:
   ```bash
   mkdocs build
   ```

### Structure

- `docs/` - Documentation source files (Markdown)
- `mkdocs.yml` - MkDocs configuration
- `.github/workflows/deploy-mkdocs.yml` - GitHub Actions deployment workflow

### Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch. The workflow builds the MkDocs site and deploys it using GitHub Pages.