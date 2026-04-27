# Tooltip Navigation UI

A clean and responsive navigation interface built with semantic HTML and modern CSS. The navigation bar includes hover tooltips for each item, positioned above the link with smooth transition effects and a professional SaaS-style appearance.

## Overview

- Responsive layout using Flexbox
- Tooltip display on hover without JavaScript
- Centered tooltip placement with a downward arrow
- Smooth fade and slide animation for tooltip reveal
- Active navigation item styling and hover effects
- Designed for desktop, tablet, and mobile screens

## Files

- `index.html` — semantic markup for the navigation bar and hero section
- `styles.css` — styling for layout, responsive design, tooltip behavior, and animations

## Features

- Fixed navigation structure with at least five navigation items
- Hover-to-show tooltip behavior using CSS only
- Tooltip transitions implemented with `opacity`, `transform`, and `visibility`
- Minimal and professional palette, consistent spacing, and readable typography
- Google Fonts integration for modern typography

## Usage

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project directory:

```bash
cd "ToolTip System"
```

3. Open `index.html` in a browser to preview the navigation UI.

## Git workflow recommendations

- Create a feature branch for updates:

```bash
git checkout -b feature/tooltip-navigation
```

- Stage and commit changes with clear messages:

```bash
git add index.html styles.css README.md
git commit -m "Add responsive tooltip navigation UI and documentation"
```

- Merge back into the main branch after review:

```bash
git checkout main
git merge feature/tooltip-navigation
git push
```

## Notes

This project is intentionally built without JavaScript, relying solely on HTML and CSS for interactive tooltip behavior and responsive presentation.