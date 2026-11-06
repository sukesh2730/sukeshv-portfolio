# Sukesh V — Portfolio

Personal portfolio showcasing AI/ML projects, full-stack applications, research work, and professional experience.

**Live:** TBD &nbsp;|&nbsp; **GitHub:** [sukesh2730/sukeshv-portfolio](https://github.com/sukesh2730/sukeshv-portfolio)

---

## About

I'm Sukesh V, a B.Tech AI & Machine Learning student at Sri Ramachandra Institute of Higher Education and Research (2024-2028), building real AI systems across healthcare risk models, computer vision, quantum ML, RAG, algorithmic trading, and production SaaS platforms.

This portfolio showcases my engineering work — from full-stack web applications to quantum fraud detection, from mobile AI apps to production deployments.

---

## Tech Stack

| Layer      | Technology                                       |
| ---------- | ------------------------------------------------ |
| Framework  | Next.js 16.2 (App Router, React Compiler)        |
| Animations | GSAP 3 + Three.js                                |
| Styling    | CSS Modules + Tailwind v4                        |
| Icons      | react-icons                                      |
| Fonts      | Geist, Baloo 2, Dancing Script (via next/font)   |

---

## Getting Started

```bash
git clone https://github.com/sukesh2730/sukeshv-portfolio.git
cd sukeshv-portfolio
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see the portfolio locally.

To build for production:

```bash
npm run build
npm start
```

---

## Portfolio Structure

All personal content is managed through JSON files for easy updates:

### `data/profile.json`

Contains all personal information:

- **Personal Info**: Name, email, tagline, bio, location
- **Professional**: Roles, skills, stats
- **Experience**: Work history with companies, roles, projects, tech stack
- **Projects**: Portfolio projects with descriptions, tech stack, and links
- **Publications**: Research papers, blog posts, articles
- **Social Links**: GitHub, LinkedIn, etc.

### `data/content.json`

Contains website copy (section taglines, CTA text, footer phrases).

### `app/globals.css`

Design tokens and color scheme. Edit CSS custom properties under `:root` to change colors:
- `--accent`, `--hero-start`, `--hero-mid`, `--hero-end`, `--text-primary`

### `lib/siteConfig.js`

Site configuration including base URL for metadata and SEO.

---

## Assets

Images and videos are stored in `public/assets/`:

| Asset                  | Usage                     | Description                            |
| ---------------------- | ------------------------- | -------------------------------------- |
| `intro video.mp4`      | Video Intro               | Full-screen intro video                |
| `hero.jpeg`            | Hero Section              | Professional headshot                  |
| `about.png`            | About Section, OG Image   | About section photo and SEO image      |
| `CQMS RANK IN NCC.png` | Work Experience           | NCC CQMS rank achievement photo        |
| `footer.png`           | Footer Section            | Footer transition image                |
| `footer-mobile.webp`   | Footer (mobile)           | Static mobile footer background        |
| `footer-video.mp4`     | Footer (desktop)          | Looping footer background video        |
| `project-*.png`        | Projects Section          | One image per project                  |

---

## Featured Projects

### 🚀 Recent Projects

1. **IdeaBuddy** — Full-stack idea management web app (Node.js, Express, MongoDB, JWT)
2. **TaskFlow AI** — AI-powered mobile productivity app (Flutter, Dart, GitHub Actions)
3. **Quantum Fraud Detection** — Quantum ML model using PennyLane VQC (93% precision)
4. **ROME JARVIS** — Personal AI coding assistant with voice input and 4-tier fallback system

### 🔬 AI/ML Research

- **AeroSight** — Prophet + XGBoost dual-model AQI/mortality forecasting (2nd place, Research Day 2025)
- **Pollumap V3** — Real-time air quality dashboard with XGBoost forecasts and healthy routing
- **Market Oracle** — Commodity price forecasting ensemble for Mitsui Challenge
- **EcoSynth** — Neuro-symbolic green retrosynthesis planner with RAG

### 💼 Professional Work

- **ASPCV CRM** — Full-stack CRM for cleantech company (MERN stack, role-based access)
- **Aspiration Cleantech Academy** — Training platform (Next.js, Express, MongoDB)
- **Aspiration Cleantech Ventures** — Production web app for solar energy company

---

## Deployment

### Vercel (Recommended)

1. Push your repository to GitHub
2. Connect to [Vercel](https://vercel.com)
3. Import repository and deploy (zero config needed)

Alternatively, use Vercel CLI:

```bash
npm i -g vercel
vercel
```

### Cloudflare Workers

```bash
npm run deploy
```

---

## License

MIT License — feel free to fork and use this portfolio template for your own work.

---

## Contact

**Sukesh V**  
B.Tech AI & Machine Learning  
Sri Ramachandra Institute of Higher Education and Research

📧 sukeshkavin@gmail.com  
🔗 [GitHub](https://github.com/sukesh2730) | [LinkedIn](https://www.linkedin.com/in/r-jeyadev)

---

Built with Next.js 16, GSAP, Three.js, and modern web technologies.
