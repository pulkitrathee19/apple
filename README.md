# Apple Homepage — Modern Web Experience

A pixel-perfect, responsive website inspired by Apple's official homepage, showcasing the latest hardware innovations and software experiences with Apple's signature minimalist design language.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Design](https://img.shields.io/badge/Design-Apple%20Minimalism-black)

---

## ✨ Features

- **Clean White Navigation Bar**:
  - Translucent frosted glass effect (`backdrop-filter: saturate(180%) blur(20px)`), deepening upon scroll.
  - Vector Apple branding, complete menu directory (*Store, Mac, iPad, NewtonPhone, Watch, Vision, AirPods, TV & Home, Entertainment, Accessories, Support*).
  - Interactive search bar trigger and shopping bag icon with live item badge counter.
  - Fully responsive mobile navigation with animated hamburger drawer.

- **NewtonPhone 16 Pro Hero Section**:
  - Dramatic dark titanium theme with dynamic ambient atmospheric glow.
  - **Interactive Titanium Color Switcher**: Toggle between *Desert Titanium*, *Natural Titanium*, *White Titanium*, and *Black Titanium* to see dynamic finish tags and lighting updates.
  - Hardware highlights ribbon: *Grade 5 Titanium*, *A18 Pro with 16-Core Neural Engine*, *48MP Fusion & Camera Control*, *Up to 33 hrs Video Playback*.
  - Dual call-to-actions: Apple signature blue pill button (**"Learn more"**) and outline pill button (**"Buy"**).

- **NewtonPhone 16 Standard Section**:
  - Vibrant showcase highlighting the saturated color palette (*Ultramarine, Teal, Pink, White, Black*).

- **MacBook Pro Section**:
  - Space Black finish with Liquid Retina XDR screen glow and M4 chip credentials.
  - Performance metrics bar (*3.4x faster than M1 Max*, *24 hrs battery life*, *1600 nits peak HDR brightness*, *up to 128GB unified memory*).

- **iPad Pro Section**:
  - Minimalist silver theme highlighting *"Thinpossible."* (5.1 mm ultra-thin profile, tandem OLED Ultra Retina XDR display, and Apple Pencil Pro).

- **Apple Watch Series 10 Section**:
  - Jet Black polished finish, wide-angle OLED display, sleep apnea notifications, and fast charging metrics.

- **Apple Bento Grid**:
  - 2x2 responsive bento cards for **Apple Vision Pro**, **AirPods Pro**, **Apple Trade In**, and **Apple Card**.

- **Apple TV+ Entertainment Showcase**:
  - Streaming carousel featuring Apple Originals (*The Morning Show*, *Severance*).

- **Interactive "Buy" Configurator & Slide-Over Bag Drawer**:
  - Clicking **"Buy"** on any device opens a modal to choose storage capacities (128GB, 256GB, 512GB, 1TB) with live price recalculation.
  - Clicking **"Add to Bag"** animates the navbar badge and slides open the shopping bag drawer with subtotal calculation, free shipping note, and checkout flow.

- **Apple Global Footer**:
  - 5 legal footnotes & disclaimers with superscript references.
  - Breadcrumb navigation (`Apple Logo > Apple Store`).
  - 5-column directory hierarchy covering all 10 Apple divisions.
  - Copyright notices, legal links, and country/region selector.

---

## 📁 Project Structure

```
apple-homepage/
├── index.html                   # Semantic HTML5 with Apple layout & typography
├── README.md                    # Project documentation
├── .gitignore                   # Ignored files
└── assets/
    ├── css/
    │   └── styles.css           # Glassmorphism, SF typography, pill buttons & responsive layouts
    ├── js/
    │   └── main.js              # Navbar scroll, color switchers, configurator modal & bag drawer
    └── images/                  # High-resolution official product photography
```

---

## 🚀 Getting Started

No build tools or external dependencies required! Simply open the project in any browser:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/pulkitrathee19/apple.git
   cd apple
   ```

2. **Open directly in browser:**
   ```bash
   open index.html
   ```

3. **Or run with a local development server:**
   ```bash
   python3 -m http.server 3000
   ```
   Then visit `http://localhost:3000` in your browser.

---

## 🎨 Design Tokens & Standards

- **Typography:** `-apple-system, BlinkMacSystemFont, "SF Pro Display", "SF Pro Text", "Helvetica Neue", sans-serif`
- **Pill Buttons:** `border-radius: 980px`, Apple blue `#0071e3` / `#0077ed`
- **Backdrop Blur:** `backdrop-filter: saturate(180%) blur(20px)`
- **Responsive Breakpoints:** Optimized for Mobile (`< 540px`), Tablet (`< 834px`), Small Desktop (`< 1024px`), and Large Desktop (`1200px+`)
