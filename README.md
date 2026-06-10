# Stria Icons - HTML Starter Kit

This is a minimal HTML starter kit for integrating Stria Icons using plain HTML, CSS Masking, or the self-executing vanilla JS replacer utility.

## Usage

Open `index.html` in your web browser.

### 1. Plain HTML / Vanilla JS Replacer
Using the lightweight self-executing script (replacer utility) via jsDelivr CDN:

```html
<script src="https://cdn.jsdelivr.net/npm/stria-icons@latest/dist/js/stria.min.js"></script>

<!-- Add elements with the data-stria attribute -->
<i data-stria="user" data-stria-style="solid"></i>
<i data-stria="home" data-stria-style="regular"></i>

<script>
  stria.replace();
</script>
```

### 2. CSS Masking
Using CSS Masking utility classes:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/stria-icons@latest/dist/css/stria.min.css">

<!-- Use the utility classes -->
<i class="stria-solid stria-user"></i>
```

## Licenses

- Code (compiler toolchain, wrappers, build scripts): MIT License
- Icon designs (SVGs in `/icons` directory): CC BY 4.0
