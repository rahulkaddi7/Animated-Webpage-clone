# 💠 CYBERFICTION – Interactive Scroll Animation Experience

[LINK](https://animated-webpage.onrender.com)

---

## 🧩 Overview

**CYBERFICTION** is a visually engaging, scroll-based web experience designed to immerse users in a futuristic virtual world. It combines smooth scrolling, canvas-based animation, and a decentralized storytelling concept.

This project uses:
- **GSAP** and **ScrollTrigger** for scroll-driven animation.
- **Locomotive Scroll** for smooth scrolling.
- **Canvas rendering** for frame-by-frame animation using 300 high-resolution character images.

---

## 🎬 Features

- 🚀 **Smooth Scrolling:** Powered by LocomotiveScroll for elegant navigation.
- 🎞 **Canvas-Based Frame Animation:** Displays a 300-frame animated sequence based on scroll position.
- 📌 **Scroll Pinning:** Key content pages stay fixed while the user scrolls, enhancing focus.
- 🌐 **Responsive Design:** Canvas adjusts dynamically on window resize.
- 💡 **Semantic Messaging:** Aims to promote creativity, community, and good humanity in virtual worlds.

---

## 📂 File Structure

```
/images/
  male0001.png
  ...
  male0300.png
index.html
style.css
script.js
README.md
```

---

## 🔧 Technologies Used

- [GSAP (GreenSock Animation Platform)](https://greensock.com/gsap/)
- [ScrollTrigger](https://greensock.com/scrolltrigger/)
- [Locomotive Scroll](https://locomotivemtl.github.io/locomotive-scroll/)
- HTML5 Canvas API
- JavaScript (vanilla)

---

## 📜 JavaScript Functionality Breakdown

### 1. `locomotive()`
- Initializes smooth scrolling.
- Syncs LocomotiveScroll with GSAP's ScrollTrigger.

### 2. Canvas Setup
- Dynamically resizes the canvas to full viewport.
- Loads 300 images (`male0001.png` to `male0300.png`) into memory.

### 3. Scroll-Driven Frame Control
- Animates frame playback as the user scrolls.
- Uses `gsap.to()` to interpolate through frames smoothly.

### 4. Pinning Pages
- Uses ScrollTrigger to pin `#page1`, `#page2`, and `#page3` during scroll.

---

## 🚀 How to Run Locally

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/cyberfiction.git
   cd cyberfiction
   ```

2. Make sure your images are in `/images/` and named correctly (`male0001.png` to `male0300.png`).

3. Open `index.html` in a browser.

---

## 👁‍🗨 License & Use

This project is designed as a creative scroll experience and may serve as a prototype for decentralized storytelling or metaverse projects. Attribution required if reused or remixed.
