# 🌌 h2obt's Dotfiles

My personal configuration files for a minimal and efficient Hyprland + Waybar setup on Linux.

> A collection of configurations I've crafted (with some AI assistance 😄) to create a beautiful and functional desktop environment. These dotfiles are here so I don't have to rebuild everything when things break!

I'm always open to suggestions and improvements. Feel free to reach out if you think something can be done better! 💡

---

## 🛠️ What's Included

### Core Components
- **WM:** [Hyprland](https://hyprland.org/) - A modern wayland compositor
- **Bar:** [Waybar](https://github.com/Alexays/Waybar) - Status bar for wlroots-based compositors
- **Terminal:** [Kitty](https://sw.kovidgoyal.net/kitty/) - GPU-based terminal emulator
- **Application Launcher:** [Rofi-wayland](https://github.com/lbonn/rofi) - Application/window switcher
- **Wallpaper Manager:** [Hyprpaper](https://github.com/hyprwm/hyprpaper) - Wallpaper daemon for Hyprland
- **File Manager:** [Thunar](https://docs.xfce.org/xfce/thurico/thunar/start) - Lightweight file manager

---

## 📋 Requirements & Dependencies

### Essential
- **Base WM & Compositor:** Hyprland
- **Display Server:** Wayland (no X11 support in this config)
- **Font:** `ttf-jetbrains-mono-nerd` (for icons and text rendering)

### Tools & Utilities
| Category | Tools |
|----------|-------|
| **Screenshots** | hyprshot |
| **Authentication** | hyprpolkitagent |
| **Screen Sharing** | xdg-desktop-portal-hyprland |
| **Audio** | wireplumber, pavucontrol, playerctl |
| **Bluetooth** | blueman |
| **Network** | network-manager-applet |
| **VPN** | mullvad-vpn |
| **System Info** | lm_sensors, libnotify |
| **Browser** | firefox |

---

## 📁 Directory Structure

```
dotfiles/
├── hypr/              # Hyprland configuration
├── waybar/            # Waybar status bar config
├── kitty/             # Kitty terminal config
├── rofi/              # Rofi launcher config
├── ly/                # Ly login manager config
├── etc/               # Additional system configs
└── README.md          # This file
```

---

## 🚀 Quick Start

### Prerequisites
Ensure you have Hyprland installed. For Arch Linux:

```bash
pacman -S hyprland waybar kitty rofi-wayland hyprpaper ttf-jetbrains-mono-nerd
```

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/h2obt/dotfiles ~/.config/dotfiles
   cd ~/.config/dotfiles
   ```

2. **Copy configurations to their respective directories:**
   ```bash
   cp -r hypr ~/.config/
   cp -r waybar ~/.config/
   cp -r kitty ~/.config/
   cp -r rofi ~/.config/
   ```

3. **Install optional dependencies** as needed for full functionality

4. **Restart Hyprland** (Ctrl + Alt + Q) or log out and back in

### Manual Setup
If you prefer, you can manually copy individual config files to:
- `~/.config/hypr/` (Hyprland)
- `~/.config/waybar/` (Waybar)
- `~/.config/kitty/` (Kitty)
- `~/.config/rofi/` (Rofi)

---

## ⚙️ Configuration Notes

Each directory contains configuration files for its respective application:

- **hypr/**: Hyprland window manager settings, keybindings, and window rules
- **waybar/**: Status bar layout, modules, and styling
- **kitty/**: Terminal font, colors, and behavior settings
- **rofi/**: Application launcher theme and functionality
- **ly/**: Display manager configuration (if using Ly)
- **etc/**: Additional system-level configurations

Feel free to customize these files to match your preferences!

---

## 🎨 Customization

The configs are designed to be modular and easy to customize:

1. Edit `hypr/hyprland.conf` for window manager settings
2. Edit `waybar/config` and `waybar/style.css` for the status bar
3. Modify `kitty/kitty.conf` for terminal settings
4. Adjust `rofi/config.rasi` for the application launcher

Refer to each application's official documentation for detailed configuration options.

---

## 📝 License

These dotfiles are provided as-is. Feel free to use, modify, and share!

---

## 🤝 Contributing

Suggestions and improvements are welcome! If you have ideas to improve these configurations, please feel free to open an issue or reach out.

---

## 🙏 Acknowledgments

- Thanks to the Hyprland, Waybar, and wider Linux community for amazing tools
- Props to AI for the initial guidance during setup

---

**Last Updated:** 2026-07-02
