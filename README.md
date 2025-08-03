# Redirect Mechanism

A beautiful, animated redirect page with JSON-based configuration. Perfect for domain redirects, maintenance pages, or temporary landing pages.

![Sleek Redirect Preview](https://raw.githubusercontent.com/rajatrajputdev/redirect-mechanism/refs/heads/main/demo.png)

## Features

-  **Modern Dark Theme** - Glassmorphism design with animated particles
-  **JSON Configuration** - Easy setup without touching code
-  **Customizable Countdown** - Set your own redirect delay
-  **Fully Responsive** - Works perfectly on all devices
-  **Keyboard Shortcuts** - Enter/Space to redirect, Escape to cancel
-  **Smooth Animations** - Progress bars, particles, and transitions
-  **Error Handling** - Clear messages when configuration fails
-  **Zero Dependencies** - Single HTML file, no external libraries

## Quick Start

1. **Download** or clone this repository
2. **Edit** `redirect-config.json` with your settings
3. **Upload** both files to your web server
4. **Done!** Your redirect page is ready

## File Structure

```
redirect-mechanism/
├── index.html           # Main redirect page
├── redirect-config.json # Configuration file
└── README.md            # This file
```

## Configuration

Edit `redirect-config.json` to customize your redirect:

```json
{
  "url": "https://your-destination.com",
  "delay": 5,
  "title": "Redirecting to My Site",
  "subtitle": "Taking you to an awesome destination...",
  "logo": "🌟",
  "showDestination": true,
  "theme": {
    "background": "linear-gradient(135deg, #0f0f0f 0%, #1a1a1a 50%, #0a0a0a 100%)",
    "accentColor": "#00ff95"
  }
}
```

### Configuration Options

| Option | Type | Required | Default | Description |
|--------|------|----------|---------|-------------|
| `url` | string | ✅ Yes | - | Destination URL for redirect |
| `delay` | number | ❌ No | `5` | Countdown time in seconds |
| `title` | string | ❌ No | `"Redirecting..."` | Main heading text |
| `subtitle` | string | ❌ No | `"Taking you to your destination"` | Subtitle text |
| `logo` | string | ❌ No | `"🚀"` | Emoji or text for logo |
| `showDestination` | boolean | ❌ No | `true` | Whether to show destination URL |
| `theme.background` | string | ❌ No | - | CSS background property |
| `theme.accentColor` | string | ❌ No | `"#00ff95"` | Primary accent color |

## Themes

### Cyberpunk (Default)
```json
{
  "theme": {
    "background": "linear-gradient(135deg, #0f0f0f 0%, #1a1a1a 50%, #0a0a0a 100%)",
    "accentColor": "#00ff95"
  }
}
```

### Ocean Blue
```json
{
  "theme": {
    "background": "linear-gradient(135deg, #1e3c72 0%, #2a5298 100%)",
    "accentColor": "#00bfff"
  }
}
```

### Sunset
```json
{
  "theme": {
    "background": "linear-gradient(135deg, #ff7e5f 0%, #feb47b 100%)",
    "accentColor": "#ff6b35"
  }
}
```

### Purple Dream
```json
{
  "theme": {
    "background": "linear-gradient(135deg, #667eea 0%, #764ba2 100%)",
    "accentColor": "#a855f7"
  }
}
```

## Keyboard Shortcuts

- **Enter** or **Space** - Redirect immediately
- **Escape** - Cancel redirect and stop countdown



## Contributing

Contributions are welcome! Feel free!

## License

MIT License - feel free to use this in your projects!

## Credits

Created with ❤️ for the developer community by [Rajat Rajput](https://github.com/rajatrajputdev/). If you find this useful, consider giving it a star!

---

**Made with modern web technologies and little bit of of coffee ☕**