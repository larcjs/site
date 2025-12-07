# ⚠️ REPOSITORY ARCHIVED - Moved to Monorepo

**This repository has been archived and is now maintained in the [larcjs/larc](https://github.com/larcjs/larc) monorepo.**

**New Location:** [`larcjs/larc/docs/site`](https://github.com/larcjs/larc/tree/main/docs/site)

🌐 **The live site is still active:** [https://larcjs.github.io/larc/docs/site/](https://larcjs.github.io/larc/docs/site/)

---

## 🔄 Migration Information

- **Date:** December 6, 2025
- **Reason:** Consolidated documentation into monorepo for easier maintenance alongside code
- **Status:** This repo is read-only, all development happens in the monorepo
- **Issues/PRs:** Please open them at [larcjs/larc](https://github.com/larcjs/larc/issues)

---

# LARC Site

[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Website](https://img.shields.io/badge/website-live-brightgreen.svg)](https://larcjs.github.io/larc/docs/site/)

> **Official documentation website** and showcase for the LARC/PAN ecosystem

The central hub for LARC documentation, guides, API references, and interactive demos.

🌐 **Live Site:** [https://larcjs.github.io/larc/docs/site/](https://larcjs.github.io/larc/docs/site/)

---

## 📚 What's Inside

### Documentation
- **Getting Started Guide** — Quick introduction to LARC/PAN
- **API Reference** — Complete API documentation
- **Topic Conventions** — Message pattern guidelines
- **Architecture Guide** — System design and patterns
- **Security Best Practices** — Secure application development
- **Migration Guides** — Upgrade paths and breaking changes

### Interactive Pages
- **Component Gallery** — Visual showcase of all UI components
- **Demo Applications** — Full-featured app examples
- **Examples Index** — Categorized example browser
- **Component Registry** — Searchable component catalog
- **Theme Showcase** — Theming capabilities demonstration

### Resources
- **Roadmap** — Future plans and version goals
- **Changelog** — Version history and updates
- **Contributing Guide** — How to contribute
- **FAQ** — Frequently asked questions

---

## 🚀 Local Development

**Note:** Development now happens in the monorepo. See [larcjs/larc](https://github.com/larcjs/larc) for current setup instructions.

### Prerequisites
- Node.js 16+ (for build scripts)
- Python 3 (for local server, or use any alternative)

### Setup (Legacy - use monorepo instead)

1. **Clone the repository:**
   ```bash
   git clone https://github.com/larcjs/larc.git
   cd larc/docs/site
   ```

2. **Start local server:**
   ```bash
   python3 -m http.server 8000
   # or
   npx serve .
   ```

3. **Open in browser:**
   ```
   http://localhost:8000
   ```

---

## 📝 Documentation Files

All documentation is in plain HTML/Markdown for zero-build philosophy:

- `index.html` — Homepage
- `docs/` — Documentation pages
  - `getting-started.html`
  - `api-reference.html`
  - `architecture.html`
  - `security.html`
- `examples/` — Code examples
- `components/` — Component demos
- `assets/` — Styles and images

---

## 🌐 Deployment

The site is automatically deployed to GitHub Pages from the monorepo:
- **Source:** `larcjs/larc/docs/site`
- **URL:** https://larcjs.github.io/larc/docs/site/
- **CI:** GitHub Actions in main monorepo

---

## 🤝 Contributing

**Important:** All contributions should now be made to the monorepo.

1. Fork [larcjs/larc](https://github.com/larcjs/larc)
2. Create a feature branch
3. Make changes in `docs/site/`
4. Submit PR to the monorepo

See [CONTRIBUTING.md](https://github.com/larcjs/larc/blob/main/CONTRIBUTING.md) in the monorepo.

---

## 📦 Project Structure

```
site/ (now at larcjs/larc/docs/site/)
├── index.html          # Homepage
├── gallery.html        # Component gallery
├── examples.html       # Examples index
├── apps.html           # Demo applications
├── docs/              # Documentation
│   ├── getting-started.html
│   ├── api-reference.html
│   ├── architecture.html
│   └── ...
├── examples/          # Code examples
│   ├── basic/
│   ├── advanced/
│   └── ...
├── components/        # Component demos
├── assets/           # Styles, images
└── generate-docs.mjs # Doc generation script
```

---

## 🔗 Links

- [LARC Monorepo](https://github.com/larcjs/larc) ← **Development happens here**
- [Live Documentation](https://larcjs.github.io/larc/docs/site/)
- [LARC Core](https://github.com/larcjs/core)
- [LARC Components](https://github.com/larcjs/components)
- [Report Issues](https://github.com/larcjs/larc/issues) ← **Report issues here**

---

## 📜 License

MIT

---

## ⚡ Quick Links for Developers

- **Edit docs:** [larcjs/larc/docs/site](https://github.com/larcjs/larc/tree/main/docs/site)
- **File issues:** [larcjs/larc/issues](https://github.com/larcjs/larc/issues)
- **View live site:** [larcjs.github.io/larc/docs/site](https://larcjs.github.io/larc/docs/site/)
