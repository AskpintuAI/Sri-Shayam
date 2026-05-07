# 🚀 श्री श्याम रेस्टोरेंट — GitHub Deployment Guide

---

## 📁 इन Files को GitHub पर Upload करना है

```
index.html      ← मुख्य वेबसाइट (customer देखेगा)
admin.html      ← Admin panel (menu update करने के लिए)
manifest.json   ← App जैसा दिखने के लिए
sw.js           ← Offline support के लिए
icon.png        ← App icon (अपना logo यहाँ रखें)
qr.png          ← UPI QR Code image
```

---

## ✅ Step-by-Step: GitHub पर Live करें

### Step 1 — GitHub Account
👉 https://github.com पर जाएं
अगर account नहीं है तो बनाएं (Free है)

### Step 2 — New Repository बनाएं
1. Login करके **"New"** button दबाएं
2. Repository name: `shyam-restaurant` (या कोई भी नाम)
3. **Public** select करें
4. **"Create repository"** दबाएं

### Step 3 — Files Upload करें
1. **"uploading an existing file"** पर click करें
2. ऊपर बताई सभी files एक साथ drag & drop करें
3. **"Commit changes"** दबाएं

### Step 4 — GitHub Pages ON करें
1. Repository में **Settings** tab खोलें
2. Left sidebar में **"Pages"** पर click करें
3. **Source** में `Deploy from a branch` select करें
4. Branch: **main** → Folder: **/ (root)**
5. **Save** दबाएं

### Step 5 — लिंक मिलेगा!
```
https://[आपका-username].github.io/shyam-restaurant/
```
यही link Customer को share करें! 🎉

---

## 📲 Customer को QR Code कैसे दें?

Website live होने के बाद:
1. https://qr.io या https://www.qrcode-monkey.com खोलें
2. अपनी website का link paste करें
3. QR download करें — print करवाएं!

---

## 🍽️ Daily Menu Update कैसे करें?

1. Website का link खोलें
2. Link के अंत में `/admin.html` लिखें
   ```
   https://[username].github.io/shyam-restaurant/admin.html
   ```
3. Password डालें: **shyam1234**
4. आज का मेन्यू update करें → **"सेव करें"** दबाएं
5. बस! Customer को तुरंत नया मेन्यू दिखेगा

---

## 🔐 Admin Password बदलना है?

`admin.html` फ़ाइल खोलें, यह line ढूंढें:
```
const ADMIN_PWD = 'shyam1234';
```
यहाँ `shyam1234` की जगह अपना नया password लिखें।

---

## ❓ कोई परेशानी हो तो?
📞 AskPintuAI से संपर्क करें
🌐 https://askpintuai.github.io
