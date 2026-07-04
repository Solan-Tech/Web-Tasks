# Catchhub — Landing Page

A pixel-close HTML/CSS recreation of the Catchhub landing page design (`design.jpg`), built with semantic HTML5, plain CSS (flexbox layout), and self-hosted Poppins web fonts — no build step, no frameworks.

## Structure

```
.
├── index.html
├── styles.css
└── assets/
    ├── logo.png, favicon.jpg
    ├── top_screens.png, sec_screens.png, thhh_screens.png, for_screens.png
    ├── vectors.png, peratude.png
    ├── app_store.png, play_store.png
    └── fonts/ (self-hosted Poppins woff2 files)
```

## Sections

1. **Hero** — logo, tagline, subtitle, store buttons, discover/profile/channels phone mockups.
2. **Channels** — video & channel mockups with supporting copy.
3. **Messages** — messaging & group chat mockups with supporting copy.
4. **In Future** — places/events/restaurant mockups, supporting copy, and category icon row.
5. **Footer** — download call-to-action, store buttons, contact link, Peratude credit.

## Run locally

Just open `index.html` in a browser, or serve statically:

```bash
npx serve .
```

## Deploy

Static site — deploy the folder as-is to Netlify or Vercel (no build command needed).
