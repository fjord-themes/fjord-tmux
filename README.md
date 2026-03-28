# Fjord Theme for Tmux

A clean and elegant tmux color theme plugin with the Fjord color scheme inspired by Nord and Ayu Mirage.


## 🎨 Color Palette

### Core Colors

| Color | Name |
| ---- | ----------------- |
| ![background](https://img.shields.io/badge/%231B2532-1B2532) | **background** |
| ![backgroundAlt](https://img.shields.io/badge/%23222E3F-222E3F) | **backgroundAlt** |
| ![surface](https://img.shields.io/badge/%231F2A39-1F2A39) | **surface** |
| ![line](https://img.shields.io/badge/%23233141-233141) | **line** |
| ![foreground](https://img.shields.io/badge/%23E8F0F3-E8F0F3) | **foreground** |
| ![muted](https://img.shields.io/badge/%236C7A86-6C7A86) | **muted** |
| ![mutedDim](https://img.shields.io/badge/%2351606B-51606B) | **mutedDim** |

### Accent Colors

| Color | Name |
| ---- | ---------------------------- |
| ![green](https://img.shields.io/badge/%239DD99A-9DD99A) | **green** _(primary accent)_ |
| ![blue](https://img.shields.io/badge/%235DA6EA-5DA6EA) | **blue** |
| ![yellow](https://img.shields.io/badge/%23FFD285-FFD285) | **yellow** |
| ![purple](https://img.shields.io/badge/%23B9A0F8-B9A0F8) | **purple** |
| ![red](https://img.shields.io/badge/%23F37C7C-F37C7C) | **red** |
| ![cyan](https://img.shields.io/badge/%23B8E7E9-B8E7E9) | **cyan** |

## 📦 Installation



### Using TPM

Add this line to your `~/.tmux.conf`:

```tmux
set -g @plugin 'fjord-themes/fjord-tmux'
```

Then press `prefix` + <kbd>I</kbd> to fetch and install the plugin.

### Manual Installation


1. Clone this repository:
```bash
git clone https://git.jshuntley.com/fjord-theme/fjord-tmux.git ~/.tmux/plugins/fjord-tmux
```

2. Add this line to your `~/.tmux.conf`:
```tmux
run '~/.tmux/plugins/fjord-tmux/fjord.tmux'
```

3. Reload tmux configuration:
```bash
tmux source-file ~/.tmux.conf
```

## 🔧 Configuration

### Status Content

To disable the status bar content:

```tmux
set -g @fjord_tmux_show_status_content 0
```

### Date Format

Customize the date format in the status bar:

```tmux
set -g @fjord_tmux_date_format "%Y-%m-%d"
```

### No Patched Font

If you don't have a powerline-patched font installed, disable the special characters:

```tmux
set -g @fjord_tmux_no_patched_font 1
```

## Plugin Support

Fjord supports the following plugins:

- [tmux-prefix-highlight](https://github.com/tmux-plugins/tmux-prefix-highlight) - Shows a visual indicator when prefix is pressed

To use tmux-prefix-highlight, install it AFTER the Fjord theme:

```tmux
set -g @plugin 'fjord-themes/fjord-tmux'
set -g @plugin 'tmux-plugins/tmux-prefix-highlight'
```
## 🔄 Updates

This theme is automatically generated from [fjord-core](https://github.com/fjord-themes/fjord-core) and deployed on every release. For an overview of all supported platforms and the full color palette, visit the [Fjord GitHub page](https://github.com/fjord-themes).
## ☕ Support My Work

If you enjoy the Fjord theme and find it useful, consider supporting my work:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy_Me_A_Coffee-99dd9a?style=for-the-badge&logo=buy-me-a-coffee&logoColor=FFD285&logoSize=auto&labelColor=1B2532)](https://buymeacoffee.com/jshuntley)
## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.
## 🤝 Contributing

For theme suggestions or issues, please open an issue on the [Fjord GitHub page](https://github.com/fjord-themes).