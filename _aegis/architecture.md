---
project: apparel-sevenplus
domain: apparel.sevenplus.jp
type: static-web
phase: launch
updated: 2026-06-18
---

# Architecture

```mermaid
mindmap
  root((apparel.sevenplus.jp))
    Frontend
      index.html
        HTML 1046 lines
        Inline CSS
        Inline JS
      assets/
        sevenplus-logo.png
        product images x4
        style images x3
        luna-single.jpg
    Hosting
      GitHub Pages
      CNAME → apparel.sevenplus.jp
    Brand
      SEVENPLUS
      電磁波対策ジュエリー
      日米特許取得 EMC技術
      Language: Japanese
```

## Key Files

| File | Role |
|------|------|
| `index.html` | Single-page site — all CSS, JS, content inline |
| `assets/` | Product & style photography + logo |
| `CNAME` | Custom domain: apparel.sevenplus.jp |

## Notes

- Single HTML file with embedded styles and scripts (no build toolchain)
- Japanese-language luxury apparel/jewelry brand site
- Static hosting via GitHub Pages
