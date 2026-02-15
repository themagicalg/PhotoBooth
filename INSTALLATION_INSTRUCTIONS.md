# 📸 Photobooth - iOS PWA Installation Guide

## What You're Getting
Your photobooth is now a **Progressive Web App (PWA)** that can be installed on iOS devices like a native app!

## ✅ Features That Work on iOS:
- ✨ Camera access (both front and back)
- ✨ Photo filters and wallpapers
- ✨ Email sharing (opens Mail app)
- ✨ Works offline once installed
- ✨ Full-screen app experience
- ✨ App icon on home screen

## ⚠️ Limitations:
- Text/SMS feature is simulated (no real SMS sending on PWA)
- To get real SMS, we'd need to go the native app route

## 📱 How to Install on iPhone/iPad:

### Step 1: Host Your Files
You need to put these files on a web server (they won't work from local files):

**Option A - Quick Test (Use GitHub Pages - FREE)**
1. Go to github.com and create a free account
2. Create a new repository called "photobooth"
3. Upload these files:
   - photobooth.html
   - manifest.json
   - service-worker.js
   - icon-192.svg
   - icon-512.svg
4. Go to Settings > Pages > Enable GitHub Pages
5. You'll get a URL like: `https://yourusername.github.io/photobooth/photobooth.html`

**Option B - Use Any Web Hosting**
- Upload all files to any web hosting service
- Just need HTTPS (required for PWA)

### Step 2: Install on Your iPhone
1. Open **Safari** on your iPhone (must use Safari, not Chrome!)
2. Go to your hosted URL
3. Tap the **Share button** (square with arrow pointing up)
4. Scroll down and tap **"Add to Home Screen"**
5. Name it "Photobooth" and tap **Add**
6. Done! 🎉 You'll see the app icon on your home screen

### Step 3: Use It Like a Native App
1. Tap the Photobooth icon
2. Grant camera permission when asked
3. Take photos with filters and wallpapers!
4. Share via email (opens Mail app)

## 🔧 Troubleshooting:

**Camera not working?**
- Make sure you granted permission in Safari settings
- Go to Settings > Safari > Camera > Allow

**Can't install?**
- Must use Safari browser (not Chrome)
- URL must be HTTPS (not HTTP)
- Make sure all files are uploaded to the server

**Want real SMS sending?**
- Let me know and we can convert to a native iOS app
- Requires Xcode, Mac, and Apple Developer account ($99/year)

## 📂 Files Included:
- `photobooth.html` - Main app file
- `manifest.json` - PWA configuration
- `service-worker.js` - Enables offline mode
- `icon-192.svg` - App icon (small)
- `icon-512.svg` - App icon (large)

## 🚀 Next Steps:

**If this works for you:**
- Enjoy your photobooth app!
- Customize colors, filters, or features as needed

**If you need real SMS:**
- We can convert to a native iOS app using Capacitor
- This adds real SMS capability
- Requires more setup but gives full iOS integration

Let me know how it goes! 📸
