# bumper the Band — Official Website

The official website for **bumper**, a three-piece alternative indie band from Washington featuring Jayden Tierney, Maile Salois, and Amos Horne. Live at [bumpertheband.com](https://bumpertheband.com).

---

## Overview

A static multi-page website hosted on **GitHub Pages** with a custom domain. Built with pure HTML and CSS, it serves as the band's hub for music discovery, merchandise, and fan engagement. No build step or server required.

---

## Pages

| File | URL | Description |
|---|---|---|
| `index.html` | `/` | Home — band intro, photo slideshow, merch shop |
| `pages/discography.html` | `/pages/discography.html` | Music — full discography with streaming links |
| `pages/contact.html` | `/pages/contact.html` | Contact — social links and contact info |

---

## Project Structure

```
bumperwebsite/
├── index.html              # Home page
├── style.css               # Merch grid and home page styles
├── univ.css                # Shared styles: nav, size modal, cart badge
├── favicon.jpg             # Browser tab icon
├── CNAME                   # GitHub Pages custom domain (bumpertheband.com)
├── pages/
│   ├── discography.html    # Music / discography page
│   ├── disc.css            # Discography page styles
│   ├── contact.html        # Contact page
│   └── cntc.css            # Contact page styles
└── assets/
    ├── bumperbanner.jpg    # Top banner image
    ├── burg.png            # Hamburger menu icon
    ├── Slideshow/          # 11 photos for the home page slideshow (1.jpg–11.jpg)
    ├── SocIcn/             # Social/streaming platform icon images
    ├── SongCovers/         # Album and single artwork
    └── merch/              # Merch product photos
```

---

## Features

### Navigation
Every page shares a consistent burger-menu dropdown (`.brgbx` / `.drp`). Clicking the hamburger icon slides open a nav panel with links to Home, Music, and Contact Us.

### Home Page
- **Banner** — full-width `bumperbanner.jpg` at the top
- **Social / streaming bar** — icon links to Spotify, Apple Music, Amazon Music, Instagram, TikTok, Facebook, YouTube
- **Photo slideshow** — 11-image carousel with prev/next arrows
- **Merch shop** — CSS grid of product listings. Apparel items trigger a size-picker modal (XS–3XL) before adding to cart; accessories (stickers, hats) skip the modal

### Merch Catalog

| Product | Price | Size Required |
|---|---|---|
| bumper Neon T-Shirt | $30.00 | Yes |
| Album T-Shirt | $30.00 | Yes |
| BUMP3R Longsleeve | $50.00 | Yes |
| BUMP3R Crewneck | $52.00 | Yes |
| White Rose Hoodie | $50.00 | Yes |
| White Rose Crewneck | $55.00 | Yes |
| White Rose Shirt | $40.35 | Yes |
| BUMP3R Hat | $25.00 | No |
| BUMP3R Bumper Sticker | $7.25 | No |

### Discography
Searchable song/album grid. Each entry shows the song title, album art, album name, and icon links to Spotify, Amazon Music, and Apple Music.

**Releases:**
- **Intertwined** (EP/Album) — Your Love Tonight, I Won't Forget, Selene, Want to Stay, Intertwined, Take the Burden, White Rose, End Scene
- **Take The Burden - Extended** (Single)

---

## Deployment

The site deploys automatically from the `main` branch via **GitHub Pages**. The `CNAME` file sets the custom domain to `bumpertheband.com`.

Push HTML/CSS changes to `main` and they go live within seconds. No build step needed.

---

## Local Development

No server required. Just open `index.html` in a browser, or use VS Code's Live Server extension.

---

## Social & Streaming

| Platform | Link |
|---|---|
| Spotify | https://open.spotify.com/artist/1gHIm66CzHIb1HP74a0iwo |
| Apple Music | https://music.apple.com/us/artist/bumper/1821055021 |
| Amazon Music | https://music.amazon.com/artists/B08KS6K125/bumper |
| Instagram | https://www.instagram.com/bumpertheband/ |
| TikTok | https://www.tiktok.com/@bumpertheband |
| Facebook | https://www.facebook.com/people/bumper-The-Band/61578075552657/ |
| YouTube | https://www.youtube.com/@bumpertheband |
| Ko-fi (donate) | https://ko-fi.com/bumpertheband |
