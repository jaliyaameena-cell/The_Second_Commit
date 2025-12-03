# 💡 IdeaWall

A simple, beautiful idea board to capture and organize your thoughts. Built with pure HTML and CSS — no JavaScript required.

## Features

- 🎨 **Cork board aesthetic** with colorful sticky notes
- 🎯 **Smooth animations** for an engaging experience
- 📱 **Fully responsive** — works on all devices
- ⚡ **Zero dependencies** — just open and use

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your browser

```
ideawall/
├── index.html    # Main HTML file
├── styles.css    # All styling
└── README.md     # You're here
```

## Adding Ideas

To add a new idea, open `index.html` and copy this template inside the `<div class="idea-wall">`:

```html
<div class="idea-card" style="--rotation: 0deg; --hue: 60;">
    <div class="pin"></div>
    <h3>Your Idea Title</h3>
    <p>Your idea description goes here.</p>
    <span class="idea-date">Dec 3, 2025</span>
</div>
```

### Customization Tips

- **rotation**: Try values between `-4deg` and `4deg` for a natural look
- **hue**: Use 0-360 for different colors:
  - `0` = Red
  - `60` = Yellow
  - `120` = Green
  - `180` = Cyan
  - `240` = Blue
  - `300` = Pink

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge).

## License

MIT — feel free to use and modify for your own projects.
