# 🚀 Quick Deploy to GitHub Pages

## Files Included ✅
- ✅ index.html (main app)
- ✅ manifest.json (PWA config)
- ✅ service-worker.js (offline support)
- ✅ icon-192.png (app icon)
- ✅ icon-512.png (app icon)
- ✅ README.md (documentation)
- ✅ .gitignore (git config)

## Deploy Steps

### 1. Create GitHub Repository
```bash
# On GitHub.com:
# - Click "New repository"
# - Name it: catalog-maker (or anything you want)
# - Make it Public
# - Don't add README (we have one)
# - Create repository
```

### 2. Upload Files

**Option A: Drag & Drop (Easiest)**
1. On your new repo page, click "uploading an existing file"
2. Drag ALL files from this folder
3. Commit changes

**Option B: Git Command Line**
```bash
# In this folder, run:
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

### 3. Enable GitHub Pages
1. Go to repo **Settings**
2. Click **Pages** in left sidebar
3. Under **Source**: select **main** branch
4. Click **Save**
5. Wait 1-2 minutes

### 4. Access Your App! 🎉
```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

## Install as App

### iPhone:
Safari → Share → Add to Home Screen

### Android:
Chrome → Menu → Install app

---

## Troubleshooting

**App not installing?**
- Wait 2-3 minutes after enabling GitHub Pages
- Hard refresh: Ctrl+Shift+R (or Cmd+Shift+R on Mac)
- Check icons uploaded correctly

**Service worker errors?**
- Clear browser cache
- Make sure using HTTPS (GitHub Pages auto-provides this)

**PDF import not working?**
- Try smaller PDF first
- Check browser console (F12) for errors

---

## Next Steps

1. Open the app URL
2. Add to home screen
3. Import a PDF or take photos
4. Create your first catalog!

**Need help?** Check README.md for full documentation.
