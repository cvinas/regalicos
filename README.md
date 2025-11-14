# 🎁 regalicos

[![License](https://img.shields.io/badge/License-All_Rights_Reserved-red.svg)](#)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](https://github.com/cvinas/regalicos-app)
[![PWA](https://img.shields.io/badge/PWA-enabled-purple.svg)](https://github.com/cvinas/regalicos-app)

> The ultimate gift management app for Christmas, birthdays, and special occasions. Never forget a present again! 🎉

**[🚀 Live Demo](https://cvinas.github.io/regalicos-app/)** | **[📱 Install as App](#installation)**

![regalicos Screenshot](preview.png)

---

## ✨ Features

### 🎯 Core Functionality
- **👥 Organize by Person or Event** - Manage gifts for friends, family, and coworkers
- **🎄 Multiple Event Types** - Christmas, Birthdays, Kings Day, Saint's Day
- **💡 Gift Ideas Tracker** - Save ideas with links to Amazon, AliExpress, Shein, and more
- **✅ Purchase Tracking** - Mark gifts as bought and assign to specific events
- **🛒 Shopping History** - View all purchased gifts with advanced filters

### 📊 Analytics & Insights
- **💰 Budget Tracking** - Track spent vs pending amounts
- **📈 Statistics Dashboard** - Breakdown by event and person
- **🔍 Smart Filters** - Filter by event, person, or purchase status
- **📋 Multiple View Modes** - List view (collapsed) or expanded view

### 💎 User Experience
- **📱 Mobile-First Design** - Optimized for smartphones
- **🎨 Modern UI** - Glassmorphism effects with smooth animations
- **💾 Auto-Save** - All data stored locally in your browser
- **🔒 Privacy-First** - No servers, no tracking, 100% offline
- **⚡ Lightning Fast** - No loading times, instant responses
- **🌐 PWA Ready** - Install as native app on any device

---

## 🚀 Quick Start

### Option 1: Use Online (Easiest)
1. Visit **[Gift4All Live Demo](https://cvinas.github.io/regalicos-app/)**
2. Start adding people and gift ideas!
3. Optional: Install as app (see below)

### Option 2: Download & Use Locally
```bash
# Clone the repository
git clone https://github.com/cvinas/regalicos-app.git

# Open index.html in your browser
cd regalicos-app
# Double-click index.html or use a local server
```

### Option 3: Install as Mobile App (PWA)

#### 📱 On Android
1. Open the app in **Chrome**
2. Tap the menu (⋮) → **"Add to Home Screen"**
3. Enjoy the native app experience!

#### 🍎 On iOS
1. Open the app in **Safari**
2. Tap the share button → **"Add to Home Screen"**
3. Done!

---

## 📖 How to Use

### 1️⃣ Add a Person
- Tap the **+** floating button
- Enter a name (max 10 chars)
- Select relevant events (Christmas, Birthday, etc.)
- Save!

### 2️⃣ Add Gift Ideas
- Tap **"+ Añadir"** on any person card
- Enter gift description
- Optional: Add a link (Amazon, etc.) and price
- Save!

### 3️⃣ Mark as Purchased
- Tap the **☐** checkbox next to any gift idea
- It turns into **✅** when purchased
- Assign it to a specific event (Christmas, Birthday, etc.)

### 4️⃣ View Your Shopping
- Go to the **🛒 Compras** tab
- See all purchased gifts
- Filter by event or sort by price/person

### 5️⃣ Check Your Budget
- Go to the **📊 Stats** tab
- View total spent and pending
- See breakdown by event and person

---

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styles + Tailwind CSS
- **Vanilla JavaScript** - No frameworks needed
- **LocalStorage API** - Data persistence
- **PWA** - Service Worker ready
- **Tailwind CDN** - Only external dependency

### Why No Framework?
✅ Lightweight (loads instantly)  
✅ No build process needed  
✅ Easy to understand and modify  
✅ Works forever (no breaking updates)  
✅ Perfect for beginners to learn from  

---

## 📂 Project Structure
```
regalicos-app/
├── index.html          # Main app file (single-file architecture)
├── manifest.json       # PWA manifest
├── README.md          # This file
├── LICENSE            # MIT License
└── assets/
    ├── icon-192.png   # App icon (192x192)
    ├── icon-512.png   # App icon (512x512)
    └── preview.png    # Screenshot for README
```

---

## 🎨 Customization

### Change Colors
Edit the Tailwind config in the `<script>` tag:
```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: { /* Your colors */ },
                accent: { /* Your colors */ }
            }
        }
    }
}
```

### Change Events
Modify the `eventos` object in JavaScript:
```javascript
const eventos = {
    navidad: { icon: '🎄', name: 'Navidad' },
    // Add your custom events here
};
```

---

## 🤝 Contributing

This is a private project. If you find bugs or have suggestions, feel free to:
- 🐛 Report bugs via Issues
- 💡 Suggest features
- ⭐ Star the project if you like it!

Note: Pull requests are not currently accepted without prior authorization.
```

### **4. NO subas archivo LICENSE**

- Si GitHub te pide crear un LICENSE file, **sáltalo**
- O crea un archivo `LICENSE` con esto:
```
Copyright (c) 2025 cvinas

All Rights Reserved.

This software and associated documentation files (the "Software") may not be 
used, copied, modified, merged, published, distributed, sublicensed, and/or 
sold without explicit written permission from the copyright holder.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.

---

## 📝 Roadmap

- [ ] Export/Import data (JSON backup)
- [ ] Multi-language support
- [ ] Dark mode
- [ ] Photo attachments for gifts
- [ ] Sharing lists with family
- [ ] Cloud sync (optional)
- [ ] Reminder notifications

---

## 📄 License

© 2025 cvinas. **All Rights Reserved.**

This code is provided for viewing purposes only. No permission is granted to use, copy, modify, or distribute this software without explicit written permission from the author.

---

## 👤 Author

**cvinas**

- GitHub: [@cvinas](https://github.com/cvinas)

---

## 💖 Acknowledgments

- Inspired by the need to never forget a gift again
- Built with ❤️ for friends and family
- Special thanks to the open-source community

---

## 📧 Support

Having issues? Found a bug?
- Open an [Issue](https://github.com/cvinas/regalicos-app/issues)
- Or contact: [Your email if you want]

---

<div align="center">
  
**[⬆ Back to Top](#-gift4all---smart-gift-organizer)**

Made with 🎁 by cvinas | © 2025

</div>
