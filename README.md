# gridOS

> terminal-core linux distro for hackers, devs, and system controllers.  
> minimal. beautiful. powerful. 100% keyboard-native.

![ChatGPT Image May 10, 2025, 01_23_52 PM](https://github.com/user-attachments/assets/98eb3d05-1d9a-4534-89bf-c60a2b1e8c66)

---

## ⚙️ what is gridOS?

`gridOS` is a terminal-only Linux distro built from Fedora, baked with:

- full TUI-based install system
- custom terminal UI with starship, zsh/fish, tmux
- support for fullscreen GUI apps without window managers
- no desktop bloat. just pure control.
- designed for development, debugging, hacking, servers, and immersion.

> ideal for hackers, minimalists, and terminal-only setups.

---

## 🖥️ features

- 💀 **zero desktop** – no DEs, no WMs, no cruft
- 🌌 **beautiful shell UX** – starship prompt, zsh or fish, tmux sessioning
- 📦 **fast install** – guided ncurses TUI script
- 💡 **run GUI apps** via `xinit`, `xvfb`, or inside tmux fullscreen panes
- 🧱 **modular build system** – make your own ISO with `create_iso.sh`

---

## 🚀 install to disk

boot into live ISO, then run:

```bash
sudo install.sh
```

you'll get a full guided terminal installer (TUI) with disk wipe + auto-login setup.
