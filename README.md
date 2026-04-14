# 🔗 Kechifikasion Link Tree

A modern, glassmorphism-styled link-in-bio page with a looping video background. Built as a fast, static single-page site — no frameworks, no build steps.

🌐 **Live:** [tree.urbexhawks.com](https://tree.urbexhawks.com/)

---

## ✨ Features

- **Video Background** — Full-screen looping MP4 with blur & dimming overlay
- **Glassmorphism UI** — Frosted-glass cards with `backdrop-filter` blur
- **Responsive Design** — Optimized for mobile, tablet, and desktop
- **Social Links** — YouTube, Twitch, GitHub with branded hover effects
- **SEO & Open Graph** — Meta tags and social share preview configured
- **PWA-Ready** — Includes web manifest and full favicon set

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Markup | HTML5 (Semantic) |
| Styling | Vanilla CSS3 (Flexbox, Media Queries, Glassmorphism) |
| Typography | [Montserrat](https://fonts.google.com/specimen/Montserrat) via Google Fonts |
| Icons | [Font Awesome 6](https://fontawesome.com/) |

---

## 📁 Project Structure

```
link-tree/
├── index.html              # Main page
├── css/
│   └── styles.css          # All styles
├── images/
│   ├── bg-vid.mp4          # Looping background video (Git LFS)
│   ├── video-poster.jpg    # Video fallback poster & OG image
│   └── favicon/            # Full favicon set + web manifest
├── LICENSE
├── .gitignore
├── .gitattributes          # LF normalization + Git LFS rules
└── README.md
```



---

## 🚀 Getting Started

No build tools or servers required — just open `index.html` in your browser.

> **Note:** `bg-vid.mp4` is tracked via Git LFS. Make sure to install Git LFS before cloning:
> ```bash
> git lfs install
> git clone https://github.com/kechifikasion/link-tree-source.git
> ```

---

## 🌍 Deployment

This is a fully static site. You can deploy it anywhere:

- **GitHub Pages** — Push to `main` and enable Pages in repo settings
- **Cloudflare Pages / Netlify / Vercel** — Connect the repo for auto-deploy
- **Traditional Hosting** — Upload all files via FTP/SFTP

---

## 🎨 Customization

| What | Where |
|------|-------|
| Links & text | `index.html` — edit `<ul>` items inside `.link-container` |
| Colors & effects | `css/styles.css` — hover colors, blur intensity, card opacity |
| Background video | Replace `images/bg-vid.mp4` and `images/video-poster.jpg` |
| Favicon | Replace files in `images/favicon/` and update `site.webmanifest` |
| OG / SEO meta | `<head>` section in `index.html` |

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">
  Made with ☕ by <a href="https://github.com/kechifikasion">Kechifikasion</a>
</p>
