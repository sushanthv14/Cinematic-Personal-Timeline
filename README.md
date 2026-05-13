# The Drive — Interactive Automotive Portfolio

A high-performance, immersive portfolio showcasing cutting-edge web technologies combined with cinematic automotive storytelling. Built with Three.js, GSAP, and advanced scroll-trigger animations.

## 🎬 Features

- **Live on Vercel** — Deployed and accessible instantly at your Vercel domain
- **3D Scene Rendering** — WebGL-powered Three.js environment with real-time rendering
- **Scroll-Driven Animations** — GSAP ScrollTrigger integration for seamless, choreographed sequences
- **Frame-Based Car Animations** — High-fidelity frame sequencing for ultra-smooth vehicle reveal sequences
- **3D Helix Timeline** — CSS3D rendered milestone timeline with interactive hover states
- **Custom Cursor Mechanics** — Magnetic cursor with glow effects and blend modes
- **Volumetric Lighting** — Dynamic lighting transitions and atmospheric effects
- **Glitch Effects** — Kinetic text animations with 3D perspective transforms
- **Performance Optimized** — Efficient DOM interactions, lazy loading, and contained rendering
- **Responsive Design** — Optimized for desktop viewing experiences

## 🛠️ Tech Stack

- **Three.js** (r128) — WebGL 3D rendering
- **GSAP 3.12** — Animation library with ScrollTrigger & MotionPath plugins
- **CSS3D Renderer** — CSS-based 3D transformations
- **Vanilla JavaScript** — No framework dependencies
- **Modern CSS** — CSS variables, Grid, Flexbox, and animations

## 📋 Project Structure

```
├── index.html          # Main portfolio page
├── assets/            # Image sequences and media files
├── LICENSE            # MIT License
└── README.md          # This file
```

## 🚀 Getting Started

### Requirements
- Modern browser with WebGL support (Chrome, Firefox, Safari, Edge)
- Frame images for car animation sequences loaded via CDN or local assets

### Installation & Deployment

**Live Demo:** Visit the deployed site on Vercel

**Local Development:**

1. Clone the repository:
```bash
git clone https://github.com/yourusername/the-drive.git
cd the-drive
```

2. Install Vercel CLI (optional):
```bash
npm i -g vercel
```

3. Run locally:
```bash
vercel dev
```

4. Deploy to Vercel:
```bash
vercel
```

The site will be live at your Vercel deployment URL instantly after pushing to GitHub.

## 🎨 Customization

### Colors & Theme
Edit CSS variables in the `<style>` section:
```css
:root {
    --cyan: #00f3ff;
    --red: #ff003c;
    --magenta: #ff007f;
    /* ... more variables */
}
```

### Animation Timings
Adjust GSAP timeline durations and easing in the JavaScript section:
- Scroll speeds: `carreraTL` configuration
- Entrance animations: `initAnimations()` function
- Hover states: `.helix-card` event listeners

### Frame Sequences
Update the `frameSrc()` function to point to your frame image paths

## ⚡ Performance Tips

- Pre-load frame images for smoother playback
- Enable hardware acceleration in browser settings
- Test on target devices for optimal frame rates
- Use WebP format for frame images where possible
- Monitor GPU usage with DevTools

## 🔧 Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Full |
| Firefox | ✅ Full |
| Safari  | ✅ Full |
| Edge    | ✅ Full |
| IE 11   | ❌ Not supported |

## 📚 Dependencies

All dependencies are loaded via CDN:
- GSAP 3.12.2
- Three.js r128
- Google Fonts (Syncopate, JetBrains Mono)

No build process required—works out of the box.

## 🎯 Use Cases

- Personal portfolio hosted on Vercel showcasing advanced web development skills
- Interactive case studies for automotive/product design with instant deployment
- Demonstration of modern animation techniques with zero-config hosting
- Template for immersive storytelling websites

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Feel free to fork, modify, and improve. If you create something cool with this, let me know!

## 📧 Contact

For questions or feedback, reach out via GitHub or visit my portfolio.

---

**Built with obsession for detail and performance.**
