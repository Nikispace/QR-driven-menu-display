
# QR-Driven Digital Menu Card - Indian Kitchen 

A sleek, responsive, single-page digital menu application tailored for restaurants, specifically showcasing authentic Tamil Nadu cuisine. Designed for mobile-first user experiences, this application acts as a cost-effective, high-performance solution for contactless dining via QR code scanning.

---

## 📄 Description

**Indian Kitchen** is a high-performance, mobile-responsive web application designed to serve as a digital menu card accessed seamlessly via QR codes at restaurant tables. Built using semantic HTML5, utility-first CSS via Tailwind, and optimized vanilla JavaScript, it eliminates the need for expensive native applications or heavy backends. This front-end solution streamlines restaurant workflows by organizing menus contextually by timeline, indicating preparation speed, and incorporating interactive waiter assistance features.

---

## ✨ Features

* 📱 **Mobile-First Responsive Layout:** Custom responsive elements styled gracefully for handheld viewports using a premium dark-mode dashboard aesthetics (`#0f1115`).
* 🧭 **Sticky Scroll-Spy Navigation:** Seamless category pills navigation matching real-time user scroll positions across 7 meal segments (Tiffin, Lunch, Beverages, etc.).
* ⚡ **Dynamic DOM Component Generation:** Zero-dependency vanilla JS data architecture that injects multi-format grids, list layouts, and cards programmatically from modular object templates.
* 🔔 **Digital Waiter Assistance Hook:** Includes an interactive local broadcast mock notification triggers enabling zero-contact operations.
* 🌱 **Visual Dietary Signifiers:** Color-coded structural indicators dynamically classifying items into Pure Vegetarian (`bg-green-500`) and Non-Vegetarian (`bg-red-500`) selections.
* 📢 **Animate Marquee Banner:** Highly-visible, non-blocking sticky notification ticker loop highlighting special announcements and chef recommendations.

---

## 🛠️ Technologies Used

* **Language:** HTML5, JavaScript (ES6+)
* **Styling Framework:** Tailwind CSS v3.x (via CDN Injection)
* **Typography & Vector Graphics:** FontAwesome v6.0.0, Google Fonts (Plus Jakarta Sans)
* **Design Paradigm:** Utility-First CSS, Responsive Breakpoint Grid Layouts, Glassmorphism Filters

---

## 📦 Installation Instructions

Since this is a client-side web application leveraging standard CDNs, setup requires no compilation or build pipelines.

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/nikispace/QR-driven-menu-display.git](https://github.com/nikispace/QR-driven-menu-display.git)
   cd QR-driven-menu-display

```

2. **Run Locally:**
* Double-click the `index.html` file to open it directly in any modern browser.
* Alternatively, spin up a local server using VS Code Live Server extension or Python:


```bash
python -m http.server 8000

```
Then navigate to `http://localhost:8000`.

---

## 💡 Usage

### Component Structure Example

The web application extracts and renders information dynamically based on structured JSON arrays. To update your restaurant's digital items list, modify the `menuData` model inside `index.html`:

```javascript
const menuData = {
    tiffin: [
        { 
          name: "Poo Idli (2 Nos)", 
          price: "₹40", 
          prep: "5m", 
          desc: "Steamed rice cakes with 3 chutneys & sambar.", 
          veg: true 
        }
    ],
    // Add or modify extra segments down here...
};

```

### URL Anchoring

You can link direct physical QR codes straight to isolated structural sections using native window location hashes:

* Landing on Drinks segment directly: `https://nikispace.github.io/QR-driven-menu-display/#drinks`
* Landing on Lunch segment directly: `https://nikispace.github.io/QR-driven-menu-display/#lunch`

---

## 📂 Project Structure

```text
QR-driven-menu-display/
├── index.html        # Main single-page application structure, logic, and dataset
└── README.md         # Professional documentation repository mapping
|__ LICENSE           # Added licence

```

---

## 🖼️ Screenshots / Demo

> 💡 **Recruiter Note:** A live interactive version of this deployment can be tested instantly at [Live Menu Demo Link](https://nikispace.github.io/QR-driven-menu-display/#lunch)
> 
| Desktop & Category View | Mobile UI/UX Engine Mockup |
| --- | --- |
| *[![Project Screenshot](images/Project_picture.png)* | *[[Watch Demo](media/Indian kitchen web in mobile view.mp4)* |

---

## 🤝 Contributing

Contributions are welcome! Please fork this repository and open a pull request for any design enhancements, accessibility implementations (ARIA compliance), or advanced ordering features.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 👤 Contact

* **Developer:** Niki Space ( Nikitha M)
* **GitHub Project URL:** [https://github.com/nikispace/QR-driven-menu-display] - (https://www.google.com/search?q=https://github.com/nikispace/QR-driven-menu-display)
* **Live Project URL:** [https://nikispace.github.io/QR-driven-menu-display/] - (https://www.google.com/search?q=https://nikispace.github.io/QR-driven-menu-display/)

```

```
