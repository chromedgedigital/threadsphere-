# ThreadSphere — File Structure Guide

## 📁 Folder Structure
```
threadsphere/
├── index.html              ← Main page (structure only)
├── images/
│   ├── photo1.jpg          ← Rename your photos to photo1–photo6
│   ├── photo2.jpg
│   ├── photo3.jpg
│   ├── photo4.jpg
│   ├── photo5.jpg
│   └── photo6.jpg
├── css/
│   ├── variables.css       ← 🎨 COLORS & FONTS — edit to change theme
│   ├── base.css            ← Reset, body, cursor, buttons, loader
│   ├── animations.css      ← All @keyframes + scroll reveal classes
│   ├── effects.css         ← Blobs, tape, stickers, canvas, rings
│   ├── nav.css             ← Navigation bar
│   ├── hero.css            ← Hero section
│   ├── marquee.css         ← Scrolling text strip
│   ├── gallery.css         ← Gallery grid
│   ├── craft.css           ← Craft story section
│   ├── process.css         ← Process steps
│   ├── pricing.css         ← Pricing cards
│   ├── testimonials.css    ← Testimonial cards
│   ├── instagram.css       ← Instagram grid
│   ├── contact.css         ← Contact form
│   └── footer.css          ← Footer + Final CTA
└── js/
    ├── animations.js       ← Scroll reveal, counter, parallax, tilt
    ├── effects.js          ← Floating stickers, thread canvas, sparkles
    └── interactions.js     ← Loader, cursor, nav, form, scroll-top

```

## ✏️ How to Make Changes

| What to change | Edit this file |
|---|---|
| Colors / fonts | `css/variables.css` |
| Animation speeds | `css/animations.css` |
| Floating stickers | `js/effects.js` |
| Contact form logic | `js/interactions.js` |
| Gallery layout | `css/gallery.css` |
| Pricing cards | `css/pricing.css` |
| Nav links | `index.html` |
| Text content | `index.html` |
| Images | Replace files in `images/` folder |

## 🖼️ Replacing Images
1. Name your photos: `photo1.jpg` to `photo6.jpg`
2. Upload them to the `images/` folder on GitHub
3. Done! No code changes needed.

## 🚀 GitHub Pages Upload Order
Upload ALL these folders/files to your repository:
- `index.html`
- `css/` folder (all files inside)
- `js/` folder (all files inside)  
- `images/` folder (your photos)
