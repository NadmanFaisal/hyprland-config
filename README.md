# Nadman's Hyprland Config

A highly optimized, blazing-fast Hyprland Wayland configuration built on top of JaKooLit's dotfiles. This setup has been specifically tuned for Linux Mint and an AMD Ryzen 7 laptop to bypass XWayland bottlenecks and achieve maximum app launch speeds.

## System Details
* **Window Manager:** Hyprland (Wayland)
* **Terminal:** Kitty

## Installation
To use this configuration on a new machine, clone it directly into your Hyprland directory:

```bash
git clone git@github.com:NadmanFaisal/hyprland-config.git ~/.config/hypr
```

Based on the excellent JaKooLit Hyprland Dotfiles.

## Monitor Management (hyprmoncfg)
This setup uses **hyprmoncfg** for a visual way to manage monitor layouts, rotations, and profiles without manual coordinate math.

### 1. Installation
To install the tool and its background daemon on a fresh system, run the following:

```bash
chmod +x install_hyprmonconf.sh
```
