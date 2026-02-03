# Card Snap - iPhone Installation Guide

## Overview
Card Snap is a web app that lets you take 10 photos of your trading card and combine them into a single image. It guides you through each shot:
- Front + 4 corners
- Back + 4 corners

## Installation Steps (Free, ~10 minutes)

### Step 1: Create a Free GitHub Account (skip if you have one)
1. Go to https://github.com
2. Click "Sign up" and create a free account

### Step 2: Create a New Repository
1. Log into GitHub
2. Click the **+** icon in the top right → "New repository"
3. Name it: `card-snap` (or anything you like)
4. Make sure "Public" is selected
5. Click "Create repository"

### Step 3: Upload the App Files
1. On your new repository page, click "uploading an existing file"
2. Drag and drop ALL 5 files from the `card-snap-pwa` folder:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Click "Commit changes"

### Step 4: Enable GitHub Pages (Free Hosting)
1. Go to your repository's **Settings** tab
2. Scroll down to **Pages** in the left sidebar
3. Under "Source", select **Deploy from a branch**
4. Under "Branch", select **main** and **/ (root)**
5. Click **Save**
6. Wait 1-2 minutes for deployment

### Step 5: Get Your App URL
1. Go back to **Settings → Pages**
2. You'll see: "Your site is live at https://YOUR-USERNAME.github.io/card-snap/"
3. Copy this URL

### Step 6: Install on Your iPhone
1. Open **Safari** on your iPhone (must be Safari, not Chrome)
2. Go to your app URL from Step 5
3. Tap the **Share** button (square with arrow)
4. Scroll down and tap **"Add to Home Screen"**
5. Name it "Card Snap" and tap **Add**

### Done! 🎉
You now have a Card Snap icon on your home screen. Tap it to launch the app!

---

## Using the App

1. **Tap "Start Capturing"** to begin
2. **Allow camera access** when prompted
3. **Follow the prompts** - the app tells you exactly which shot to take:
   - Front (full card)
   - Front Top Left corner
   - Front Top Right corner
   - Front Bottom Left corner
   - Front Bottom Right corner
   - Back (full card)
   - Back Top Left corner
   - Back Top Right corner
   - Back Bottom Left corner
   - Back Bottom Right corner
4. **Tap the white button** to capture each photo
5. **Tap "Skip"** if you want to skip a shot temporarily
6. **Tap any photo** to retake it
7. When all 10 are done, tap **"Combine All Photos"**
8. **Long-press the result** to save to your Photos app

---

## Troubleshooting

**Camera not working?**
- Make sure you're using Safari (not Chrome)
- Check Settings → Safari → Camera → Allow
- Make sure you're accessing via HTTPS (GitHub Pages provides this)

**App not installing to home screen?**
- You must use Safari browser
- Make sure to tap "Add to Home Screen" not just bookmark

**Photos not saving?**
- Long-press the combined image and select "Save to Photos"
- Or screenshot the result

---

## Updating the App
If you want to make changes:
1. Edit the files on GitHub
2. Changes go live automatically in 1-2 minutes
3. On iPhone, close and reopen the app to get updates
