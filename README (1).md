# ☕ Vansh Pratap Singh Cafe — Premium Restaurant Website

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![No Framework](https://img.shields.io/badge/No_Framework-Pure_Vanilla-gold?style=for-the-badge)
![WhatsApp](https://img.shields.io/badge/WhatsApp_Orders-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

> *"This restaurant provides the best taste and premium service in town."*

**A fully responsive, single-file luxury restaurant website with live ordering via WhatsApp — built with pure HTML, CSS & JavaScript. No libraries. No frameworks. Zero dependencies.**

</div>

---

## 🌟 What Makes This Project Unique

This isn't just a restaurant website — it's a **complete digital dining experience** packed into a single HTML file:

- 🎠 **12-slide Auto Hero Slider** — swaps every 2 seconds with smooth Ken Burns zoom effect, progress bar, dot navigation & slide labels
- 💨 **Full Hookah Lounge Section** — a dedicated premium sub-page with animated smoke particles, floating glow rings & hookah pipe SVG animation
- 📱 **WhatsApp Direct Ordering** — clicking "Order Now" opens WhatsApp with a pre-filled message including item name, quantity & total price. No backend needed!
- 🛒 **Live Cart System** — add multiple items, manage quantities, view cart summary & checkout — all in memory, no database
- ✨ **Pure CSS Animations** — 15+ custom keyframe animations including smoke rising, neon pulse, diamond spin, stat counter, toast notifications
- 🏆 **Premium Black + Gold Aesthetic** — dark luxury theme with CSS variables, radial gradients, grid texture overlay, gold glows & glassmorphism effects
- 📊 **Animated Stats Counter** — triggered by IntersectionObserver when the stats bar scrolls into view
- 🎯 **Zero External JS Dependencies** — only Google Fonts CDN used; everything else is vanilla

---

## 🚀 Live Features

| Feature | Details |
|---|---|
| 🍔 Food Menu | 12 items across 3 categories — Fast Food, Desi Specials, Main Course |
| 💨 Hookah Menu | 12 premium flavours with strength, session time & coal type info |
| 🛒 Cart | Add, update quantity, remove, view total, checkout |
| 📲 WhatsApp Orders | Auto-formatted message sent directly to cafe's WhatsApp |
| ❤️ Wishlist | Like/unlike any food card |
| 🎠 Hero Slider | 12 slides, 2s auto-swap, manual arrows, dot nav, progress bar |
| 📊 Stats | Animated counters: 5000+ customers, 80 menu items, 4.9⭐, 10 years |
| 🔔 Toast Notification | Appears on every successful add/order action |
| 📱 Responsive | Works on mobile, tablet & desktop |
| 🌙 Dark Luxury Theme | Deep black + gold premium UI |

---

## 📁 Project Structure

```
vansh-cafe/
│
├── index.html        ← Entire project (HTML + CSS + JS — single file)
└── README.md         ← This file
```

> 💡 **Yes, the entire website is ONE file.** No build tools, no npm install, no config files. Just open `index.html` in a browser and it works.

---

## 🛠️ Tech Stack

```
Language    → HTML5, CSS3, Vanilla JavaScript (ES6+)
Fonts       → Google Fonts: Cinzel Decorative, Playfair Display, Rajdhani
Images      → Unsplash CDN (with onerror fallback)
Ordering    → WhatsApp Web API (wa.me deep link)
Animation   → Pure CSS @keyframes (15+ custom animations)
Layout      → CSS Grid + Flexbox
State       → JavaScript in-memory (cart array)
```

---

## ⚙️ How to Run

**Option 1 — Local (Instant)**
```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/vansh-cafe.git

# Just open the file — no server needed
open index.html
```

**Option 2 — GitHub Pages (Free Hosting)**
1. Go to repo → Settings → Pages
2. Source: `main` branch → `/root`
3. Your site will be live at `https://YOUR_USERNAME.github.io/vansh-cafe/`

**Option 3 — VS Code Live Server**
```
Install "Live Server" extension → Right click index.html → Open with Live Server
```

---

## 📲 WhatsApp Order Flow

When a customer clicks **"Order Now"** or **"Book Now"**:

```
Customer clicks button
       ↓
Popup opens with item details + quantity selector
       ↓
Customer clicks "Confirm Order"
       ↓
WhatsApp opens (new tab) with pre-filled message:
  "New Direct Food Order! 🍽️
   Order ID: #VPS12345
   Item: Classic Smash Burger
   Quantity: 2
   Total Price: ₹498
   Please deliver this ASAP!"
       ↓
Cafe owner receives message on: +91 8381975388
```

No payment gateway. No database. No server. Just instant WhatsApp connection.

---

## 🎨 Design System

```css
/* Color Palette */
--bg:       #06080f   /* Deep black background */
--gold:     #FFD700   /* Primary gold accent */
--gold2:    #f59e0b   /* Warm gold variant */
--violet:   #7c3aed   /* Hookah section accent */
--vl:       #a855f7   /* Light violet */
--card:     #0d1117   /* Card background */
--text:     #e2e8f0   /* Primary text */
--dim:      #94a3b8   /* Muted text */
--green:    #10b981   /* "Open Now" indicator */
```

**Font Pairing:**
- Display: `Cinzel Decorative` — logo, hero headings (ultra premium feel)
- Serif: `Playfair Display` — section titles, prices, card names
- Sans: `Rajdhani` — body text, buttons, labels

---

## 📸 Screenshots

> Hero Slider → Menu Grid → Hookah Lounge → Order Popup → Footer

*(Add your own screenshots here after deployment)*

---

## 🧠 How This Was Built

This project was built using **Vibe Coding** — describing what I wanted in natural language and iterating fast. The entire website was:

- Designed & coded in one session
- No frameworks, no boilerplate, no templates used
- Every animation, gradient & layout written from scratch
- WhatsApp ordering logic added without any backend

**Vibe Coding Workflow:**
```
Idea → Describe the feature → Generate → Test in browser → Iterate → Done
```

---

## 🔮 Possible Future Upgrades

- [ ] Admin panel to manage menu items
- [ ] Firebase/Supabase for real-time orders
- [ ] Razorpay/UPI payment integration
- [ ] Table reservation form with email confirmation
- [ ] PWA support (offline mode + installable)
- [ ] Customer review submission

---

## 👤 About

**Vansh Pratap Singh Cafe**
📍 Near City Mall, Ghaziabad, Uttar Pradesh — 201001
📞 8381975388
🌐 www.vanshcafe.in

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

Made with ❤️ in **Ghaziabad, UP** &nbsp;·&nbsp; Built with **Vibe Coding**

⭐ **Star this repo if you liked the project!**

</div>
