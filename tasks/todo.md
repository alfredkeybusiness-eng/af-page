# Advisor Landing Page v2 + motion

- [x] Pull design handoff files (v2 .dc.html, assets) into repo
- [x] Port `Advisor Landing Page v2.dc.html` to static `index.html` + `styles.css` + `main.js`
- [x] Scroll/entrance motion (IntersectionObserver reveals, header shrink, nav scroll-spy; all disabled under prefers-reduced-motion)
- [x] HyperFrames hero clip: `motion/hero` -> `assets/hero-motion.mp4` (8s, 710 KB, plays once over hero photo)
- [x] Verified: desktop + mobile render, no console errors, no horizontal scroll, all reveals fire

## Notes
- Source of truth was the Claude Design handoff; the `.dc.html` prototype runtime (`support.js`) is not needed by the static port.
- Form stays disabled (demo only) and all "pending review" copy is kept as designed.
