# Afif Zunnur Wahid — Portfolio

Personal portfolio website built with vanilla HTML, CSS, and JavaScript.

## Structure
```
portfolio-site/
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── img/
│       └── (images)
├── .gitignore
└── README.md
```

## Features
- **Dark theme** with acid-green accent
- **Smooth scroll reveal** animations (IntersectionObserver)
- **Marquee ticker** for continuous motion
- **Responsive** grid layouts, mobile nav drawer
- **prefers-reduced-motion** support
- **Zero dependencies** — no build step required

## Development
Open `index.html` directly in a browser, or serve locally:

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve .
```

## Customization
- Edit `index.html` for content
- Modify CSS tokens in `assets/css/style.css` (`:root` block)
- Add interactions in `assets/js/main.js`

## Deploy
Any static host works: GitHub Pages, Netlify, Vercel, Cloudflare Pages, etc.

## License
MIT — use freely, attribution appreciated.