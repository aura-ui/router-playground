# Aura Router Playground

Minimal MPA demo for [`@auraui/router`](https://www.npmjs.com/package/@auraui/router): two complete HTML pages, `extract="#content"`, and client navigation after install.

- Library: [aura-ui/router](https://github.com/aura-ui/router)
- Hosted demo: [aura-ui.github.io/router-preview](https://aura-ui.github.io/router-preview/)
- Open in StackBlitz: [stackblitz.com/github/aura-ui/router-playground](https://stackblitz.com/github/aura-ui/router-playground)
- Article: [Why I Built an SPA Router for HTML and Web Components](https://dev.to/aura-ui/why-i-built-an-spa-router-for-html-and-web-components-25dm)

## Run locally

```bash
npm install
npm run dev
```

1. Open Home.
2. Click **About** — only `#content` updates (no full reload).
3. Hard-reload `/about/` — the page still works as normal HTML.

## Layout

```
index.html          Home page + router
about/index.html    About page + same router
src/main.js         AuraRouter.install()
src/style.css       Minimal styles
vite.config.js      Vite MPA entries
```
