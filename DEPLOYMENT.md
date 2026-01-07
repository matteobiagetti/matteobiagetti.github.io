# Quick Deployment Guide

## Prerequisites

Make sure you have Git configured with your GitHub credentials.

## Step 1: Initialize Git Repository (if not already done)

```bash
cd /Users/matteobiagetti/GitProjects/matteo.biagetti.github.io
git init
git branch -M main
```

## Step 2: Add Remote Repository

```bash
# Replace with your actual GitHub username if different
git remote add origin https://github.com/matteo.biagetti/matteo.biagetti.github.io.git
```

## Step 3: Commit and Push

```bash
# Add all files
git add .

# Commit changes
git commit -m "Initial deployment of personal website with al-folio theme"

# Push to GitHub
git push -u origin main
```

## Step 4: Enable GitHub Pages

1. Go to your repository on GitHub: `https://github.com/matteo.biagetti/matteo.biagetti.github.io`
2. Click on **Settings** tab
3. Scroll down to **Pages** section (in the left sidebar under "Code and automation")
4. Under **Source**, select:
   - Branch: `gh-pages`
   - Folder: `/ (root)`
5. Click **Save**

## Step 5: Wait for Deployment

- GitHub Actions will automatically build and deploy your site
- Check the **Actions** tab to monitor the deployment progress
- Once complete (green checkmark), your site will be live at `https://matteo.biagetti.github.io`
- First deployment may take 5-10 minutes

## Troubleshooting

### If the site doesn't build:

1. Check the Actions tab for error messages
2. Ensure all required files are present
3. Verify Ruby and Jekyll versions in `.github/workflows/deploy.yml`

### If the site shows 404:

1. Wait a few more minutes for DNS propagation
2. Check that Pages is enabled in repository settings
3. Verify the gh-pages branch exists after the workflow runs

## Future Updates

After initial deployment, simply:

```bash
git add .
git commit -m "Update content"
git push
```

The site will automatically rebuild and redeploy.

## Local Testing Before Deployment

```bash
bundle install
bundle exec jekyll serve
# Visit http://localhost:4000
```
