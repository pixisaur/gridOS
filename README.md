# gridOS

> terminal-core linux distro for hackers, devs, and system controllers.  
> minimal. beautiful. powerful. 100% keyboard-native.

```
               _     ______  _____
   ____ ______(_)___/ / __ \/ ___/
  / __ `/ ___/ / __  / / / /\__ \ 
 / /_/ / /  / / /_/ / /_/ /___/ / 
 \__, /_/  /_/\__,_/\____//____/  
/____/                            
```
---

## ⚙️ what is gridOS?

`gridOS` is a terminal-only Linux distro built from scratch using Ubuntu Core with:

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
