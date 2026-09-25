# Daniel Mafuru — Portfolio Website

A modern, single-page developer portfolio for **Daniel Mafuru**, a Full Stack Web Developer. Built with a dark, cyan-accented aesthetic, smooth scroll animations, and a fully responsive layout.

![Preview](potifolio.png)

## Live Preview

Open `potifolio.html` directly in any modern browser — no build step or server required.

## Features

- **Animated hero section** with availability badge, headline, CTAs, and key stats (years of experience, projects delivered, clients, satisfaction rate)
- **Scrolling tech marquee** showcasing the core stack (React, Laravel, Bootstrap, MySQL, PostgreSQL, PHP, Java, JavaScript, HTML5, CSS3)
- **About section** with profile image, floating info card, and bio
- **Skills section** with animated progress bars grouped by Frontend, Backend, and Database
- **Services section** covering full stack development, UI/UX, API development, database design, e-commerce, and maintenance
- **Featured projects grid** with tags, descriptions, and demo/source links
- **Work experience timeline** covering professional history and education
- **Development process** breakdown (Discovery → Design → Development → Testing & Launch)
- **Client testimonials**
- **Contact section** with a working `mailto:` contact form, WhatsApp, phone, and social links
- **Digital rain canvas animation**, scroll-triggered fade-ups, glowing hover effects, and a mobile-friendly nav with slide-out menu
- **Toast notifications** for form feedback

## Built With

- **HTML5** — page structure
- **Tailwind CSS** (via CDN) — utility-first styling
- **Vanilla JavaScript** — animations, canvas rain effect, scroll spy, mobile menu, form handling
- **Iconify** — icon set (Lucide + brand logos)
- **Google Fonts** — Space Grotesk & Geist

No frameworks, bundlers, or dependencies to install — it's a single static HTML file.

##  Project Structure

```
.
├── potifolio.html    # Main portfolio page (all HTML/CSS/JS)
├── potifolio.png     # Profile photo used in the About section
└── README.md         # This file
```

## Getting Started

1. Clone or download this repository.
2. Make sure `potifolio.png` sits in the same folder as `potifolio.html` (the image is referenced by relative path).
3. Open `potifolio.html` in your browser — that's it.

To serve it locally instead (optional, useful for testing on other devices):

```bash
# Python 3
python3 -m http.server 8000

# then visit
http://localhost:8000/potifolio.html
```

## ⚙️ Customization

| What to change | Where |
|---|---|
| Name, title, tagline | `<h1>` in the Hero section |
| Bio, skills percentages | About & Skills sections |
| Services offered | Services section cards |
| Projects, tags, links | Projects section cards (replace placeholder `#` links and `picsum.photos` images with real screenshots) |
| Work history / education | Experience timeline |
| Testimonials | Testimonials section |
| Contact details | Contact section (email, phone, WhatsApp) and the `mailto:` address inside the `<script>` at the bottom |
| Social links | Footer & Contact section (`github.com`, `linkedin.com`, `twitter.com` placeholders) |
| Colors / theme | `tailwind.config` block (`trust` color) and the `<style>` block |

> **Note:** Contact form and phone numbers currently contain placeholder/example values in a couple of spots (e.g. the "Hire Me" WhatsApp links use different numbers in different sections) — double-check and align these to your real contact info before publishing. Social links also point to generic domains and should be updated to your actual profiles.

##  Contact

- **Email:** mafurudaniel99@gmail.com
- **Phone / WhatsApp:** +255 706095151

## 📄 License

© 2025 Daniel Mafuru. All rights reserved. Feel free to fork this for learning purposes, but please don't republish it as your own portfolio.
