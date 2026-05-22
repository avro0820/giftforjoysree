# Happy Birthday Gift for Joysree

A beautiful, customizable single-file birthday webpage with animations and interactive elements.

## Features ✨

- 🎉 5-step interactive birthday experience
- 💖 Animated heart background (Three.js)
- 📸 Photo gallery with slideshow mode
- ✍️ Fully editable in-browser editor
- 🎊 Confetti animations
- 📱 Responsive design
- 🎨 Beautiful gradient UI with glassmorphism

## Quick Start

### Local Preview

1. **Using Python:**
   ```bash
   python -m http.server 8000
   # Open http://localhost:8000 in your browser
   ```

2. **Using VS Code:**
   - Install the "Live Server" extension
   - Right-click `index.html` → "Open with Live Server"

### Customize

1. Open the page in your browser
2. Click the **✏️ Edit** button (top right)
3. Update:
   - Greeting message
   - Birthday heading and message
   - Final wish
   - Upload your favorite photos
   - Add romantic quotes (one per line)
4. Click **Apply & Save** (changes saved locally)
5. Click **Download HTML** to get the customized file

### Deploy to GitHub Pages

1. Create a new GitHub repository named `giftforjoysree`
2. Upload `index.html` to the repository root:
   - Option A: Drag-and-drop via GitHub web interface
   - Option B: Use Git CLI
   ```bash
   git clone https://github.com/YOUR_USERNAME/giftforjoysree
   cd giftforjoysree
   cp /path/to/index.html .
   git add index.html
   git commit -m "Add birthday gift page"
   git push
   ```
3. Go to **Settings → Pages** → Enable GitHub Pages (main branch)
4. Your site will be live at: `https://YOUR_USERNAME.github.io/giftforjoysree`

## File Structure

```
giftforjoysree/
├── index.html           ← Main file (only one you need!)
├── README.md            ← This file
└── IMG-20251029-WA0123.jpg  ← Sample photo (optional)
```

## Customization Guide

### Photos
- Click "Edit" → Upload multiple images
- Use "Grid" or "Slideshow" display mode
- Photos are stored locally in your browser

### Quotes
- Add romantic lines one per line in the editor
- They'll rotate on the first page

### Text
- All text fields are editable via the Edit panel
- Changes appear instantly

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Page doesn't load | Ensure `index.html` is at repository root (not in subfolder) |
| Photos not showing | Browsers must upload photos locally; default image provided |
| Scripts fail to load | Check internet connection; CDN libraries may be temporarily unavailable |
| Edits disappear | Use "Download HTML" to save a permanent copy |
| GitHub Pages not working | Check **Settings → Pages** → Ensure "Source" is set to "main" branch |

## Browser Support

- ✅ Chrome/Brave (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ IE11 (not supported)

## Libraries Used

- **Tailwind CSS** - Styling
- **Three.js** - 3D animated hearts
- **GSAP** - Smooth animations
- **Canvas Confetti** - Celebration effects

All loaded from CDN, so no build step needed!

## Tips

1. **Backup your work**: Use "Download HTML" regularly
2. **Mobile friendly**: Works great on phones and tablets
3. **No dependencies**: Single HTML file, no npm/build tools needed
4. **Shareable**: Send the GitHub Pages URL to anyone
5. **Reusable**: Edit the HTML to customize for different people

## License

Free to use and modify for personal projects.

---

**Made with ❤️ for special people in your life**
