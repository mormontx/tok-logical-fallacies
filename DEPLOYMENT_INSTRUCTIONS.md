# GitHub Pages Deployment Instructions

## Your files are ready! Here's how to deploy:

### Step 1: Create a New Repository on GitHub

1. Go to: https://github.com/new
2. Repository name: `tok-logical-fallacies` (or any name you prefer)
3. Description: "TOK Teaching Resources - Logical Fallacy Analysis Materials"
4. Set to **Public** (required for free GitHub Pages)
5. **Do NOT** initialize with README, .gitignore, or license
6. Click "Create repository"

### Step 2: Push Your Files

After creating the repository, run these commands in Terminal:

```bash
cd /Users/tj/AG/tok-fallacies-website
git remote add origin https://github.com/mormontx/tok-logical-fallacies.git
git push -u origin main
```

(Replace `tok-logical-fallacies` with whatever repository name you chose)

### Step 3: Enable GitHub Pages

1. Go to your repository settings: https://github.com/mormontx/tok-logical-fallacies/settings/pages
2. Under "Source", select "main" branch
3. Leave the folder as "/ (root)"
4. Click "Save"

### Step 4: Access Your Site

After a few minutes, your site will be live at:
```
https://mormontx.github.io/tok-logical-fallacies/
```

## What's Included

Your website has three pages:

1. **index.html** - Beautiful landing page with links to both resources
2. **student.html** - Student version with all 12 extended texts
3. **teacher.html** - Teacher's annotated guide with highlighted fallacies

## Files Location

All website files are in: `/Users/tj/AG/tok-fallacies-website/`

## Quick Commands Summary

```bash
# Navigate to the folder
cd /Users/tj/AG/tok-fallacies-website

# Set remote (after creating GitHub repo)
git remote add origin https://github.com/mormontx/YOUR-REPO-NAME.git

# Push to GitHub
git push -u origin main
```

## Alternative: Manual Upload

If you prefer not to use command line:

1. Create the repository on GitHub (Step 1 above)
2. Click "uploading an existing file" 
3. Drag and drop these files:
   - index.html
   - student.html
   - teacher.html
4. Commit the files
5. Enable GitHub Pages (Step 3 above)

---

**Need help?** Let me know if you encounter any issues!
