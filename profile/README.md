# 🩸 Berserk Arch

[![Berserk Arch](https://img.shields.io/badge/Berserk%20Arch-282a36?style=for-the-badge&logo=arch-linux&logoColor=blue)](https://berserkarch.org)
[![License](https://img.shields.io/badge/license-GPLv3-blue)](https://www.gnu.org/licenses/gpl-3.0.en.html)
[![ISO Release](https://img.shields.io/badge/ISO-Stable_Release-success)](https://berserkarch.org/download)
[![Downloads (SourceForge)](https://img.shields.io/sourceforge/dt/berserkarch.svg)](https://sourceforge.net/projects/berserkarch/files/latest/download)
[![Subreddit](https://img.shields.io/reddit/subreddit-subscribers/BerserkArch?style=social)](https://reddit.com/r/BerserkArch)

**Berserk Arch** is a bleeding-edge, security-focused, performance-tuned Arch Linux-based operating system crafted for hackers, developers, and technical users. It ships a modular desktop environment selection, a curated offensive security tool manager (`berserk`), signed package infrastructure, and a minimal-by-design base — giving you full control from the first boot.

> ⚠️ **This is not a beginner-friendly distro.** You are expected to know your way around Linux.

---

## SourceForge

<img src="https://sourceforge.net/cdn/syndication/badge_img/3928536/oss-users-love-us-white?&r=https://sourceforge.net/p/berserkarch/admin/files-sf/badges" width="125" /><img src="https://sourceforge.net/cdn/syndication/badge_img/3928536/oss-rising-star-white?achievement=oss-rising-star&r=https://sourceforge.net/p/berserkarch/admin/files-sf/badges" width="125" />

---

## 🧩 What's Inside

### 🖥️ Desktop Profiles

Six pre-configured desktop environments — pick what fits your workflow:

| Profile | Notes |
|---------|-------|
| **DWM** | X11 tiling WM |
| **Hyprland** | Wayland-native, composited, fast |
| **i3wm** | X11 tiling, battle-tested |
| **Openbox** | Lightweight floating WM |
| **XFCE4** | Solid GTK desktop, recommended default |
| **GNOME** | Full GNOME shell |
| **KDE Plasma** | Full KDE stack |

---

### 🛠️ `berserk` — Offensive Security Tool Manager

The flagship tool. `berserk` manages your entire hacking toolkit from a single command — always pulling from original sources, always latest:

- **Multi-backend**: installs via `go`, `cargo`, `pipx`, `npm`, `gem`, `pacman`, and GitHub releases
- **Profiles**: install entire toolkits by use case (OSCP loadout, AD attacks, web, recon, post-exploitation...)
- **Categories**: fine-grained tagging for targeted installs
- **Docker catalog**: run pre-configured containers (Kali CLI, Tor Browser, etc.) without managing image names
- **Extensible**: the full YAML catalog is yours to fork, extend, and customize

```sh
berserk doctor                        # verify all backends
berserk sync                          # pull latest catalog
berserk list -p                       # list all profiles
berserk install --profile ad-attacks  # install a full profile
berserk install nuclei naabu          # install specific tools
berserk search bloodhound             # search the catalog
berserk run kali-cli                  # run a Docker container
berserk update                        # update everything
```

> `berserk` also installs standalone on **Kali**, **Parrot**, and any **Arch-based** system.  
> See: [`thehackersbrain/berserk`](https://github.com/thehackersbrain/berserk)

### 📦 Package Mirrors

Three signed repos on top of the full Arch ecosystem:

- `berserkarch-core` — core distro packages
- `berserkarch-aur` — curated AUR packages, pre-built
- `berserkarch-extra` — extended tooling and utilities

Full mirror setup: [wiki.berserkarch.org](https://wiki.berserkarch.org)

---

## 🚀 Get Started

### 1. Download the ISO

| Mirror | Link |
|--------|------|
| 🔗 Direct | [berserkarch.org/download](https://berserkarch.org/download) |
| 📦 SourceForge | [sourceforge.net/projects/berserkarch](https://sourceforge.net/projects/berserkarch/files/) |
| ☁️ Google Drive | [Drive folder](https://drive.google.com/drive/folders/14sOpnU4iMUeivxWvj9rvctVFgGUbXiAq) |
| 🌊 Torrent | [berserkarch.org/torrent](https://berserkarch.org/torrent) |

Always verify with `.sig` or `sha256sum` before flashing.

---

## 📚 Documentation

Everything lives at *[wiki.berserkarch.org](https://wiki.berserkarch.org)*:

- [Installing the System](https://wiki.berserkarch.org/installation/install/)
- [berserk Tool Manager](https://github.com/thehackersbrain/berserk)
- [Docker Containers](https://wiki.berserkarch.org/containers/docker/)
- [Keyboard Shortcuts](https://wiki.berserkarch.org/keyboard-shortcuts/)
- [Changelogs](https://wiki.berserkarch.org/changelogs/)

---

## 🤝 Contribute

- **Tools**: add entries to the [berserk-repo](https://github.com/berserkarch/berserk-repo) catalog YAML — profiles, categories, installers, Docker containers
- **Packages**: help test and maintain `berserkarch-core`, `berserkarch-aur`, `berserkarch-extra`
- **Docs**: write guides, post configs, document use-cases on the wiki
- **Bug reports**: [GitLab Issues](https://gitlab.com/berserkarch) or [r/BerserkArch](https://reddit.com/r/BerserkArch)

---

## 🌐 Links

| | |
|-|-|
| 🔗 Website | [berserkarch.org](https://berserkarch.org) |
| 📖 Wiki | [wiki.berserkarch.org](https://wiki.berserkarch.org) |
| 🗨️ Subreddit | [r/BerserkArch](https://reddit.com/r/BerserkArch) |
| 🧑‍💻 GitLab | [gitlab.com/berserkarch](https://gitlab.com/berserkarch) |
| 🐙 GitHub | [github.com/berserkarch](https://github.com/berserkarch) |
| 🐦 X (Twitter) | [@thehackersbrain](https://x.com/thehackersbrain) |

---

## 🩸 Final Note

Berserk Arch is not designed to be easy.  
> **Built by hacker, for hackers.**
