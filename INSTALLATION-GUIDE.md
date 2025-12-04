# Faith-filled Finance - Installation & Setup Guide

## 🎉 What's New

Your app now has:
- 🔒 **Password Protection** - Secure login screen
- 💾 **Manual Export/Import** - Download backups to your device
- ☁️ **Google Drive Sync Ready** - Framework for cloud backup
- 📱 **PWA (Progressive Web App)** - Install as a native app
- 🔄 **Auto-save** - Data protection every 5 minutes

---

## 📱 INSTALLING ON YOUR PHONE

### Method 1: Install as PWA (Recommended)

#### **iPhone/iPad (Safari):**
1. Open `apex-finance.html` in Safari
2. Create your password on first launch
3. Tap the Share button (square with arrow)
4. Scroll down and tap "Add to Home Screen"
5. Name it "Faith Finance" (or your choice)
6. Tap "Add"
7. App icon appears on your home screen! 🎉

#### **Android (Chrome):**
1. Open `apex-finance.html` in Chrome
2. Create your password on first launch
3. Tap the menu (three dots)
4. Tap "Add to Home screen" or "Install app"
5. Confirm installation
6. App icon appears on your home screen! 🎉

### Method 2: Host Online (For Access Anywhere)

**Option A - GitHub Pages (Free):**
1. Create a GitHub account (github.com)
2. Create a new repository
3. Upload both files:
   - `apex-finance.html`
   - `manifest.json`
4. Enable GitHub Pages in repository settings
5. Access via: `https://yourusername.github.io/repo-name/apex-finance.html`
6. Install as PWA from that URL

**Option B - Netlify/Vercel (Free):**
1. Sign up at netlify.com or vercel.com
2. Drag & drop both files
3. Get your custom URL
4. Install as PWA from that URL

---

## 🔒 PASSWORD SETUP

### First Time:
1. Open the app
2. You'll see "Set up your master password"
3. Create a password (minimum 4 characters)
4. Confirm password
5. Click "Create Password"

### Important Notes:
- ⚠️ **Write down your password!** - If you forget it, you'll lose access
- 🔐 Password is stored securely on your device
- 🔒 No one can access your data without the password
- 💡 Use a strong, memorable password

### Logging In:
- Enter password
- Click "Unlock"
- Wrong password? Try again

### Lock the App:
- Click "🔒 Lock App" button (bottom left)
- Requires password to unlock again

---

## 💾 BACKUP YOUR DATA

### Manual Export (Recommended Weekly):
1. Click "💾 Export Backup" (bottom left)
2. Save the `.json` file to:
   - Your phone's files
   - Cloud storage (Google Drive, Dropbox, iCloud)
   - Email it to yourself
3. Keep multiple backup copies!

### Manual Import (To Restore):
1. Click "📥 Import Backup"
2. Select your backup `.json` file
3. Confirm replacement
4. All data restored! ✓

### What Gets Backed Up:
- ✅ All income records
- ✅ All budgets
- ✅ All transactions
- ✅ All investments
- ✅ All debts/loans
- ✅ All financial goals
- ✅ Gamification progress (XP, level, achievements)
- ✅ Currency preference

---

## ☁️ GOOGLE DRIVE SYNC

### Current Status:
The "Connect Drive" button is ready but requires Google Cloud setup for full functionality.

### For Full Implementation (Advanced):
1. Create a Google Cloud Project
2. Enable Google Drive API
3. Get OAuth credentials
4. Update the app with your credentials

### For Now:
Use **Manual Export/Import** for backups:
- Export weekly to Google Drive manually
- Very secure and reliable
- No internet required

---

## 📱 CHANGING PHONES

### Best Practice (Zero Data Loss):

**Before Getting New Phone:**
1. Open Faith-filled Finance
2. Click "💾 Export Backup"
3. Save backup to:
   - Cloud storage (Google Drive, Dropbox)
   - Email yourself
   - Multiple locations for safety

**On New Phone:**
1. Install app on new phone (see installation steps)
2. Set up password
3. Click "📥 Import Backup"
4. Select your backup file
5. All data restored! 🎉

### Backup Schedule Recommendation:
- 📅 **Weekly**: Export backup every Sunday
- 💰 **After major transactions**: Export after big purchases/income
- 🎯 **Before phone changes**: Always export before switching devices

---

## 💡 TIPS & BEST PRACTICES

### Security:
- 🔒 Lock app when not using it
- 📝 Keep password in safe place
- 🚫 Don't share password
- 💾 Regular backups protect against data loss

### Data Management:
- 📊 Export backup weekly
- ☁️ Store backups in multiple locations
- 🔄 Test restore occasionally (import to check backup works)
- 📱 Before updating phone OS, export backup first

### Offline Use:
- ✅ App works completely offline once installed
- ✅ All data stored on your device
- ✅ No internet required for daily use
- ☁️ Internet only needed for Google Drive sync (future feature)

### Performance:
- 🚀 Fast and responsive
- 💾 Auto-saves every 5 minutes
- 🔋 Battery efficient
- 📊 Handles thousands of transactions

---

## ❓ TROUBLESHOOTING

### "I forgot my password!"
- ⚠️ There's no password recovery
- 💡 Solution: You'll need to reset (loses all data)
- 🔧 To reset: Clear browser data/app storage
- 💾 This is why regular backups are critical!

### "My data disappeared!"
- 📥 Import your latest backup
- 💾 Future backups will prevent this
- ☁️ Consider uploading backups to cloud storage

### "App won't install as PWA"
- 📱 Try different browser (Chrome/Safari)
- 🔄 Refresh the page
- 📲 Follow browser-specific instructions above

### "Backup import not working"
- ✅ Check file is `.json` format
- ✅ Use file from "Export Backup" button
- ✅ File should contain `"version": "1.0"`

### "Lost phone with all data!"
- 😊 If you have backup: Install on new phone, import backup
- 😢 If no backup: Data cannot be recovered
- 💾 Start fresh, then set up weekly backups!

---

## 🎮 GAMIFICATION FEATURES

### Level Up System:
- Earn XP for every action
- Level up every 100 XP
- Track progress in top bar

### Achievements:
- 12 achievements to unlock
- Special rewards for consistency
- View all in Achievements page

### Daily Streaks:
- Log activity daily
- Maintain streak for bonuses
- See streak counter at top

---

## 📖 SCRIPTURE FEATURES

- Random Bible verses about finance
- Appears after transactions (30% chance)
- 15 carefully selected scriptures
- Encouragement and wisdom
- Auto-dismisses after 15 seconds

---

## 🆘 SUPPORT

### Files Needed:
1. `apex-finance.html` - Main app file
2. `manifest.json` - PWA configuration

### Keep Both Files Together:
- Same folder/directory
- Upload both if hosting online
- Required for PWA installation

---

## ✅ QUICK START CHECKLIST

- [ ] Open app in browser
- [ ] Create master password (WRITE IT DOWN!)
- [ ] Add to home screen / Install as app
- [ ] Add first transaction
- [ ] Export first backup
- [ ] Save backup to cloud storage
- [ ] Set weekly backup reminder
- [ ] Enjoy managing your finances with faith! 🙏

---

## 🌟 RECOMMENDED WORKFLOW

**Daily:**
- Open app (enter password)
- Log transactions
- Check budget progress
- Lock app when done

**Weekly:**
- Review spending
- Export backup
- Upload to cloud storage
- Check financial goals

**Monthly:**
- Set new budgets
- Review investments
- Update debt payments
- Celebrate achievements!

---

## 📊 DATA PRIVACY

- 🔒 All data stored locally on YOUR device
- 🚫 No external servers
- 🔐 Password protected
- 👤 Completely private
- ✋ You control all backups
- 💾 Export/import at any time

---

## 🙏 BIBLICAL STEWARDSHIP

Remember the words of Proverbs 21:5:
*"The plans of the diligent lead surely to abundance, but everyone who is hasty comes only to poverty."*

This app helps you be a faithful steward of God's blessings! 

---

**Enjoy managing your finances with faith and wisdom! ⛪💰**
