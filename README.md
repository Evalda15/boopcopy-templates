# 🎨 BoopCopy Templates

Template collection for [BoopCopy](https://github.com/Evalda15/BoopCopy) — AI Landing Page Generator.

## 📂 Structure

```
boopcopy-templates/
├── clean-minimalist/   → Clean & minimalist designs
├── cyber-neon/         → Dark futuristic & neon themes
├── dark-luxury/        → Premium luxury aesthetics
├── editorial-mono/     → Editorial & monochrome styles
├── modern-tech/        → Modern tech & SaaS layouts
├── warm-organic/       → Warm, natural, organic feel
├── assets/             → Shared assets (logos, CSS)
└── manifest.json       → Template registry (source of truth)
```

## 🏷️ Naming Convention

| Element | Format | Example |
|---------|--------|---------|
| Folder (Theme) | `kebab-case` | `modern-tech/` |
| HTML File (Layout) | `kebab-case.html` | `saas.html` |
| Thumbnail | `[name].thumb.webp` | `saas.thumb.webp` |

## 🚀 Deployment

This repository is deployed via **Cloudflare Pages** at:
```
https://boopcopy-templates.pages.dev
```

Every `git push` to `main` triggers an automatic deployment.

## 📝 Adding a New Template

1. Create your HTML file in the appropriate theme folder
2. (Optional) Add a `.thumb.webp` screenshot alongside it
3. Update `manifest.json` with the new entry and tags
4. Commit & push — Cloudflare deploys automatically

## 📋 License

Private repository — All rights reserved.
