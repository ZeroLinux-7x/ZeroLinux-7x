<h1 align="center">
  <img src="https://your-logo-url.png" width="120"/><br>
  ZeroLinux
</h1>

<p align="center">
  <b>A custom Arch-based distribution for hackers, developers, and power users.</b><br>
  <i>Built with passion by <strong>Zero7x</strong></i>
</p>

<p align="center">
  <a href="https://github.com/ZeroLinux-7x/ZeroLinux"><img src="https://img.shields.io/github/stars/ZeroLinux-7x/ZeroLinux?style=for-the-badge&color=blueviolet" alt="Stars"></a>
  <a href="https://github.com/ZeroLinux-7x/ZeroLinux"><img src="https://img.shields.io/github/license/ZeroLinux-7x/ZeroLinux?style=for-the-badge" alt="License"></a>
  <a href="#"><img src="https://img.shields.io/badge/Arch-Based-blue?style=for-the-badge&logo=arch-linux" alt="Arch Linux"></a>
</p>

---

## 🚀 About ZeroLinux

**ZeroLinux** is a fast, modern, and highly customized Arch-based Linux distribution designed specifically for:

- ⚔️ Ethical hackers
- 💻 Developers & system administrators
- 🎨 Customization lovers
- 🧠 Power users who love full control

ZeroLinux combines the power of Arch with a stunning ZSH environment, pre-installed penetration tools, beautiful theming, and a semi-automatic Calamares installer.

---

## 🔧 Features

- ✅ Based on Arch Linux (rolling release)
- 🧪 Includes pre-configured ethical hacking tools (via `zero-tools`)
- 🖥️ Custom ZSH terminal with Starship, Fastfetch & ASCII branding
- 🧠 KDE Plasma with dark, minimal and stylish theme
- 🧩 Pre-installed scripts: `zero-tools` & `zero-manager`
- 💿 Calamares installer with custom branding and auto-partitioning
- 🐧 Lightweight, clean, and blazing fast

---

## 📸 Screenshots

<p align="center">
  <img src="assets/desktop.png" width="700" alt="ZeroLinux Desktop Screenshot">
  <img src="assets/installer.png" width="700" alt="Calamares Installer Screenshot">
</p>

---

## 🛠️ Installation

### 1. Download the ISO

> (Coming Soon) — ISO will be available in the [Releases](https://github.com/ZeroLinux-7x/ZeroLinux/releases)

### 2. Create a bootable USB

```bash
sudo dd if=ZeroLinux.iso of=/dev/sdX bs=4M status=progress && sync
