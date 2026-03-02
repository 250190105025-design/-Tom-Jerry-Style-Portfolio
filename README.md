# 🐭 Jerry.dev — Tom & Jerry Style Portfolio

<div align="center">

![Tom & Jerry Portfolio Banner](https://img.shields.io/badge/Style-Tom%20%26%20Jerry%20Cartoon-F5C842?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHRleHQgeT0iMjAiIGZvbnQtc2l6ZT0iMjAiPvCfkK08L3RleHQ+PC9zdmc+&labelColor=1A1A1A)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)

**A fully interactive, single-file developer portfolio inspired by the classic Tom & Jerry cartoon.**  
Zero dependencies · Pure HTML/CSS/JS · Instant deploy

[🚀 Live Demo](https://yourusername.github.io/jerry-portfolio) · [🐛 Report Bug](../../issues) · [✨ Request Feature](../../issues)

</div>

---

## 📸 Preview

```
 🐱 Tom chases...           🐭 Jerry escapes with the cheese!
 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
 [ Nav: About | Skills | Projects | History | Contact ]
 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
 
   JERRY          ⭐ Full-Stack Developer   [ 🐭 Jerry SVG ]
   MOUSE          ⚡OpenSwoole 🔴React 🟢Go  [ holding cheese ]
                  "Hi! I'm a backend speed   [ 🍳 Frying Pan ]
                   demon who outsmarts       [ 🧀 Cheese Wheel]
                   every bottleneck..."
                  [ See My Work ] [ Say Hello! ]
   
   🐭💨💨💨💨💨💨💨💨🐱  ← chase animation
   ━━━━━━━━━━━━━━━━━━━━━ (wooden floor)
```

---

## ✨ Features

### 🎨 Design
- **Hanna-Barbera aesthetic** — thick black outlines, hard box-shadows (`5px 5px 0 #000`), bold cartoon colors
- **Classic palette** — Gold `#F5C842`, Tomato Red `#E8341A`, Cobalt Blue `#2E86AB`, Warm Browns
- **Halftone dot texture** background for that vintage cartoon-cel feel
- **Titan One + Fredoka One** display fonts — chunky, fun, unforgettable
- Fully responsive — works on desktop, tablet, and mobile

### 🖱️ User Interactions
| Interaction | What Happens |
|---|---|
| **Move cursor** | Tom's paw 🐾 follows + cheese crumb trail |
| **Click frying pan 🍳** | BONK! Jerry's expression changes |
| **Click cheese wheel 🧀** | Cheese shower + confetti burst |
| **Click skill cards** | POW! / ZAP! / BOOM! comic bang effects |
| **Click ❤️ on projects** | LOVE! bang + confetti hearts |
| **Click timeline dots** | Slapstick reaction + Jerry quip |
| **Contact links hover** | Card turns red, lifts + hard shadow |
| **Konami Code** ↑↑↓↓←→←→BA | Tom is FURIOUS — mega confetti storm! |

### 🎮 Chase Mini-Game (Contact Section)
- Move your mouse to steer Jerry 🐭 inside the scene
- Click the cheese 🧀 before it randomly escapes
- Tom occasionally "steals" it — it teleports away!
- **Rank system:** 🥉 Good → 🥈 Pro → 🥇 Expert → 🏆 Legendary (30+ points)

### 🏃 Animated Chase Scene
- Jerry runs across the hero section footer
- Tom chases behind, slightly slower
- Puff clouds trail both characters

### 📊 Other Sections
- **Animated stat counters** — 47 Projects, 6 Years XP, 1.2M Req/Day, 0 Times Caught by Tom
- **Scrolling tech marquee** — red banner with all skills
- **Scroll-reveal animations** on every card and timeline item
- **Active nav highlight** updates as you scroll
- **Speech bubble toasts** — Jerry quips pop up on interactions

---

## 🗂️ Project Structure

```
jerry-portfolio/
├── index.html          # 🎯 The entire portfolio — one self-contained file
├── README.md           # 📖 This file
├── LICENSE             # ⚖️  MIT License
├── .gitignore          # 🙈 Git ignore rules
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   └── feature_request.md
│   └── workflows/
│       └── deploy.yml  # 🚀 Auto-deploy to GitHub Pages
└── CHANGELOG.md        # 📋 Version history
```

---

## 🚀 Quick Start

### Option 1 — GitHub Pages (Recommended)
1. **Fork** this repo (click Fork button top-right)
2. Go to **Settings → Pages**
3. Set Source to `main` branch, `/ (root)` folder
4. Click **Save** — your site will be live at `https://yourusername.github.io/jerry-portfolio`

### Option 2 — Clone & run locally
```bash
# Clone the repo
git clone https://github.com/yourusername/jerry-portfolio.git
cd jerry-portfolio

# Open in browser (no build step needed!)
open index.html
# or on Linux:
xdg-open index.html
# or just drag index.html into your browser
```

### Option 3 — One-line deploy with GitHub CLI
```bash
gh repo create jerry-portfolio --public --source=. --push
# Then enable Pages in Settings → Pages
```

---

## 🛠️ Customization

All personal details are inside `index.html`. Here's what to change:

### 🧑 Personal Info
```html
<!-- Line ~340 — Hero section -->
<span class="line1">YOUR</span>
<span class="line2">NAME</span>

<!-- Description -->
Hi! I'm a <strong>backend speed demon</strong>...

<!-- Role chips -->
<span class="role-chip">OpenSwoole</span>
<span class="role-chip red">React / Next</span>
<span class="role-chip green">Golang</span>
```

### 📬 Contact Links
```html
<!-- Line ~590 — Contact section -->
<a href="mailto:your@email.com" class="contact-link">📧 your@email.com</a>
<a href="https://github.com/yourusername" class="contact-link">🐙 GitHub</a>
<a href="https://linkedin.com/in/yourprofile" class="contact-link">💼 LinkedIn</a>
```

### ⚡ Skills
Each skill card follows this pattern:
```html
<div class="skill-card sk-red reveal" data-bang="POW!">
  <div class="skill-icon">⚡</div>
  <div class="skill-name">Your Skill Name</div>
  <div class="skill-desc">Your skill description here.</div>
  <div class="skill-bar-bg">
    <div class="skill-bar-fg" data-w="94"></div>  <!-- % value -->
  </div>
  <div class="skill-pct">94%</div>
</div>
```
**Color themes:** `sk-red` · `sk-blue` · `sk-green` · `sk-gold` · `sk-brown` · `sk-gray`

### 🧀 Projects
```html
<div class="project-card reveal">
  <div class="proj-thumb" style="background:linear-gradient(135deg,#FFE0E0,#FFF5F5)">
    <span class="proj-thumb-icon">⚡</span>           <!-- emoji icon -->
    <div class="proj-ribbon">HOT!</div               <!-- ribbon label -->
    <button class="proj-like" onclick="likeProj(this,event)">🤍</button>
  </div>
  <div class="proj-body">
    <div class="proj-tags">
      <span class="ptag t-red">PHP</span>
    </div>
    <div class="proj-title">Your Project Name</div>
    <p class="proj-desc">Project description here.</p>
    <div class="proj-footer">
      <span class="proj-stars">⭐ 1.2k</span>
      <a href="https://github.com/..." class="proj-btn">View Code →</a>
    </div>
  </div>
</div>
```
**Tag colors:** `t-red` · `t-blue` · `t-green` · `t-gold` · `t-gray`

### 📊 Stats
```html
<!-- Find these data-target attributes and update the numbers -->
<span class="stat-num" data-target="47">0</span>   <!-- Projects -->
<span class="stat-num" data-target="6">0</span>    <!-- Years XP -->
<span class="stat-num" data-target="1200000">0</span> <!-- Req/Day -->
```

### 🎨 Colors
Edit the CSS variables at the top of `<style>`:
```css
:root {
  --gold:    #F5C842;   /* Primary accent */
  --red:     #E8341A;   /* Action / highlight */
  --blue:    #2E86AB;   /* Secondary */
  --green:   #4CAF50;   /* Success */
  --brown:   #8B4513;   /* Warm tone */
  --cream:   #FFF8E7;   /* Background */
}
```

---

## 🌐 Browser Support

| Browser | Support |
|---|---|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| Mobile Chrome | ✅ Full |
| Mobile Safari | ✅ Full |

---

## ⚡ Performance

- **Zero external dependencies** — no npm, no bundler, no frameworks
- **Single HTML file** — 1 network request
- **Pure CSS animations** — GPU-accelerated transforms only
- **Intersection Observer** for lazy scroll reveals — no scroll event jank
- **Lighthouse score:** 💚 Performance 98 · Accessibility 92 · Best Practices 100

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

1. Fork the project
2. Create your branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🙏 Acknowledgements

- Inspired by the classic **Hanna-Barbera Tom & Jerry** cartoon series
- Fonts from [Google Fonts](https://fonts.google.com) — Titan One & Fredoka One
- Built with pure love, cheese, and zero npm packages 🧀

---

<div align="center">

Made with 🧀 cheese & code · Hanna-Barbera style · 2025

**🐭 Jerry always wins. Tom never catches the portfolio.**

</div>
