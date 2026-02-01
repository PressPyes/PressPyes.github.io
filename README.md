# PressPyes.github.io

Official static website for **PYES** — live at [https://presspyes.com](https://presspyes.com)

This repository powers the official PYES artist website using GitHub Pages with a custom domain.  
It's a clean, fast, single-page static site built with pure HTML, CSS, and vanilla JavaScript — no frameworks, fully responsive, dark-mode aesthetic.

## What's in the Repository

- `index.html` — the complete single-page site (hero, news, discography, mobile menu, SoundCloud/Tidal embeds, IPFS downloads)
- `CNAME` — enables the custom domain `presspyes.com`
- Album/Mixtape artwork:
  - Front and back covers (`.jpg`) for all releases (e.g., `paste_cover.jpg`, `purepyes_front.jpg` / `purepyes_back.jpg`, etc.)

## Features

- Responsive layout (desktop + mobile)
- Hover flip effect on album artwork (front → back)
- Play buttons linking to SoundCloud or Tidal embeds
- **Direct IPFS downloads** for all mixtapes (free, decentralized, permanent via Pinata)
- Discography filter: Popular / Chronological order
- Mobile-friendly hamburger menu
- Gradient accents and modern dark theme

## Mixtape Downloads via IPFS (Free & Decentralized)

All mixtapes are available as ZIP archives pinned on IPFS via Pinata.  
Click the download icon (↓) on each mixtape card on the live site, or use the links below:

- **Paste** (2016)  
  [Download ZIP](https://gateway.pinata.cloud/ipfs/bafybeie6tpmghm2ba6yjj27xmnaop5fvw6r2zrmu6mfxf6daiudbi5t6jy?download=true)

- **Pure Pyes** (2014)  
  [Download ZIP](https://gateway.pinata.cloud/ipfs/bafybeieajkf74bu7jc3xr6murnz4gylepovdaluxjhfr6qqknjpz34lxge?download=true)

- **Price Of The Game** (2008)  
  [Download ZIP](https://gateway.pinata.cloud/ipfs/bafybeihmcrp5xccgu25mezurcehz6kksnne6aca53co3tdtgxjmybhty3i?download=true)

- **Pyes To Cakes Vol 2** (2006)  
  [Download ZIP](https://gateway.pinata.cloud/ipfs/bafybeig64u2hhltdulpaven6gxng6yk6psmp4b7gus733obti445eflpyu?download=true)

- **Pyes To Cakes** (2006)  
  [Download ZIP](https://gateway.pinata.cloud/ipfs/bafybeib66n7ideriumo5sesm2ylz6inf6wgqgbpocsyifhb7ghrcxpeelq?download=true)

- **Ghetto Soul** (2004)  
  [Download ZIP](https://gateway.pinata.cloud/ipfs/bafybeig5udbxb24s2eiynqwiqpd7h4vedk6septq5pyirwmt6sup4pabgy?download=true)

- **Deep Roots** (2003)  
  [Download ZIP](https://gateway.pinata.cloud/ipfs/bafybeifb7l5pbkcckkcxnh4ws42i4xecsphvih5fh27mhjzvmnpxezm3b4?download=true)

These links use Pinata's public gateway with `?download=true` to force a direct file save.  
All content is pinned permanently — files won't disappear.

## How the Site is Hosted & Updated

- **Hosting**: GitHub Pages + custom domain `presspyes.com` (via CNAME file)
- **Deployment**: Any commit/push to the `main` branch automatically updates the live site (usually within 1–2 minutes)
- **Static only** — no backend, no build tools needed

### Quick Update Workflow

1. Clone locally (optional):
   ```bash
   git clone https://github.com/PressPyes/PressPyes.github.io.git
