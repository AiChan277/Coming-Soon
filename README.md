# Rachelian — Coming Very Soon :3

A standalone, cozy, interactive "Coming Very Soon" landing page crafted for **Rachelian**, ready to deploy directly to **Cloudflare Pages** as a static website.

---

## 🌸 Core Concept & Features

Designed to evoke the warm, tranquil feeling of a developer's bedroom at night:
- **Anime & Cozy Aesthetic:** Deep navy, dark purples, soft pinks, lavender, and warm amber highlights.
- **100% Vector & Framework-Free:** Built with pure semantic HTML5, modern CSS3, vanilla JavaScript, and an animated vector SVG scene. Zero raster images, no React, Next.js, Vue, Tailwind, or heavy runtime libraries.
- **Sub-Second Performance:** Single self-contained static `index.html` file (~45 KB).
- **Two-Column Balanced Composition:** Crisp, glowing typography and interactive pills on the left; animated cozy cat bedroom scene on the right.

### 🐱 Animated Cozy Cat Scene
- **Gentle Breathing Animation:** Smooth rhythmic chest/belly expansion.
- **Lazy Tail Wag:** Slow, relaxed tail movement.
- **Ear Twitches:** Interactive and periodic twitching ears.
- **Floating Zzz's:** Drifting dream particles rising from the sleeping cat.
- **Interactive Petting:** Clicking or pressing <kbd>C</kbd> triggers synthesized cat purrs/meow sounds, floating heart bursts, and playful speech bubbles (*"purrrrr... sleeping warmly :3 ♡"*).
- **Steaming Mug:** Continuous animated steam rising above the cat-face ceramic mug (click for hot cocoa tooltip).
- **Real-Time Digital Clock:** Synchronized with the visitor's local system time (`HH:MM`) with a blinking colon and *"Good things take time ♡"* subtitle.
- **Developer Laptop:** Click to open Rachelian's terminal easter egg.
- **Desk Bookshelf:** Click to inspect the reading list (*Ideas*, *Code*, *Design*, *Better Me ♡*).
- **Hanging Stars:** Swaying in the breeze; click for crystalline bell chimes and stardust showers.
- **Night Window:** Cat-shaped crescent moon, city skyline with twinkling lights, and shooting stars.

### 🎵 Lofi Audio Engine
- **Dual-Mode Audio:**
  - **Dream Synth Mode:** 100% procedural ambient Rhodes electric piano chord progressions synthesized live with the Web Audio API and gentle vinyl warmth. Completely offline, zero external dependencies, zero bandwidth, and zero copyright issues.
  - **Live Radio Mode:** Verified streaming endpoint for **SomaFM Groove Salad** (commercial-free, listener-supported ambient chill with CORS enabled).
  - Includes play/pause toggle, volume slider, interactive animated equalizer bars, and graceful error handling.

### 📜 Section 2 ("Currently Cooking...")
- **Pillars of Work:** Aesthetic Design (92%), Zero-bloat Code (88%), Edge Systems (95%), and Creative Magic (99%).
- **Cozy Quote Roller:** *"Another thought ✦"* button cycling through cute microcopy thoughts.
- **Cozy VIP Club:** LocalStorage-backed notification signup with instant confirmation.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `Space` | Toggle Lofi Radio Play / Pause |
| `M` | Mute / Unmute audio |
| `C` | Pet the cat :3 |
| `Esc` | Close any active modal or dropdown panel |

---

## 🚀 Cloudflare Pages Deployment

This project is a 100% static site with no backend runtime, database, or server dependencies.

### Option A: Deploy via Cloudflare Dashboard (Recommended)

1. Push this repository to GitHub or GitLab:
   ```bash
   git add .
   git commit -m "feat: replace raster image with pure animated svg cat scene"
   git push origin main
   ```
2. Log into the [Cloudflare Dashboard](https://dash.cloudflare.com/) and navigate to **Workers & Pages** > **Create application** > **Pages** > **Connect to Git**.
3. Select your `Coming-Soon` repository.
4. Configure the build settings:
   - **Framework preset:** `None`
   - **Build command:** *(Leave empty)*
   - **Build output directory:** `.` *(or root directory)*
5. Click **Save and Deploy**.

### Option B: Direct Upload via Wrangler CLI

```bash
npm install -g wrangler
wrangler login
wrangler pages deploy . --project-name=rachelian-coming-soon
```

---

## 📄 License

MIT License — feel free to customize and enjoy warmly! ♡
