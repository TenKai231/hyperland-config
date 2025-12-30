# Hyprland Dotfiles

Minimal yet functional **Hyprland** setup focused on productivity, clean UI, and simplicity.  
Designed for daily use, not just screenshots.

---

## ✨ Preview
> Clean Wayland workflow with smooth animations and minimal distractions.

---

## 🧩 Stack
- **WM**: Hyprland
- **Bar**: Waybar
- **Launcher**: Wofi (Rofi optional)
- **Terminal**: Kitty
- **Compositor**: Hyprland (native)
- **Session**: Wayland

---

## 📁 Structure
```text
hyprland-dotfiles/
├── hypr/        # Hyprland main configuration
├── waybar/     # Status bar config
├── wofi/       # App launcher
├── kitty/      # Terminal config
├── rofi/       # Optional launcher
└── README.md

git clone https://github.com/USERNAME/hyprland-dotfiles.git
cd hyprland-dotfiles

cp -r hypr ~/.config/
cp -r waybar ~/.config/
cp -r wofi ~/.config/
cp -r kitty ~/.config/
cp -r rofi ~/.config/   # optional
