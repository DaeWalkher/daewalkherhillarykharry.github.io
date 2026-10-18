# Hillary K Harry — Portfolio

A single-page portfolio website built for my Web Development module at
Gauteng City College. Plain HTML, CSS and JavaScript — no frameworks,
no build steps, no dependencies.

## Features

- **Single-page app** — Home, Assignments, About and Contact merged into
  one `index.html` with a small hash-based router (`#home`, `#assignments`,
  `#about`, `#contact`). The browser back button and direct hash links work.
- **Liquid Glass design** — floating glass pill navigation, blurred
  translucent cards, soft shadows and rounded corners in the iOS style.
- **Static background** — a layered night-sky gradient (deep indigo base
  with soft indigo and teal glows). No video or animated wallpapers.
- **Light & dark mode** — automatic via `prefers-color-scheme`.
- **Responsive** — the glass nav collapses into a hamburger menu under 768px.
- **Accessible touches** — semantic HTML, ARIA labels, and reduced-motion
  support via `prefers-reduced-motion`.
- **Working contact form validation** — inline error messages and a success
  notice, all handled client-side.

## Project structure

```
index.html    # the whole site (markup, styles and script in one file)
assets/       # optional: PDFs for the assignment cards
```

## Running it

No tools needed. Either:

- double-click `index.html` to open it from your filesystem, or
- push the folder to GitHub Pages / any static host.

## Technologies

| Technology | Used for |
|------------|----------|
| HTML5 | Structure and semantic sections |
| CSS3 | Glass styling, layout, responsive design, theming |
| JavaScript | Hash router, mobile menu, form validation |

Built from scratch — no Bootstrap, no React, no CDNs.

---

&copy; 2026 Hillary K Harry. Web Development Assignment.
