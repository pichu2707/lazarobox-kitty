![lazarobox-kitty](/lazarobox-kitty.png)

# lazarobox-kitty

<p align="center">
  <img src="./assets/banner.png" alt="lazarobox-kitty banner">
</p>

<p align="center">
  <strong>A modern, GPU accelerated and aesthetically consistent kitty configuration.</strong>
</p>

<p align="center">
  Built to match the LazaroBox ecosystem with a cyan/purple cyber-inspired palette,
  vim-style navigation and productivity-focused defaults.
</p>

---

## ✨ Features

- 🚀 GPU accelerated terminal powered by kitty
- 🎨 Cyan / purple LazaroBox palette
- 🧠 Vim-style pane navigation
- 🪟 Native splits and layouts
- 🌫️ Frosted glass transparency with picom blur
- ⚡ Optimized rendering and low latency
- 🔤 JetBrains Mono ligatures enabled
- 🧩 Seamless integration with:
  - Neovim
  - Zsh
  - Tmux workflows
  - Hyprland / modern tiling WMs

---

## 🎨 Theme

The palette is directly aligned with:

- [lazarobox-wezterm](https://github.com/pichu2707/lazarobox-wezterm)
- [lazarobox-nvim](https://github.com/pichu2707/lazarobox-nvim)

### Color philosophy

- Deep dark backgrounds
- Cyan primary accents
- Purple secondary highlights
- Soft contrast for long coding sessions
- Readable diagnostics and LSP feedback

---

## ⚡ Performance

Optimized for responsiveness:

```conf id="nppdh7"
repaint_delay  8
input_delay    3
sync_to_monitor yes
```

Includes:

- low input latency
- smooth rendering
- monitor sync
- efficient redraw behavior

---

## 🌫️ Transparency & Blur

LazaroBox Kitty is designed to work beautifully with picom blur.

```conf id="06m9nw"
background_opacity 0.95
dynamic_background_opacity yes
```

Recommended compositor:

- picom with `dual_kawase` blur

This creates the frosted glass terminal aesthetic used across the LazaroBox ecosystem.

---

## 🔤 Font Configuration

Default font:

```text id="wtlq4e"
JetBrains Mono
```

Features enabled:

- ligatures
- bold italics
- programming glyphs
- Nerd Font compatibility

Recommended:

- JetBrainsMono Nerd Font

---

## 🪟 Layouts

Enabled layouts:

```text id="yvgwx4"
splits, stack, tall, fat
```

Supports:

- vertical splits
- horizontal splits
- stack layouts
- workspace-style workflows

---

## ⌨️ Keybindings

The configuration mirrors the key philosophy from `lazarobox-wezterm`.

### Pane management

| Key                      | Action           |
| ------------------------ | ---------------- |
| `Alt + -`                | Horizontal split |
| `Alt + \`                | Vertical split   |
| `Ctrl + Shift + H/J/K/L` | Navigate panes   |
| `Ctrl + Shift + ←/→/↑/↓` | Resize panes     |

### Tabs

| Key                | Action    |
| ------------------ | --------- |
| `Ctrl + Shift + T` | New tab   |
| `Ctrl + Shift + W` | Close tab |

### Clipboard

| Key                | Action |
| ------------------ | ------ |
| `Ctrl + Shift + C` | Copy   |
| `Ctrl + Shift + V` | Paste  |

### Font size

| Key        | Action        |
| ---------- | ------------- |
| `Ctrl + =` | Increase font |
| `Ctrl + -` | Decrease font |
| `Ctrl + 0` | Reset font    |

---

## 📦 Installation

Clone into your kitty config directory:

```bash id="f6szrj"
git clone https://github.com/pichu2707/lazarobox-kitty ~/.config/kitty
```

Restart kitty.

---

## 🛠 Requirements

### Required

- kitty >= 0.32
- Linux or macOS
- Nerd Font installed

### Recommended

- picom
- zsh
- Neovim
- Hyprland

---

## 🧩 Ecosystem

LazaroBox is designed as a visually and ergonomically consistent terminal ecosystem.

### Related projects

- [lazarobox-wezterm](https://github.com/pichu2707/lazarobox-wezterm)
- [lazarobox-nvim](https://github.com/pichu2707/lazarobox-nvim)

---

## ❤️ Credits

Made with love by [pichu2707](https://github.com/pichu2707)

If you like the project, consider giving it a ⭐
