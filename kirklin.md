# @kirklin/reset-css/kirklin.css

Based on [tailwind.css](./tailwind.css) with a few opinionated additions.

### Added

```css
html {
  scrollbar-gutter: stable;
}

/* Single-page applications spread across browsers */
html,
body,
#app,
#__nuxt {
    width: 100%;
    height: 100vh;
    margin: 0;
    padding: 0;
}

```
