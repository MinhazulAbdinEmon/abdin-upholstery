# ABDIN Auto Seats Upholstery L.L.C — Website

Premium one-page website for **ABDIN Auto Seats Upholstery L.L.C** — bespoke
automotive and home upholstery (car seats, sofa re-covering, custom headboards).

Static site — plain HTML + CSS + a little vanilla JavaScript. No build step.

## Highlights
- Cinematic full-bleed **hero video** (scroll-triggered: plays in view, pauses when away)
- **Steering-wheel intro animation** on first visit
- **Always-on glowing logo** and an animated **glowing WhatsApp button** (+971 55 628 2836)
- Services, materials, testimonials, and map directions
- Fully responsive (desktop + mobile), with `prefers-reduced-motion` support

## Run locally
Open `index.html` directly, or serve the folder:

```bash
python -m http.server 5577
# then visit http://localhost:5577
```

## Deploy
Any static host works (the whole folder is self-contained):
- **GitHub Pages:** Settings → Pages → deploy from `main` / root
- **Netlify / Vercel:** drag-and-drop the folder, or connect this repo

## Structure
```
index.html                 # the entire site (markup + styles + scripts)
finalized logo.png         # brand logo
intro.jfif, car seats.jfif, sofa covering.jfif, bed headboards.jfif
assets/videos/craft.mp4    # hero video
```
