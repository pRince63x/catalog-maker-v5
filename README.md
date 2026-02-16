# 📱 Catalog Maker PWA

A Progressive Web App for creating professional product catalogs with photos and CHF prices. Works offline, installable on mobile devices.

## ✨ Features

- 📸 **Camera Integration** - Take photos directly or upload from gallery
- 📄 **PDF Import** - Extract all pages from PDF files automatically
- 💰 **Price Management** - Add CHF prices in multiple formats
- 📊 **Flexible Layouts** - Export PDF with 1, 2, 3, or 4 images per A4 page
- 🎨 **Customizable Branding** - Add logo, colors, shop info
- 💾 **Offline Support** - Works without internet after first load
- 📱 **Installable** - Add to home screen on iOS/Android
- 🔄 **Backup/Restore** - Export and import all data

## 🚀 Deploy to GitHub Pages

### Step 1: Create Icons

1. Open `create-icons.html` in your browser
2. It will automatically download `icon-192.png` and `icon-512.png`
3. Place these icon files in the repository root

### Step 2: Upload to GitHub

1. Create a new GitHub repository
2. Upload these files:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `icon-192.png`
   - `icon-512.png`
   - `README.md` (this file)

### Step 3: Enable GitHub Pages

1. Go to repository **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Select branch: `main` (or `master`)
4. Select folder: `/ (root)`
5. Click **Save**

### Step 4: Access Your PWA

Your app will be available at:
```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

## 📱 Install as App

### On iPhone/iPad:
1. Open the site in Safari
2. Tap the Share button
3. Tap "Add to Home Screen"
4. Tap "Add"

### On Android:
1. Open the site in Chrome
2. Tap the menu (⋮)
3. Tap "Install app" or "Add to Home screen"

## 🔧 Usage

### Adding Products
1. Tap the **+** button
2. Take a photo or select from gallery
3. Add product name and price
4. Save

### Import from PDF
1. Tap the **Upload PDF** icon in header
2. Select a PDF file
3. All pages will be imported automatically
4. Click each product to edit name/price

### Export PDF
1. Tap the **PDF** icon in header
2. Choose layout (1, 2, 3, or 4 images per page)
3. Preview your catalog
4. Download or Share

### Shop Settings
1. Go to **Shop Info** tab
2. Upload logo
3. Add shop name, address, WhatsApp
4. Choose colors
5. Save settings

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - No build process needed
- **LocalStorage** - All data stored locally in browser
- **Service Worker** - Enables offline functionality
- **Libraries Used:**
  - jsPDF - PDF generation
  - PDF.js - PDF parsing
  - Material Icons - UI icons
  - Inter Font - Typography

## 📝 File Structure

```
.
├── index.html           # Main application (all-in-one file)
├── manifest.json        # PWA manifest
├── service-worker.js    # Service worker for offline support
├── icon-192.png         # App icon (192x192)
├── icon-512.png         # App icon (512x512)
├── create-icons.html    # Icon generator helper
└── README.md            # This file
```

## 🔒 Privacy

- All data is stored **locally** in your browser
- No data is sent to any server
- No analytics or tracking
- Works 100% offline after first load

## 📄 License

Free to use for personal and commercial projects.

## 🐛 Troubleshooting

**PWA not installing?**
- Make sure you're using HTTPS (GitHub Pages provides this automatically)
- Check that all icons are uploaded correctly
- Try clearing browser cache

**Service Worker not working?**
- Check browser console for errors
- Ensure `service-worker.js` is in root directory
- Hard refresh the page (Ctrl+Shift+R or Cmd+Shift+R)

**PDF import not working?**
- Ensure PDF is not password protected
- Try a smaller PDF file first
- Check browser console for errors

## 💡 Tips

- **Backup regularly** - Use Export Data feature in Settings
- **Name your products** - Click any imported image to add details
- **Test layouts** - Preview PDF before downloading
- **Image quality** - Use good lighting when taking photos
- **Keep it simple** - Focus on clear product photos

## 🤝 Contributing

Found a bug? Want to add a feature? Feel free to open an issue or submit a pull request!

---

Made with ❤️ for small business owners
