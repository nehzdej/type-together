# 🚀 GitHub Deployment Guide for TypeTogether

This guide will walk you through uploading TypeTogether to GitHub and making it publicly accessible.

## 📋 Prerequisites

- A GitHub account ([Sign up here](https://github.com/join))
- Git installed on your computer ([Download here](https://git-scm.com/downloads))

## 🎯 Step-by-Step Instructions

### 1. Create a New Repository on GitHub

1. Go to [github.com](https://github.com) and log in
2. Click the **"+"** button in the top right corner
3. Select **"New repository"**
4. Fill in the details:
   - **Repository name**: `typetogether` (or any name you prefer)
   - **Description**: "A communal digital typewriter for collaborative writing"
   - **Visibility**: Choose **Public**
   - **DO NOT** initialize with README (we already have one)
5. Click **"Create repository"**

### 2. Upload Files to GitHub

You have two options:

#### Option A: Using Git (Command Line) - Recommended

Open your terminal/command prompt and run these commands:

```bash
# Navigate to the folder containing your TypeTogether files
cd path/to/typetogether

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: TypeTogether communal typewriter"

# Add your GitHub repository as remote (replace YOUR_USERNAME and YOUR_REPO)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git

# Push to GitHub
git branch -M main
git push -u origin main
```

#### Option B: Using GitHub Website (Easier for Beginners)

1. On your new repository page, click **"uploading an existing file"**
2. Drag and drop these files:
   - `index.html`
   - `README.md`
   - `LICENSE`
   - `CONTRIBUTING.md`
   - `.gitignore`
3. Scroll down and click **"Commit changes"**

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** tab
3. Scroll down to **"Pages"** in the left sidebar
4. Under **"Source"**, select **"main"** branch
5. Click **"Save"**
6. Wait 1-2 minutes for deployment
7. Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO/`

### 4. Update README with Live Link

1. Edit `README.md` on GitHub
2. Find the line that says `**[Try TypeTogether Live](#)**`
3. Replace `#` with your GitHub Pages URL
4. Save changes

## 🎉 You're Done!

Your TypeTogether is now live and public! Share your link with friends and watch the collaborative magic happen.

## 🔄 Making Updates

Whenever you want to update your site:

```bash
# Make your changes to the files
# Then:
git add .
git commit -m "Description of changes"
git push
```

Changes will appear on your GitHub Pages site within a few minutes.

## ⚠️ Important Notes

### About Storage
The current implementation uses browser storage which is:
- ✅ Great for demos and personal use
- ✅ Works immediately without backend setup
- ⚠️ Limited to visitors using the same browser
- ⚠️ Not truly "real-time" across different users

### For True Multi-User Collaboration
To make it fully collaborative across different users/browsers, you'll need:
- A backend server (Node.js, Python, etc.)
- WebSocket connections for real-time sync
- Database (MongoDB, PostgreSQL, etc.)

Popular options:
- **Firebase** (easiest for beginners)
- **Supabase** (open-source Firebase alternative)
- **Socket.io** with custom backend

## 🆘 Troubleshooting

**Site not showing up?**
- Wait 2-3 minutes after enabling GitHub Pages
- Check that `index.html` is in the root directory
- Verify the branch is set to `main` in Settings → Pages

**Storage not working?**
- The current version uses browser storage, so each visitor needs to be using Claude.ai artifacts or a similar environment
- For production, consider implementing a backend (see notes above)

## 📚 Resources

- [GitHub Pages Documentation](https://docs.github.com/pages)
- [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
- [Markdown Guide](https://www.markdownguide.org/)

## 💬 Need Help?

Open an issue on the repository or check existing issues for solutions!

---

Happy typing! ⌨️✨
