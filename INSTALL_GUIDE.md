# 📱 Installation Guide for Samsung Phone

## Quick Start - 3 Easy Steps

### Step 1: Open the App
1. Open **Chrome** or **Samsung Internet** on your phone
2. Navigate to the app URL (where `Djfireapp.html` is hosted)
3. You should see the Fire Loss Inventory app

### Step 2: Install as App
**You'll see a blue banner at the top:**
```
📱 Install App
Install for better performance and offline access
[Install] [✕]
```

**Tap "Install"** and the app will be added to your home screen!

**Alternative method:**
- Tap the **menu button (⋮)** in the top-right corner
- Select **"Add to Home screen"**
- Tap **"Add"** or **"Install"**

### Step 3: Enable Microphone
When you first try to record:
1. A browser popup will ask: **"Allow microphone access?"**
2. Tap **"Allow"** or **"While using the app"**
3. You're ready to start recording!

---

## 🔧 Troubleshooting: Microphone Access

### If you accidentally denied microphone permission:

#### Method 1: Via Address Bar (Easiest)
1. **Tap the lock icon 🔒** in the address bar
2. **Tap "Permissions"** or "Site settings"
3. Find **"Microphone"**
4. Change to **"Allow"**
5. **Reload the page** (pull down to refresh)

#### Method 2: Via Browser Settings
1. Open browser **Settings**
2. Go to **"Site settings"** or **"Privacy and security"**
3. Tap **"Microphone"**
4. Find your site in the list
5. Change to **"Allow"**
6. Go back to the app and reload

#### Method 3: Via Phone Settings
1. Open **Settings** app on your phone
2. Go to **Apps** → **Chrome** (or Samsung Internet)
3. Tap **Permissions**
4. Find **Microphone**
5. Select **"Allow"**
6. Return to the app and reload

---

## 💡 Using the App

### Recording Your Items

**What to say:**
- "Samsung 55-inch TV in the living room, bought from Best Buy in 2020 for $800"
- "Nike Air Max sneakers, two pairs, about 6 months old"
- "Sony PlayStation 5 console in the bedroom, bought for $500"

**The app automatically extracts:**
- Room location (living room, bedroom, etc.)
- Brand (Samsung, Sony, Nike, etc.)
- Model numbers
- Purchase price
- Age or purchase date
- Quantity
- Store name

### Adding Multiple Items
1. **Record one item** at a time
2. **Tap stop** when done describing it
3. **Review** the parsed information
4. **Tap the microphone again** for the next item

### Editing Items
- Tap any item in the list to view details
- Use the 🗑️ trash icon to delete items

### Exporting Your Inventory
1. Fill in your **claim information** at the top:
   - Claim Number
   - Your Name
   - Phone Number
2. **Add all your items**
3. Tap **"Export CSV" 📥**
4. **Share the file** with your insurance adjuster

---

## 🌐 HTTPS & Security

### Why HTTPS is Important
For security reasons, browsers **require HTTPS** for microphone access.

### Solutions:

**If you see a yellow warning banner:**

**Option 1: Install as PWA** (Recommended)
- Installing the app bypasses the HTTPS requirement
- The app works fully offline after installation
- Best user experience

**Option 2: Access via HTTPS**
- Ask your administrator to enable HTTPS
- Use a service like GitHub Pages, Netlify, or Vercel

**Option 3: Use localhost (Testing only)**
- If running locally, use `http://localhost:8080/Djfireapp.html`
- Localhost is exempt from HTTPS requirement

---

## 🎯 App Features

### ✅ Works Offline
Once installed, the app works without internet connection!

### ✅ Auto-Save
All data is automatically saved to your phone. Never lose your progress!

### ✅ Voice Recognition
Speak naturally - the app understands context and extracts details automatically.

### ✅ Smart Duplicate Detection
If you record similar items, the app asks if you want to merge them.

### ✅ Export to CSV
Generate professional reports for your insurance company.

### ✅ Price Lookup Helper
Generate a formatted request to get current replacement prices via AI assistants.

---

## 📱 App Behavior on Samsung Phone

After installation, the app will:
- **Open in full screen** (no browser bars)
- **Have its own icon** on your home screen
- **Work offline** completely
- **Save data** between sessions
- **Request microphone** permission like a native app

---

## ❓ Common Questions

### Q: Will my data be sent to a server?
**A:** No! All data stays on your phone. Nothing is uploaded anywhere.

### Q: What happens if I clear my browser data?
**A:** You'll lose your saved items. Always export to CSV before clearing data!

### Q: Can I use this on multiple devices?
**A:** Each device stores data independently. Export and import CSV files to transfer data.

### Q: Does this work on iPhone?
**A:** Yes! Use Safari on iOS 14.5 or newer. Same installation process.

### Q: Can I use this in Firefox?
**A:** Unfortunately no - Firefox doesn't support the Web Speech API needed for voice recognition.

### Q: What if I don't have HTTPS?
**A:** Install the app as a PWA - it will work even without HTTPS after installation.

---

## 🆘 Still Having Issues?

### Check These:
- [ ] Using Chrome or Samsung Internet (not Firefox)
- [ ] Microphone permission is "Allow" (not "Ask" or "Deny")
- [ ] Speaking clearly and loudly enough
- [ ] No other app is using the microphone
- [ ] Browser is up to date
- [ ] Sufficient phone storage space

### Test Your Microphone:
Try another app that uses the microphone (like voice recorder) to ensure your phone's microphone works properly.

### Reset and Try Again:
1. Close the app completely
2. Clear browser cache for this site
3. Reinstall the app
4. Grant permissions when asked

---

**Need more help?** Check the main README.md file for detailed troubleshooting steps!
