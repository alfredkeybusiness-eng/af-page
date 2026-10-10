# Hero motion (HyperFrames)

Source for `assets/hero-motion.mp4`: an 8s square push-in on the hero photo with a soft light sweep and drifting dust motes.

```bash
cd motion/hero
npx hyperframes@0.8.143 check
npx hyperframes@0.8.143 render -f 30 -q looks --crf 26 -o ../../assets/hero-motion.mp4
```

`gsap.min.js` is vendored so renders don't need a CDN.
