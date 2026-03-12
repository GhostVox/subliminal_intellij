<div style="display: flex; align-items: center; justify-content: center;">
  <h1 style="display: flex; align-items: center; margin: 0; padding: 0;">
    <img src="./src/main/resources/META-INF/pluginIcon.svg" 
         width="80" 
         style="margin-right: -25px; display: block; object-fit: contain;" />
    <span style="padding-left: 0;">ubliminal</span>
    <span style="font-weight: normal; margin-left: 10px; color: #888;">— IntelliJ Theme</span>
  </h1>
</div>



A high-contrast dark theme for JetBrains IDEs, ported from the [Subliminal Neovim colorscheme](https://github.com/GhostVox/subliminal.nvim). Built for long coding sessions with an emphasis on readability, visual hierarchy, and aesthetic consistency across the terminal and IDE.

---

## Preview
[enums](./screenshots/classes.png)

[structs and methods](./screenshots/functions.png)

---

## Color Palette

| Role | Hex | Preview |
|---|---|---|
| Background | `#0d1117` | ![Background color swatch](https://img.shields.io/badge/%20-f5906a?style=flat-square&color=0d1117) |
| Surface | `#161b22` | ![Surface color swatch](https://img.shields.io/badge/%20-f5906a?style=flat-square&color=161b22) |
| Elevated | `#21262d` | ![Elevated color swatch](https://img.shields.io/badge/%20-f5906a?style=flat-square&color=21262d) |
| Border | `#30363d` | ![Border color swatch](https://img.shields.io/badge/%20-f5906a?style=flat-square&color=30363d) |
| Foreground | `#fef6fd` | ![Foreground color swatch](https://img.shields.io/badge/%20-f5906a?style=flat-square&color=fef6fd) |
| Muted | `#8b949e` | ![Muted color swatch](https://img.shields.io/badge/%20-f5906a?style=flat-square&color=8b949e) |
| Accent (Orange) | `#f5906a` | ![Accent Orange color swatch](https://img.shields.io/badge/%20-f5906a?style=flat-square&color=f5906a) |
| Teal | `#4ec9b0` | ![Teal color swatch](https://img.shields.io/badge/%20-f5906a?style=flat-square&color=4ec9b0) |
| Blue | `#8bafc7` | ![Blue color swatch](https://img.shields.io/badge/%20-f5906a?style=flat-square&color=8bafc7) |
| String | `#ffd9b3` | ![String color swatch](https://img.shields.io/badge/%20-f5906a?style=flat-square&color=ffd9b3) |
| Number | `#ff9f43` | ![Number color swatch](https://img.shields.io/badge/%20-f5906a?style=flat-square&color=ff9f43) |
| Error | `#ff6b6b` | ![Error color swatch](https://img.shields.io/badge/%20-f5906a?style=flat-square&color=ff6b6b) |
| Warning | `#fdcb6e` | ![Warning color swatch](https://img.shields.io/badge/%20-f5906a?style=flat-square&color=fdcb6e) |

---

## Syntax Highlighting

| Token | Color |
|---|---|
| Keywords | `#2f6b85` bold |
| Classes / Types | `#f5906a` bold |
| Functions | `#d6acac` |
| Strings | `#ffd9b3` |
| Numbers | `#ff9f43` |
| Constants | `#c5bc91` bold |
| Comments | `#7d8590` italic |
| Parameters | `#fef6fd` italic |
| Operators | `#4ec9b0` |
| Annotations | `#8bafc7` |
| Fields | `#8fbdc6` |

### Rust (RustRover / rust-plugin)

Subliminal ships extended Rust token overrides including lifetimes, enum variants, traits, crates, derive attributes, `self` parameters, and macro parameters — all tuned to match the feel of the Neovim version.

---

## Installation

### From JetBrains Marketplace

> *Coming soon*

### Manual Installation

1. Download the latest `.zip` release from the [Releases](https://github.com/ghostvox/subliminal-intellij/releases) page.
2. Open your JetBrains IDE and go to **Settings → Plugins**.
3. Click the **⚙️** gear icon → **Install Plugin from Disk...**.
4. Select the downloaded `.zip` file and restart the IDE.
5. Go to **Settings → Appearance & Behavior → Appearance** and choose **Subliminal** from the theme dropdown.

---

## Features

- Deep GitHub-dark-inspired surface palette (`#0d1117` base) consistent with terminal environments
- Orange (`#f5906a`) accent color carried across UI chrome: caret, active tab indicator, focused borders, buttons, progress bars, and toggles
- Carefully layered backgrounds — base, surface, elevated, and hover states all distinct without being jarring
- Full editor scheme (`subliminal.xml`) with both generic and language-specific token overrides
- Extended Rust support via both `RUST_*` and `org.rust.*` token namespaces for compatibility across plugin versions
- Integrated terminal colors aligned with the editor scheme
- Status bar, tool windows, popups, notifications, and dialogs all themed consistently

---

## Compatibility

| IDE | Supported |
|---|---|
| IntelliJ IDEA (Community & Ultimate) | ✅ |
| RustRover | ✅ |
| GoLand | ✅ |
| WebStorm | ✅ |
| CLion | ✅ |
| Other JetBrains IDEs | Likely ✅ |

**Minimum build:** `252.25557` (2025.2.4)

---

## Origin

Subliminal started as a custom Neovim colorscheme built around the `dark_pro` palette — a Catppuccin Mocha-adjacent aesthetic with a heavier blue-gray structural tone and warm orange accents. This IntelliJ port aims to be a faithful translation rather than a loose approximation, preserving the same visual intent across the very different theming systems.

---

## License

MIT — do whatever you want with it.

---

## Author

**Ghostvox** — [github.com/ghostvox](https://github.com/ghostvox)
