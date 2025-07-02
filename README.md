# monosharp-icons

A minimalist SVG icon system showcasing consistent stroke styling and built-in accessibility. Perfect for theming and easy integration into any web UI.

## Extended Description

monosharp-icons provides a set of four essential icons hand-coded as lightweight SVGs. Each icon uses `stroke="currentColor"` so you can inherit color from CSS, and includes a `<title>` plus `role="img"` to ensure screen readers announce their meaning. The demo page uses Tailwind’s grid utilities to showcase how these icons scale and color-shift in different contexts.

## Features
- Lean, hand-written SVGs with no extra metadata  
- `currentColor` strokes for seamless theming  
- `<title>` tags and `role="img"` for accessibility  
- Demo page illustrating usage and label pairing  

## File Structure
- **arrow-left.svg**  
  Left arrow icon, ideal for “back” actions.  
- **check-circle.svg**  
  Circle with checkmark, for success states.  
- **eye.svg**  
  Eye outline, for view-toggle controls.  
- **trash.svg**  
  Trash can, for delete actions.  
- **index.html**  
  Demo page displaying all icons with labels, styled via Tailwind.  
- **README.md**  
  Documentation (this file) with system overview, features, file breakdown, and tools used.

## Tools Used
- HTML5  
- Tailwind CSS (via CDN)

## Author
Andrew Hueston
## Live Demo
[https://andhues.github.io/monosharp-icons](https://andhues.github.io/monosharp-icons/)
