# Arjungopal Anilkumar — Portfolio

Personal portfolio website for Arjungopal Anilkumar, AI/ML Engineer specialising in LLMs, NLP pipelines, and cloud-deployed deep learning systems.

**Live site →** [arjungop.github.io](https://arjungop.github.io) *(or your CNAME domain)*

---

## Tech Stack

| Concern | Technology |
|---------|-----------|
| Structure | Semantic HTML5 |
| Styling | Vanilla CSS (no framework) |
| Smooth scroll | [Lenis](https://github.com/darkroomengineering/lenis) `1.1.20` |
| Animations | [GSAP](https://gsap.com/) `3.12.5` + ScrollTrigger |
| Fonts | Raleway (headings) · DM Sans (body) via Google Fonts |
| Image format | WebP (profile, compressed ≤150 KB) |

---

## Project Structure

```
porfolio_arj/
├── index.html          # Single-page portfolio
├── profile.webp        # Optimised portrait (700 × 808 px, ≤150 KB)
├── favicon-512.png     # 512 × 512 square app icon / apple-touch-icon
├── website.png         # OG social-share image
├── Arjungopal Anilkumar_Doc.pdf  # Résumé download
├── CNAME               # GitHub Pages custom domain
├── README.md           # This file
└── LICENSE             # MIT License
```

---

## Local Development

No build step required — open `index.html` directly in a browser, or serve with any static server:

```bash
# Python (built-in)
python3 -m http.server 8080

# Node
npx serve .
```

---

## Sections

1. **Home** — Hero with profile image, intro, and CTA buttons
2. **Skills** — Pill-tag groups: LLMs & GenAI · Deep Learning · Infrastructure
3. **Experience** — Timeline of work and leadership roles
4. **Projects** — GitHub repo cards with live spotlight effect
5. **Credentials** — Industry certifications (Columbia+, IBM, Forage, LinkedIn)
6. **Contact** — Email + social links

---

## Performance Notes

- Profile image served as **WebP** (700 px wide, ~76 KB) with explicit `width`/`height` to prevent layout shift.
- ScrollTrigger hero pin is **desktop-only** (`min-width: 861px`) via `ScrollTrigger.matchMedia`.
- Text-scramble effect runs only on the copyright line — never on critical readable content (name / role).

---

## License

MIT © 2025 Arjungopal Anilkumar
