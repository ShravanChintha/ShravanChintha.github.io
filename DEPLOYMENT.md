# GitHub Pages Deployment Instructions

## 🚀 Quick Deployment Steps

### 1. Create GitHub Repository
1. Go to [GitHub.com](https://github.com) and sign in
2. Click "New repository" (green button)
3. **Repository name**: `shravan-chintha.github.io` (replace with your GitHub username)
4. Make it **Public** (required for free GitHub Pages)
5. **Do NOT** initialize with README, .gitignore, or license (we already have these)
6. Click "Create repository"

### 2. Connect Local Repository to GitHub
Copy and run these commands in your terminal:

```bash
cd /Users/shravan-chintha/Documents/ml-exp/profile

# Add your GitHub repository as remote origin
git remote add origin https://github.com/shravan-chintha/shravan-chintha.github.io.git

# Push your code to GitHub
git branch -M main
git push -u origin main
```

### 3. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section (left sidebar)
4. Under **Source**, select "Deploy from a branch"
5. Select **main** branch and **/ (root)** folder
6. Click **Save**

### 4. Access Your Live Website
- Your portfolio will be live at: `https://shravan-chintha.github.io`
- It may take 5-10 minutes for the site to be available after first deployment
- GitHub will show you the URL in the Pages settings

## 🔧 Important Notes

- **Repository Name**: Must be `[your-username].github.io` for user pages
- **Branch**: Use `main` branch for deployment
- **Custom Domain**: You can add a custom domain later in Pages settings
- **Updates**: Any new commits to main branch will automatically update your live site

## 📝 After Deployment

1. Update README.md with your live URL
2. Share your portfolio link: `https://shravan-chintha.github.io`
3. Add the link to your LinkedIn profile and resume

Your professional data science portfolio is ready to showcase your expertise! 🎉
