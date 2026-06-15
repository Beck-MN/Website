# beckchristensen.dev

Personal portfolio website for Charles Beck Christensen — software engineering graduate, audio engineer, and radio host. Built with vanilla HTML, CSS, and minimal JavaScript. No frameworks, no build step.

## Stack

- HTML5 (semantic markup)
- CSS3 (custom properties, grid, flexbox, clamp-based fluid type)
- Vanilla JS (dropdown menu toggle only)
- Martian Mono via Google Fonts
- Netlify (deployment)

## Structure

```
/
  index.html        — all content and markup
  styles.css        — all styles
  pics/             — project screenshots and personal photos
  docs/             — resume PDF
  netlify.toml      — Netlify deployment config
```

## Customization

CSS variables are defined at the top of `styles.css`:

```css
:root {
  --bg: #151312;
  --paper: #faf7f3;
  --muted: #aaa19d;
  --line: rgba(250, 247, 243, 0.16);
  --accent: #d67fd6;
  --max: 1180px;
  --font-mono: "Martian Mono", ui-monospace, monospace;
}
```

## Contact

Beck Christensen — [beck.christensen@gmail.com](mailto:beck.christensen@gmail.com)

GitHub: [Beck-MN/Website](https://github.com/Beck-MN/Website)
