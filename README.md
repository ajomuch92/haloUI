# Halo UI

A CSS component library inspired by Bulma's structure, but implemented with Tailwind CSS v4 and a modern, neutral visual style.

## Installation

npm install haloui

## Usage

Import the CSS into your project:

```js
@import "haloui";
```

Or include the compiled file:

```html
<link rel="stylesheet" href="node_modules/haloui/dist/haloui.css">
```

Then use the style classes:

```html
<button class="button is-primary">Button</button>
<div class="card">...</div>
<div class="columns">...</div>
```

## Included Components

- Elements: button, content, delete, icon, image, notification, progress, table, tag, title.
- Components: breadcrumb, card, dropdown, menu, message, modal, navbar, pagination, panel, tabs.
- Form: input, textarea, select, checkbox, radio, file.
- Layout: columns (grid), container, hero, section, level.
- Media object and footer.

## Customization

CSS variables are defined in :root. Override the ones you need:

:root {
  --color-primary: #4f46e5;
  --color-secondary: #64748b;
  --color-success: #10b981;
  --color-danger: #ef4444;
  /* ... */
}

## License

MIT