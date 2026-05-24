# mimamedia.co.uk — Mira Szalma Website

Personal channel hub for Mira Szalma. Built with plain HTML + CSS, deployed via Vercel.

## Project structure

```
mimamedia/
├── index.html          ← main page
├── css/
│   └── style.css       ← all styles
├── images/
│   ├── hero.jpg
│   ├── about-1.jpg
│   ├── about-2.jpg
│   ├── about-3.jpg
│   ├── world-budapest.jpg
│   ├── world-london.jpg
│   ├── world-daily.jpg
│   ├── gallery-1.jpg … gallery-5.jpg
└── vercel.json         ← Vercel config
```

## Replacing images

Simply replace any file in `images/` keeping the same filename, commit and push. Vercel redeploys automatically.

## Editing content

All text is in `index.html`. English text is inside `.en-block` / `.en-text` elements, Hungarian inside `.hu-block` / `.hu-text`.

## Deployment

Hosted on [Vercel](https://vercel.com) connected to this GitHub repository.  
Domain: `mimamedia.co.uk` (registered via Ionos).
