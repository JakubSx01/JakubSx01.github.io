# Jakub Skrzynecki — Portfolio

Personal portfolio website of Jakub Skrzynecki — Electronics Engineer (B.Eng.) and Cybersecurity Specialist (M.Sc.).

**Live:** [jakubsx01.github.io](https://jakubsx01.github.io)

---

## About

Single-page portfolio built with vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies.
Showcases engineering projects, cybersecurity academic work, certifications, and contact links.

---

## Features

- **Light / Dark mode** — toggle in the header, preference saved to `localStorage`
- **EN / PL language toggle** — full bilingual content, saved to `localStorage`
- **Animated dot background** — reacts to cursor position
- **Smooth accordions** — project cards expand/collapse with CSS transitions
- **PDF viewer modal** — project reports open inline without leaving the page
- **Scroll reveal animations** — sections animate in as they enter the viewport
- **Credly badge embed** — live certification badges in the hero section
- **Fully responsive** — works on desktop and mobile

---

## Tech stack

| Layer | Choice |
|-------|--------|
| Markup | HTML5 (single file) |
| Styling | Pure CSS with custom properties (CSS variables) |
| Scripting | Vanilla JavaScript |
| Fonts | Inter (UI), Fira Code (headings) — Google Fonts |
| Badges | Credly embed |
| Hosting | GitHub Pages |

---

## Page structure

```
Hero            — intro, trait chips, CTA links, Credly badges
My Projects     — personal engineering projects
Cybersecurity   — 6 academic security project write-ups (with PDF reports)
Certificates    — CompTIA Security+, Cisco Network Security
Contact         — email, LinkedIn, TryHackMe, GitHub
```

---

## Projects

### Personal

| Project | Stack | Description |
|---------|-------|-------------|
| [Mini Gauge – Hyundai Coupé](https://github.com/JakubSx01/Mini_gauge_Hyundai_coupe) | ESP32, C/C++, LVGL, CAN bus | Custom embedded gauge replacing the OEM factory display after a 2DIN radio upgrade |
| [MyCarWallet](https://github.com/JakubSx01/MyCarWallet) | Flutter, SQLite, Google ML Kit | Offline-first Android app for tracking vehicle fuel, expenses and maintenance |

### Cybersecurity (academic)

- File Upload Vulnerabilities — penetration testing & defense
- Behavioural Biometrics — keystroke dynamics with ML classifiers (AUC ~0.81)
- MITM Security Audit — ARP Poisoning, DNS Spoofing, SSLStrip
- PlantCare App — OWASP Top 10 audit with OWASP ZAP
- Cloud SSO — Authentik with OIDC/SAML on Azure
- Web Fuzzing — content discovery with ffuf vs wfuzz vs DirBuster

---

## Running locally

No build step required. Just open `index.html` in any modern browser.

```bash
git clone https://github.com/JakubSx01/JakubSx01.github.io.git
cd JakubSx01.github.io
# open index.html
```

---

## Contact

- **Email:** sjakubskrzynecki@gmail.com
- **LinkedIn:** [jakub-skrzynecki-f0r-vv0rk](https://www.linkedin.com/in/jakub-skrzynecki-f0r-vv0rk/)
- **TryHackMe:** [CyberhelperJS](https://tryhackme.com/p/CyberhelperJS)
- **GitHub:** [JakubSx01](https://github.com/JakubSx01)
