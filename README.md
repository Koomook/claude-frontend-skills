# Claude Frontend Skills

A Claude Code skills plugin for creating distinctive, non-generic frontend designs. This plugin helps Claude avoid "AI slop" aesthetics (generic Inter fonts, purple gradients, minimal animations) and instead create bold, memorable interfaces.

## Features

The **Distinctive Frontend** skill applies a four-dimensional approach to frontend design:

1. **Typography** - Use extreme font weights (100-200 vs 800-900) and distinctive font pairings
2. **Color & Theme** - Cohesive color systems based on cultural references (Cyberpunk, Brutalist, Vaporwave, Nordic)
3. **Motion** - Orchestrated page-load animations with staggered reveals
4. **Backgrounds** - Layered gradients, textures, and atmospheric depth

## Installation

### Via npm

```bash
npm install -g @bong/claude-frontend-skills
```

### Manual Installation

1. Clone this repository:
```bash
git clone https://github.com/Koomook/claude-frontend-skills.git
```

2. Install the plugin in your Claude Code skills directory:
```bash
cp -r claude-frontend-skills/skills/* ~/.claude/skills/
```

Or on Windows:
```bash
xcopy claude-frontend-skills\skills %USERPROFILE%\.claude\skills\ /E /I
```

## Usage

Once installed, Claude Code will automatically have access to the `distinctive-frontend` skill. The skill activates when you:

- Ask Claude to create a landing page, marketing site, or portfolio
- Request "modern", "distinctive", or "eye-catching" design
- Build dashboards or web applications where aesthetics matter
- Want to avoid generic-looking interfaces

### Example Prompts

```
Create a landing page for a tech startup with a cyberpunk aesthetic
```

```
Build a portfolio site with bold typography and distinctive design
```

```
Make a dashboard with Nordic minimalism theme and smooth animations
```

## What You Get

### Design Patterns

- **Typography Systems**: Pre-configured font pairings with extreme weight contrasts
- **Theme Templates**: 4+ ready-to-use themes (Cyberpunk, Brutalist, Vaporwave, Nordic)
- **Animation Patterns**: Staggered reveal animations with smooth easing
- **Background Recipes**: Gradient meshes, noise textures, and grid patterns

### Code Templates

The skill includes:
- Complete CSS custom property systems
- HTML/CSS quick start templates
- React/Framer Motion examples
- Responsive design patterns
- Accessibility considerations

### Anti-Patterns Checklist

Claude will actively avoid:
- ❌ Inter or Roboto as primary fonts
- ❌ Safe font weights (400, 500, 600)
- ❌ Generic purple-blue gradients
- ❌ No page-load animations
- ❌ Flat white/gray backgrounds
- ❌ Low-contrast pastel colors

## Skills Included

### `distinctive-frontend`

Creates interfaces with strong visual identity using:

**Typography Examples:**
- Display: Space Grotesk 900 weight
- Body: Inter 200 weight
- Serif option: Playfair Display + Source Sans 3

**Theme Examples:**
- Cyberpunk (Blade Runner inspired)
- Brutalist (Raw concrete aesthetic)
- Vaporwave (80s/90s retro)
- Nordic Minimalism (Nord palette)

**Motion Patterns:**
- Fade-in with translateY
- Staggered delays (0.1s increments)
- Scale-in for hero elements
- Smooth cubic-bezier easing

**Background Techniques:**
- Radial gradient overlays
- Mesh gradients (multi-layered)
- SVG noise texture
- Grid patterns

## Examples

### Quick Start Template

The skill provides a complete HTML template you can use immediately:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Cyberpunk-themed page with extreme typography and staggered animations -->
  <!-- Includes: Space Grotesk 900 + Inter 200, gradient backgrounds, fade-in motion -->
</head>
<body>
  <main>
    <h1 class="fade-in stagger-1">Bold Headline</h1>
    <p class="fade-in stagger-2">Light body text</p>
    <button class="cta fade-in stagger-3">Call to Action</button>
  </main>
</body>
</html>
```

### Theme Customization

All themes use CSS custom properties for easy customization:

```css
:root {
  --font-display: 'Space Grotesk', sans-serif;
  --font-body: 'Inter', sans-serif;
  --weight-light: 200;
  --weight-black: 900;

  --bg-primary: #0a0e27;
  --accent-1: #ff2e97;
  --accent-2: #00d9ff;
  --text-primary: #e4f1ff;
}
```

## Inspiration

This plugin is based on Anthropic's blog post ["Improving Frontend Design Through Skills"](https://www.claude.com/blog/improving-frontend-design-through-skills), which identifies how to overcome distributional convergence in AI-generated designs.

The core insight: AI models default to "safe" design choices from training data. Skills provide specialized context on-demand, enabling Claude to make bold, distinctive design decisions.

## Use Cases

Perfect for:
- 🚀 **Landing Pages** - High-impact hero sections with staggered animations
- 💼 **Portfolios** - Distinctive personal branding
- 📊 **Dashboards** - Professional interfaces with clear visual hierarchy
- 🎨 **Marketing Sites** - Bold aesthetics that stand out
- 🎮 **Web Apps** - Cohesive themes with strong identity

## Requirements

- Claude Code (latest version)
- Modern browser with CSS custom properties support
- Google Fonts access (or local font files)

## Contributing

Contributions welcome! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-theme`)
3. Add your theme or pattern to the skill file
4. Update documentation
5. Submit a pull request

### Ideas for Contributions

- New theme palettes (e.g., Solarized, Dracula, Monokai)
- Animation patterns (e.g., scroll-triggered, parallax)
- Component examples (e.g., cards, navigation, forms)
- Framework-specific templates (Vue, Svelte, Angular)

## License

MIT License - see [LICENSE](LICENSE) file for details

## Links

- [GitHub Repository](https://github.com/Koomook/claude-frontend-skills)
- [npm Package](https://www.npmjs.com/package/@bong/claude-frontend-skills)
- [Issue Tracker](https://github.com/Koomook/claude-frontend-skills/issues)
- [Anthropic Blog Post](https://www.claude.com/blog/improving-frontend-design-through-skills)

## Support

- 📧 Open an issue on GitHub
- 💬 Discussions tab for questions and ideas
- ⭐ Star the repo if you find it useful!

---

Made with ❤️ for the Claude Code community
