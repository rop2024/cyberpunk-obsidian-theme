# Neon Overdrive

A dark cyberpunk theme for [Obsidian](https://obsidian.md/) featuring neon accents, cut-corner panels, terminal-inspired typography, and high-contrast headings.

![Neon Overdrive theme overview](screenshots/Screenshot%201.png)

## Highlights

- Cyber Yellow neon palette with cyan and magenta accents
- Synthwave, Matrix Green, and Amber CRT palette presets
- Distinct H1-H6 heading treatments
- Cut-corner HUD-style tabs, panels, callouts, modals, and controls
- Styled editor, properties, file explorer, calendar, graph, canvas, and community pages
- Embedded JetBrains Mono fonts with multilingual fallback fonts
- Optional block caret, scanlines, glow, motion, and boot-flicker effects
- Reduced visual effects on mobile for better performance

## Screenshots

### Editor and interface

![Neon Overdrive editor, sidebar, outline, calendar, and graph](screenshots/Screenshot%201.png)

### Reading and formatting

![Neon Overdrive text formatting and Markdown elements](screenshots/Screenshot%202.png)

## Installation

### From Obsidian

1. Open **Settings** in Obsidian.
2. Select **Appearance**.
3. Open **Manage** next to **Themes**.
4. Search for **Neon Overdrive**.
5. Select **Install and use**.

### Manual installation

1. Download `manifest.json` and `theme.css` from the latest [GitHub release](https://github.com/rop2024/cyberpunk-obsidian-theme/releases).
2. Create a folder named `neon-overdrive` inside your vault's `.obsidian/themes/` directory.
3. Copy `manifest.json` and `theme.css` into that folder.
4. Open **Settings → Appearance** and select **Neon Overdrive** as the theme.

## Customization

Install the community plugin **Style Settings** to customize the theme:

- Palette preset: Cyber Yellow, Synthwave, Matrix Green, or Amber CRT
- Heading bezel size
- Flat corners
- Calm bold text
- Block caret
- Sans-serif prose font
- Glow, animation, and scanline effects
- Boot flicker
- High-contrast text and borders
- Heavy effects on mobile

## Compatibility

- Obsidian version: `1.10.6` or newer
- Theme mode: dark
- Platforms: desktop and mobile

## Development

Clone the repository and run:

```bash
npm install
npm run lint
```

The theme styles are maintained in [theme.css](theme.css), with theme metadata in [manifest.json](manifest.json).

## License

See [LICENSE](LICENSE).
