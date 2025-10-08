# GitHub Pages Deployment Guide

## Quick Setup

1. **Create a GitHub Repository**
   - Go to GitHub.com and create a new repository
   - Name it something like `greenl8-portfolio` or `portfolio-website`
   - Make it public (required for free GitHub Pages)

2. **Upload Your Files**
   - Upload all files from this project to your repository
   - Or use Git commands:
     ```bash
     git init
     git add .
     git commit -m "Initial portfolio website"
     git branch -M main
     git remote add origin https://github.com/yourusername/your-repo-name.git
     git push -u origin main
     ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click on "Settings" tab
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access Your Website**
   - Your site will be available at: `https://yourusername.github.io/your-repo-name`
   - It may take a few minutes to deploy

## Custom Domain (Optional)

If you want a custom domain like `greenl8.com`:

1. Buy a domain from a registrar
2. In your repository settings, go to Pages section
3. Add your custom domain in the "Custom domain" field
4. Follow GitHub's instructions for DNS configuration

## Updating Your Videos

To add your actual YouTube videos:

1. Open `index.html`
2. Find the iframe elements
3. Replace `dQw4w9WgXcQ` with your actual YouTube video IDs
4. Update the titles to match your videos
5. Commit and push changes

## File Structure

```
your-repo/
├── index.html          # Main website file
├── styles.css          # Styling
├── README.md           # Project description
├── .gitignore          # Git ignore rules
└── DEPLOYMENT.md       # This file
```

## Troubleshooting

- If the site doesn't load, check that all files are in the root directory
- Make sure the repository is public
- Wait a few minutes after enabling Pages
- Check the Actions tab for any deployment errors
