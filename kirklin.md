# @kirklin/reset-css/kirklin.css

Based on [tailwind.css](./tailwind.css) with a few opinionated additions.

### Added

```css
html {
  scrollbar-gutter: stable;
}

button,
[type='button'],
[type='reset'],
[type='submit'] {
    -webkit-appearance: button; /* 1 */
    /*will affect the button style of most component libraries, so disable it*/
    /*background-color: transparent; !* 2 *!*/
    background-image: none; /* 2 */
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
