# Animated Landing Page

A creative and interactive landing page featuring an animated desk scene with a working clock and character animations.

## Description

This project showcases a stylized desk setup scene created entirely with HTML and CSS animations. It includes various animated elements such as:
- Animated human character
- Working clock with moving hands
- Monitor with LCD light effect
- Complete desk setup with chair and computer

## Technologies Used

- HTML5
- CSS3/SCSS
  - CSS Animations
  - SCSS for better CSS organization
- JavaScript
  - Animation management
  - Window resize handling

## Features

- Responsive design
- Smooth CSS animations
- Auto-resetting animations on window resize
- Interactive elements
- SVG integration

## Project Structure

```
.
├── index.html                    # Main HTML file
└── assets/                      # Asset directories
    ├── css/
    │   ├── style.scss          # SCSS source file
    │   └── style.css          # Compiled CSS
    ├── img/
    │   └── lugon.svg          # Logo/branding SVG
    └── js/
        └── main.js            # JavaScript for animation control
```

## Setup

1. Clone the repository:
```bash
git clone <repository-url>
```

2. Open `index.html` in a modern web browser:
```bash
open index.html
```

No build steps or dependencies are required to run the project. The page should work immediately in any modern web browser.

## Development

If you want to modify the SCSS:

1. Install a SASS compiler
2. Watch the SCSS file for changes:
```bash
sass --watch assets/css/style.scss:assets/css/style.css
```

## Browser Support

The landing page is compatible with all modern browsers that support CSS animations and modern JavaScript (ES6+).
