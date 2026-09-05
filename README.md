# 🔗 Link Tree — Terminal Dashboard Theme

A dark, terminal/dashboard-styled link-in-bio page. Built as a fast, static single-page site — no frameworks, no build steps. Use this as a template: swap the placeholders for your own name, links and socials.

🌐 **Live:** [kechilab.io](https://kechilab.io)

---

## ✨ Features

- **Dashboard UI** — Dark, terminal-inspired panel layout with a red accent
- **Responsive Design** — Optimized for mobile, tablet, and desktop
- **Social Links** — YouTube, Kick, GitHub with branded hover effects (easy to add/remove)
- **SEO & Open Graph** — Meta tags and social share preview configured
- **PWA-Ready** — Includes web manifest and full favicon set

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Markup | HTML5 (Semantic) |
| Styling | Vanilla CSS3 (Flexbox, Media Queries) |
| Typography | System monospace (`Courier New`) + `Arial` |
| Icons | [Font Awesome 6](https://fontawesome.com/) |

---

## 📁 Project Structure

```
link-tree-source/
├── index.html              # Main page — edit the marked section for your content
├── css/
│   └── styles.css          # All styles
├── images/
│   └── favicon/            # Full favicon set + web manifest
├── LICENSE
├── .gitignore
├── .gitattributes
└── README.md
```

---

## 🚀 Getting Started

No build tools or servers required — just open `index.html` in your browser.

```bash
git clone https://github.com/selimunsel/link-tree-source.git
```

---

## 🌍 Deployment

This is a fully static site. You can deploy it anywhere:

- **GitHub Pages** — Push to `main` and enable Pages in repo settings
- **Cloudflare Pages / Netlify / Vercel** — Connect the repo for auto-deploy
- **Traditional Hosting** — Upload all files via FTP/SFTP

---

## 🎨 Customization

`index.html` has an `EDIT BELOW` comment marking the block to personalize. Replace every placeholder before deploying:

| Placeholder | Where | Replace with |
|---|---|---|
| `YOUR NAME` | `<title>`, meta tags, `.brand`, `.ft` | Your display name |
| `https://your-domain.com/` | `og:url`, `og:image`, `twitter:image`, canonical | Your live domain |
| `PROJECT ONE` / `PROJECT TWO` + `https://your-link-1.com` / `-2.com` | `LINKS` panel | Your own project links |
| `your@email.com` | `LINKS` panel | Your contact email |
| `yourhandle` (YouTube / Kick / GitHub URLs) | `SOCIALS` panel | Your social handles |
| `v1.0.0` | `.badge` | Your own version tag, or delete |
| `Kechifikasion` name fields | `images/favicon/site.webmanifest` | Your app/site name |

> **Note:** `og:image` / `twitter:image` currently point to `android-chrome-512x512.png` as a placeholder. For a proper social share preview, add a dedicated 1200×630 image (e.g. `images/og-image.jpg`) and update those two meta tags.

Colors, spacing and hover effects live in `css/styles.css` (`:root` variables at the top control the palette).

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">
  Made with ☕ by <a href="https://github.com/selimunsel">Ahmet Selim ÜNSEL</a>
</p>
