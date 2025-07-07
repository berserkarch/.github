# 🩸 Berserk Arch

[![License](https://img.shields.io/badge/license-GPLv3-blue)](https://www.gnu.org/licenses/gpl-3.0.en.html)
[![ISO Release](https://img.shields.io/badge/ISO-Beta_Released-success)](https://berserkarch.xyz)
[![Mirror Status](https://img.shields.io/badge/mirrors-signed-green)](https://wiki.berserkarch.xyz/mirrors)
[![Subreddit](https://img.shields.io/reddit/subreddit-subscribers/BerserkArch?style=social)](https://reddit.com/r/BerserkArch)
[![Docs](https://img.shields.io/badge/Readthedocs-%23000000.svg&logo=readthedocs&logoColor=white)](https://wiki.berserkarch.xyz/)

**Berserk Arch** is a security-focused, performance-tuned Arch Linux-based operating system tailored for developers, hackers, and technical users. It offers a modular environment with pre-configured desktop profiles, secure package infrastructure, and curated toolsets — all designed with flexibility, clarity, and control in mind.

---

## 🧩 Repository Structure

Berserk Arch is built as a modular, GitOps-style ecosystem:

- [`berserk-core`](https://gitlab.com/berserkarch/berserk-core) – Base system files, hooks, branding, system tweaks
- [`berserk-pkg`](https://gitlab.com/berserkarch/berserk-pkg) – Custom PKGBUILDs, hacking tools, red team utilities
- [`berserk-profiles`](https://gitlab.com/berserkarch/berserk-profiles) – Desktop environment modules
  - `berserk-xfce` – Default profile, stable and pre-configured
  - `berserk-openbox` – Lightweight, fast, minimal
  - `berserk-hyprland` – Wayland-based, sleek, modern
  - _(GNOME planned, KDE intentionally excluded)_

---

## 🛠️ How to Use

### 🔥 Get the Beta ISO

- Download from the [Official Site](https://berserkarch.xyz)
- Verify using `.sig` or `sha256sum`
- Boot the ISO → Calamares Installer → Get hacking

### 📚 Read the Docs

- Installation Guide, Post-Install Setup, Configs: [wiki.berserkarch.xyz](https://wiki.berserkarch.xyz)
- Bug reports, feedback, feature requests:
  - GitLab issues or
  - Subreddit thread: [r/BerserkArch](https://reddit.com/r/BerserkArch)

### 🔃 Contribute

- Submit patches to `berserk-core`, `berserk-pkg`, or profile modules
- Suggest tools for meta packages or join testing on the subreddit
- Help document the distro and share use-cases, configs, and issues

---

## 🚀 Roadmap (Post-Beta)

- 📦 Package Meta Groups (`berserk-tools-core`, `berserk-tools-redteam`, etc.)
- 🐳 Official Docker Image (base setup for CI/CD workflows)
- 🧬 Auto-updating OTA ISO and pacman repos
- 🤖 Full CI/CD pipeline for package builds, repo syncs, mirror updates
- 🖼 Additional DE profiles (GNOME planned, KDE not supported by choice)
- 💡 More security/hacking tools with configs ready-to-go out of the box

---

## 🌐 Links

- 🔗 Website: [https://berserkarch.xyz](https://berserkarch.xyz)
- 📖 Wiki: [https://wiki.berserkarch.xyz](https://wiki.berserkarch.xyz)
- 🗨️ Subreddit: [https://reddit.com/r/BerserkArch](https://reddit.com/r/BerserkArch)
- 📦 Mirrors: Signed `berserk-core`, `berserk-aur`, `berserk-extra` (see wiki for usage)
- 🧑‍💻 GitLab Group: [https://gitlab.com/berserkarch](https://gitlab.com/berserkarch)

---

## 🩸 Final Note

Berserk Arch is not designed to be easy.  
It’s designed to make **you** powerful.

Whether you're reverse-engineering binaries, automating exploits, or just ricing your XFCE like a lunatic...  
This distro gives you the **base** to build your **edge**.

Welcome to the madness.

> **Built by a hacker, for hackers.**
