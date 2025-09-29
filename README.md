# @textflyer/ui-theme

TextFlyer unified dark theme and focus styles (buildless CSS).

## Installation

```bash
npm install @textflyer/ui-theme
```

## Usage

Import the theme CSS file in your application:

```css
@import "@textflyer/ui-theme/styles/theme-base.css";
```

Or in JavaScript/TypeScript:

```js
import "@textflyer/ui-theme/styles/theme-base.css";
```

## What's Included

- **CSS Variables**: Core dark theme tokens (`--tx-bg`, `--tx-surface`, `--tx-card`, `--tx-border`, `--tx-fg`, `--tx-accent`)
- **Base Typography**: Responsive headings and text styles
- **Surface Elements**: Consistent styling for cards, panels, sidebars
- **Enhanced Focus**: Accessible keyboard navigation with visible focus rings
- **Form Elements**: Styled inputs, buttons, and form controls
- **Command Palette**: Overlay and dialog element styling

## CSS Variables Reference

```css
:root {
  /* Core Colors */
  --tx-bg: #0e0f12;        /* Main background */
  --tx-surface: #15171c;   /* Sidebar/surface background */
  --tx-card: #1a1d23;      /* Card/panel background */
  --tx-border: #2a2f38;    /* Border color */

  /* Text Colors */
  --tx-fg: #e8e8ec;        /* Primary text */
  --tx-fg-muted: #a0a0af;  /* Muted text */

  /* Accent */
  --tx-accent: #5a93e6;    /* Accent/focus color */

  /* Layout */
  --tx-base: 17px;         /* Base font size */
  --tx-line: 1.65;         /* Line height */
  --tx-maxw: 980px;        /* Max container width */
  --tx-pad: clamp(12px, 3vw, 24px); /* Responsive padding */
}
```

## Features

- **Build-less**: Pure CSS, no compilation required
- **Accessible**: Enhanced focus visibility for keyboard navigation
- **Responsive**: Fluid typography and spacing
- **Dark Theme**: Optimized for dark interfaces
- **Consistent**: Unified styling across all TextFlyer applications

## License

MIT