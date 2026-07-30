# Crystal Clean Website

A responsive, premium-style front-end website for Crystal Clean Cleaning Service.

## Stack
- HTML5
- SCSS
- Vanilla JavaScript
- Google Fonts

## Structure

```text
crystal-clean-website/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── main.css
    ├── js/
    │   └── main.js
    ├── images/
    └── scss/
        ├── _variables.scss
        ├── _mixins.scss
        └── main.scss
```

## Run locally

The website can be opened directly by opening `index.html` in a browser.

For SCSS development, install Sass:

```bash
npm install -g sass
```

Then compile SCSS:

```bash
sass assets/scss/main.scss assets/css/main.css --watch
```

For a production build:

```bash
sass assets/scss/main.scss assets/css/main.css --style=compressed
```

## Replacing images

Put your real images in:

```text
assets/images/
```

Then replace the placeholder `<div class="image-placeholder ...">` elements in `index.html` with normal image elements or background images.

Suggested files:
- `hero-cleaning.jpg`
- `about-team.jpg`
- `project-1.jpg`
- `project-2.jpg`
- `project-3.jpg`
- `project-4.jpg`
- `project-5.jpg`
- `project-6.jpg`

## Business details included

Crystal Clean
Sparkling space, Happy faces

13B Abeokuta Road, Ijebu-Ode, Ogun State

Phone:
0906 600 5298
0901 361 5835

WhatsApp:
0808 559 6898

Update these details in `index.html` if your official business contact information changes.
