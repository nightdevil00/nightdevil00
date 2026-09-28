# Hi there

I'm **Robertino Mihai Sandorhazi** — a tech and programming enthusiast.

I build things for my own machine: system configuration, small tools, and the
kind of automation that makes everyday use less tedious.

## Plugins

Fifteen shell plugins for [Omarchy](https://omarchy.org/), written in QML for
Quickshell — bar widgets, panels, overlays and background services.

[![Plugins](https://img.shields.io/badge/plugins-15-6f42c1?style=flat-square)](https://github.com/nightdevil00/Plugins)

| | |
| --- | --- |
| **Panels & overlays** | [Omarchy Settings](https://github.com/nightdevil00/Plugins/tree/main/custom-settings) · [Spotlight](https://github.com/nightdevil00/Plugins/tree/main/mihai.spotlight) · [Wallpaper Picker](https://github.com/nightdevil00/Plugins/tree/main/mihai.picker) · [Simple Dock](https://github.com/nightdevil00/Plugins/tree/main/simple.dock) |
| **Bar widgets** | [Better Displays](https://github.com/nightdevil00/Plugins/tree/main/better.displays) · [Bluetooth Codecs](https://github.com/nightdevil00/Plugins/tree/main/bt.codecs) · [2048](https://github.com/nightdevil00/Plugins/tree/main/custom-2048) · [Default Apps](https://github.com/nightdevil00/Plugins/tree/main/setup.defaults) · [Hider](https://github.com/nightdevil00/Plugins/tree/main/plugin.hider) · [Screenshot Picker](https://github.com/nightdevil00/Plugins/tree/main/pick.screenshot) · [TLP Battery](https://github.com/nightdevil00/Plugins/tree/main/tlp.battery) · [OmaPony](https://github.com/nightdevil00/Plugins/tree/main/yt-pony) · [opencode Usage](https://github.com/nightdevil00/Plugins/tree/main/mihai.opencode-usage) |
| **Services** | [YouTube Music](https://github.com/nightdevil00/Plugins/tree/main/mihai.ytmusic) · [No Sleep](https://github.com/nightdevil00/Plugins/tree/main/white.nights) |

Browse them all in the [Plugins collection](https://github.com/nightdevil00/Plugins)
— it has a map, per-plugin notes, and install instructions.

## Tools

[![Tools](https://img.shields.io/badge/tools-1-6f42c1?style=flat-square)](https://github.com/nightdevil00/Tools)

Small standalone Linux apps, in the [Tools collection](https://github.com/nightdevil00/Tools).

| Tool | What it does |
| --- | --- |
| [DDWriter](https://github.com/nightdevil00/Tools/tree/main/DDWriter) | GTK3 utility for writing ISO images to USB drives with `dd` — device detection, live progress, optional SHA256 verification, auto-eject |

## Dotfiles

[![Dotfiles](https://img.shields.io/badge/dotfiles-2-6f42c1?style=flat-square)](https://github.com/nightdevil00/Dotfiles)

My own machine's configuration, in the [Dotfiles collection](https://github.com/nightdevil00/Dotfiles).

| Config | What it is |
| --- | --- |
| [Hyprland](https://github.com/nightdevil00/Dotfiles/tree/main/Hyprland) | Hyprland configuration and keybindings, written in Lua |
| [Fastfetch](https://github.com/nightdevil00/Dotfiles/tree/main/Fastfetch) | Two `fastfetch` layouts, with a script to pick and install one |

Each config installs with its own `install.sh` from a clone, and each backs up what it is about to replace, so re-running is safe. Fastfetch's asks which layout you want — 1 or 2.

## Scripts

[![Scripts](https://img.shields.io/badge/scripts-5-6f42c1?style=flat-square)](https://github.com/nightdevil00/Scripts)

Installer, recovery and setup scripts in the [Scripts collection](https://github.com/nightdevil00/Scripts).

| Collection | What it does |
| --- | --- |
| [OfflineArch](https://github.com/nightdevil00/Scripts/tree/main/OfflineArch) | Builds a custom Arch ISO that installs Arch with no internet — DualBoot alongside Windows or full wipe — and runs the installer automatically on first boot |
| [System_Repair](https://github.com/nightdevil00/Scripts/tree/main/System_Repair) | Rescue script for a machine that will not boot: finds the root partition, handles LUKS, mounts Btrfs subvolumes and boot partitions, then drops you into a chroot. Writes nothing to disk |
| [Arch_Installers](https://github.com/nightdevil00/Scripts/tree/main/Arch_Installers) | Eight standalone installers and repair tools — full installs with a choice of desktop environment, Windows dualboot with GRUB or Limine, disk partitioning for `archinstall`, and a Limine recovery script |
| [Tweaks](https://github.com/nightdevil00/Scripts/tree/main/Tweaks) | Eight one-off setup scripts — Nerd Fonts for waybar, XDG directories, default applications, SDDM autologin, memory tuning, disabling services |
| [Dotfiles_Backup](https://github.com/nightdevil00/Scripts/tree/main/Dotfiles_Backup) | `dotback` — archives `~/.config`, `~/.local` and your package lists, and restores them on a fresh machine |

Each collection has its own README with requirements, usage and caveats. The
installers are works in progress, and the READMEs say which ones have bugs that
stop them working and what to fix first.

## Wallpapers

Desktop backgrounds in the [Wallpapers collection](https://github.com/nightdevil00/Wallpapers) — 18 images, installable into `~/Pictures/Wallpapers` with `./install.sh`.

## Documentation

[Documentation](https://github.com/nightdevil00/Documentation) — 37 notes I kept worth reading: how Omarchy works, problems I hit and what fixed them, this laptop's hardware, and tutorials.

## What I work with

- **Linux** — Arch, Hyprland, and the desktop stack around them
- **QML / Quickshell** — shell plugins, bar widgets, panels
- **Shell and automation** — install scripts, system tuning, backups
- **Occasionally** — Nix, and other things I probably shouldn't have started

## Find me

<!-- TODO: fill these in, or delete any line you don't need. -->

- **GitHub** — [@nightdevil00](https://github.com/nightdevil00)
- **Email** — <!-- TODO: you@example.com -->
- **Website** — <!-- TODO: https://your-site.example -->
