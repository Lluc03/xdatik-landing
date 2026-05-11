# X-DATIK Landing

Landing comercial pública servida en [xdatik.com](https://xdatik.com).

Página estática HTML/CSS/JS, sin backend, sin build step.
Servida vía Coolify (nginx) en VPS Hetzner.

## Estructura

```
.
├── index.html       # Landing principal
├── robots.txt       # SEO
└── sitemap.xml      # SEO
```

## Deploy

Conectado a Coolify. Cualquier push a `main` despliega automáticamente.

## Stack

- HTML5 + CSS3 + JS vanilla
- Google Fonts (Barlow, Barlow Condensed, JetBrains Mono)
- Sin dependencias externas