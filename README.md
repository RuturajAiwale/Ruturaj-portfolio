# 🛡️ Ruturaj Aiwale — Personal Portfolio

> **Technical Support Engineer | Microsoft CE&S | Cloud & Enterprise IT Operations**

A responsive, single-page portfolio website showcasing my professional experience, technical skills, certifications, and contact information.

---

## 🌐 Live Preview

Open `index.html` directly in any modern browser — no build step or server required.

---

## 📋 Table of Contents

- [About](#about)
- [Sections](#sections)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Customisation](#customisation)
- [Contact](#contact)

---

## About

This is my personal portfolio site built with vanilla HTML, CSS, and JavaScript. It is designed to present my professional profile to recruiters, hiring managers, and collaborators in the Microsoft, cloud, and enterprise IT space.

---

## Sections

| Section | Description |
|---|---|
| **Hero** | Animated typing headline, key stats, and CTA buttons |
| **Current Role** | Live status banner — Technical Support Engineer at Microsoft CE&S |
| **Philosophy** | Core working principles: Resolve Fast, Root Cause Everything, Document Everything |
| **Experience** | Tabbed view — Microsoft CE&S, Rahitech IT Solutions internship, and lab projects |
| **Impact & Certifications** | Key metrics (SLA, CSAT, resolution speed) and certification progress |
| **Tech Stack** | Dynamically rendered skills cloud |
| **Contact** | Contact details and a contact form |

---

## Tech Stack

**Languages & Technologies used to build this site:**

- HTML5
- CSS3 (custom properties, CSS Grid, Flexbox, animations)
- Vanilla JavaScript (ES6+)

**External resources (CDN — no npm install needed):**

- [Font Awesome 6](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css) — icons
- [Google Fonts](https://fonts.google.com/) — Poppins & JetBrains Mono

---

## Features

- **Typing animation** — cycles through phrases in the hero headline
- **Animated counters** — stat numbers count up when scrolled into view (Intersection Observer)
- **Orbiting skill nodes** — CSS `@keyframes` animation in the hero visual
- **Tabbed experience section** — switch between roles and projects without page reload
- **Dynamic skills cloud** — skill tags generated from a JavaScript array; easy to extend
- **Sticky navbar** with blur backdrop and smooth-scroll active-link highlighting
- **Mobile responsive** — hamburger menu for small screens
- **Contact form** — client-side validation with a toast notification on submission
- **Animated background** — subtle floating gradient orbs (GPU-friendly, `opacity: 0.03`)
- **Zero dependencies** — no frameworks, no build tools, no package.json

---

## Getting Started

### Option 1 — Open directly

```bash
# Clone or download the repo, then just open the file
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

### Option 2 — Local dev server (recommended for editing)

```bash
# Using Python (comes pre-installed on most systems)
python3 -m http.server 8080

# Or using Node.js
npx serve .
```

Then visit `http://localhost:8080` in your browser.

---

## Project Structure

```
portfolio/
│
├── index.html       # Single self-contained file (HTML + CSS + JS)
└── README.md        # This file
```

All styles and scripts are embedded inside `index.html` for maximum portability — no separate asset folders needed.

---

## Customisation

All content lives inside `index.html`. Here are the key areas to edit:

### Personal details
Search for and update your name, title, email, phone number, LinkedIn URL, GitHub URL, and location in the `<!-- Hero -->` and `<!-- Contact -->` sections.

### Stats (hero counter)
```html
<span class="stat-number" data-count="20">0</span>
```
Change the `data-count` value to update the animated counter target.

### Typing animation phrases
```javascript
const phrases = [
    'Enterprise Issues.',
    'Azure Incidents.',
    // add or remove phrases here
];
```

### Skills cloud
```javascript
const skills = [
    { name: 'Microsoft 365', icon: 'fab fa-microsoft' },
    // add new skill objects here
];
```

### Colour scheme
CSS custom properties in `:root` control the entire colour palette:
```css
:root {
    --primary: #00d4aa;      /* teal accent */
    --secondary: #6c5ce7;    /* purple accent */
    --dark: #0f172a;
    --darker: #0a0f1f;
}
```

---

## Contact

| Channel | Details |
|---|---|
| 📧 Email | ruturajaiwale@gmail.com |
| 📞 Phone | +91 9130454291 |
| 💼 LinkedIn | [linkedin.com/in/ruturajaiwale](https://linkedin.com/in/ruturajaiwale) |
| 🐙 GitHub | [github.com/ruturajaiwale](https://github.com/ruturajaiwale) |
| 📍 Location | Navi Mumbai, Maharashtra, India |

---

> © 2026 Ruturaj Aiwale. Open to **Technical Support Engineer**, **Cloud Support Engineer**, and **IT Operations Engineer** opportunities.
