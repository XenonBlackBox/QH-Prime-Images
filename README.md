# 🐎 QH Prime Consulting — Image Assets

This repository stores **official image assets** for the QH Prime Consulting platform.  
All files are hosted here for easy access during development, deployment, and marketing.

---

## 📂 Repository Structure


/assets
├── logo.png              # Primary logo (transparent background, web use)
├── logo-dark.png         # Alternate version (for dark backgrounds)
├── favicon.ico           # Favicon for browser tabs
├── horse-icon.png        # Minimal horse silhouette (social, small display)
└── samples/              # Screenshots & demo graphics

---

## 🎨 Logo Usage

### Primary Logo (Transparent)
- **File:** `assets/logo.png`  
- **Use Case:** Website header, app UI, documents  
- **Background:** Optimized for **white/light backgrounds**  

### Dark Logo (Navy Background)
- **File:** `assets/logo-dark.png`  
- **Use Case:** Presentations, pitch decks, social media  
- **Background:** Optimized for **dark backgrounds**  

### Minimal Horse Icon
- **File:** `assets/horse-icon.png`  
- **Use Case:** Favicon, app icons, watermarks  
- **Background:** Transparent  

---

## 🌐 Direct Hosting Links
If this repo is public and GitHub Pages is enabled:  

- **Primary Logo:**  
  `https://yourusername.github.io/qhprime-images/assets/logo.png`

- **Dark Logo:**  
  `https://yourusername.github.io/qhprime-images/assets/logo-dark.png`

- **Horse Icon:**  
  `https://yourusername.github.io/qhprime-images/assets/horse-icon.png`

---

## 📜 License
All logos and assets are © Project Black Box LLC.  
Usage outside of QH Prime Consulting is **strictly prohibited** without written consent.  

---

## 🔗 Integration with QH Prime
When deployed with Emergent:  
1. Add the logo to your **`/public/`** folder for automatic serving:  
   - `/public/logo.png` → `https://qhprime.consulting/logo.png`  
2. Reference it in React:  
   ```tsx
   import Logo from "/logo.png";

   function Header() {
     return (
       <header>
         <img src={Logo} alt="QH Prime Consulting Logo" className="h-12" />
       </header>
     );
   }
