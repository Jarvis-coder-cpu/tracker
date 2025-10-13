# 🔥 Fire Loss Inventory Tracker

A Progressive Web App (PWA) for tracking personal property lost in a fire for insurance claims. Optimized for Samsung phones and all mobile devices.

## ✨ Features

- 🎤 **Voice Recording** - Speak naturally to add items
- 📱 **Standalone App** - Install on your home screen
- 💾 **Offline Support** - Works without internet connection
- 📊 **Export to CSV** - Generate reports for insurance claims
- 🔄 **Auto-Save** - Never lose your data with localStorage
- 🏷️ **Smart Parsing** - Automatically extracts room, brand, model, cost, etc.

## 📱 Installation on Samsung Phone

### Method 1: Install as PWA (Recommended)

1. **Open the app** in Samsung Internet or Chrome browser
2. **Tap the menu** button (⋮) in the top right
3. **Select "Add to Home screen"** or "Install app"
4. **Tap "Install"** or "Add"
5. **Done!** The app icon will appear on your home screen

### Method 2: Add to Home Screen via Banner

1. **Open the app** in your browser
2. **Look for the blue install banner** at the top
3. **Tap "Install"**
4. **Done!** The app will be added to your home screen

## 🎤 Enabling Microphone Access

### If microphone permission is denied:

#### Samsung Internet / Chrome on Android:

1. **Tap the lock icon** 🔒 in the address bar
2. **Tap "Permissions"** or "Site settings"
3. **Find "Microphone"**
4. **Select "Allow"**
5. **Reload the page**

#### Alternative Method:

1. Open **Settings** app
2. Go to **Apps** → **Chrome** (or your browser)
3. Tap **Permissions**
4. Find **Microphone**
5. Select **Allow**

### Important: HTTPS Requirement

- Microphone access **requires HTTPS** for security
- If you see a security warning, either:
  - Access the app via HTTPS URL
  - Install as PWA (bypasses HTTP requirement)
  - Use localhost for testing

## 📝 How to Use

### Recording Items:

1. **Tap the red microphone button** 🎤
2. **Allow microphone access** when prompted
3. **Speak naturally** about each item, for example:
   - "Samsung 55-inch TV in the living room, bought from Best Buy in 2020 for $800"
   - "Nike sneakers, two pairs, about 6 months old"
   - "Sony PlayStation 5 in the bedroom"
4. **Tap the stop button** ⏹️ when done
5. **Review the parsed information** and edit if needed

### What You Can Say:

- **Room**: "in the living room", "bedroom", "kitchen", etc.
- **Brand**: Samsung, Sony, LG, Apple, Nike, etc.
- **Cost**: "$500", "$1,200"
- **Age**: "2 years old", "6 months old", "bought in 2019"
- **Quantity**: "two pairs", "three items", "5 plates"
- **Store**: "from Best Buy", "bought at Walmart", etc.

### Managing Items:

- **Edit**: Tap on any item to view details (editing coming soon)
- **Delete**: Tap the 🗑️ trash icon
- **Duplicate Detection**: App will ask if similar items should be merged

### Exporting Data:

1. **Fill in claim information** at the top:
   - Claim Number
   - Your Name
   - Phone Number
2. **Add all your items** using voice recording
3. **Tap "Export CSV"** 📥 to download
4. **Send the CSV file** to your insurance adjuster

### Getting Prices:

1. **Tap "Get Prices"** 💰
2. **The pricing request is copied** to your clipboard
3. **Paste it** in your preferred AI assistant (Claude, ChatGPT, etc.)
4. **Get current replacement prices** for all items

## 🔧 Technical Details

### Technologies Used:

- React 18 (via CDN)
- TailwindCSS for styling
- Web Speech API for voice recognition
- Service Worker for PWA functionality
- LocalStorage for data persistence

### Browser Compatibility:

- ✅ Chrome on Android
- ✅ Samsung Internet
- ✅ Safari on iOS 14.5+
- ❌ Firefox (no Web Speech API support)

### Data Storage:

- All data is stored **locally** on your device
- No data is sent to any server
- Data persists between sessions
- Clear browser data will erase saved items

## 🐛 Troubleshooting

### Microphone Not Working:

1. **Check browser compatibility** (use Chrome on Android or Safari on iOS)
2. **Verify HTTPS** or install as PWA
3. **Check permissions** in browser settings
4. **Reload the page** after granting permission
5. **Try in Incognito/Private mode** to test without extensions

### App Not Installing:

1. **Use a supported browser** (Chrome, Samsung Internet, Safari)
2. **Access via HTTPS** if available
3. **Clear browser cache** and try again
4. **Update your browser** to the latest version

### Voice Recognition Issues:

- **Speak clearly** and at normal volume
- **Reduce background noise**
- **Check microphone** works in other apps
- **Try speaking slower** for better accuracy
- **Use specific terms** (brands, models, etc.)

### Data Not Saving:

1. **Don't use incognito/private mode**
2. **Check storage permissions**
3. **Clear enough space** on your device
4. **Don't clear browser data** without exporting first

## 📄 Privacy & Security

- **No data collection** - everything stays on your device
- **No analytics or tracking**
- **No server communication** except for loading the app
- **Microphone access** only when recording
- **Open source** - review the code yourself

## 🚀 Deployment

To deploy this app:

1. **Upload files** to a web server
2. **Ensure HTTPS** is enabled (required for microphone)
3. **Files needed**:
   - `Djfireapp.html` (main app)
   - `manifest.json` (PWA config)
   - `sw.js` (service worker)

### Testing Locally:

```bash
# Using Python
python3 -m http.server 8080

# Using Node.js
npx http-server -p 8080
```

Then visit: `http://localhost:8080/Djfireapp.html`

## 📞 Support

For issues or questions:
- Check the troubleshooting section above
- Review browser console for errors (F12 or DevTools)
- Ensure you're using a compatible browser on HTTPS

## 📜 License

See LICENSE file for details.

---

**Made for Samsung phones and all mobile devices** 📱🔥
