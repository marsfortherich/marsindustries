# Mars Industries Website

Official website for Mars Industries game development studio, hosted at [marsindustries.dev](https://marsindustries.dev).

## Structure

```
marsindustries/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styles
├── js/
│   └── main.js         # JavaScript functionality
├── images/
│   └── favicon.svg     # Site favicon
└── README.md           # This file
```

## Features

- Responsive design that works on all devices
- Animated starfield background
- Mars planet animation
- Smooth scrolling navigation
- Interactive project cards with 3D hover effects
- Modern, space-themed design

## Projects

The website links to game projects hosted on subdomains:

- **Gacha Game Company Simulator**: [gachagamecompanysimulator.marsindustries.dev](https://gachagamecompanysimulator.marsindustries.dev)

## Deployment

This is a static website that can be deployed to any static hosting provider:

### GitHub Pages
1. Push to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Configure custom domain to `marsindustries.dev`

### Netlify
1. Connect your GitHub repository
2. Set publish directory to root (`/`)
3. Configure custom domain

### Vercel
1. Import your GitHub repository
2. Deploy (no configuration needed)
3. Add custom domain

## Adding New Projects

To add a new project, add a new project card in `index.html` within the `.projects-grid` section:

```html
<a href="https://yourproject.marsindustries.dev" class="project-card" target="_blank" rel="noopener">
    <div class="project-image">
        <div class="project-placeholder">
            <span class="project-emoji">🎮</span>
        </div>
    </div>
    <div class="project-info">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">Description of your project.</p>
        <span class="project-link">Play Now →</span>
    </div>
</a>
```

## Customization

### Colors
Edit the CSS variables in `css/styles.css`:

```css
:root {
    --color-primary: #e94560;    /* Main accent color */
    --color-accent: #ff6b35;     /* Secondary accent */
    --color-bg: #0a0a0f;         /* Background color */
    /* ... */
}
```

### Fonts
The site uses Google Fonts:
- **Orbitron** - For headings and display text
- **Inter** - For body text

## License

© 2025 Mars Industries. All rights reserved.
