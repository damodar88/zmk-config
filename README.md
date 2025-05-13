# ZMK Config: Ferris Keyboard (Dvorak for Git/IntelliJ/Linux)

![Ferris Keyboard](https://i.imgur.com/JKQl6LY.jpg)

A Dvorak-optimized firmware configuration for Ferris split keyboards with developer shortcuts for Git, IntelliJ, and Linux workflows.

## Features

- **Dvorak layout** with home row mods (HRML/HRMR)
- **Layer-based workflow**:
  - Git commands (clone, checkout, commit, push)
  - IntelliJ shortcuts (search, refactor, debug)
  - Linux commands (ls, grep, mkdir)
- **40+ combos** for quick access
- **Bluetooth support** (3 devices)

## Layers

| Layer | Description                  |
|-------|------------------------------|
| BASE  | Default Dvorak with mods     |
| CMK   | Linux/IntelliJ commands      |
| NUM   | Numbers & editor shortcuts   |
| SYM   | Symbols & Git commands       |
| FNC   | Special chars & Bluetooth    |

## 🔧 Installation

### Quick Method (Pre-built):
1. Go to **Actions** → "Build Firmware"
2. Download latest successful build
3. Connect Ferris in bootloader mode (double-click reset)
4. Copy:
   - `ferris_left.uf2` → Left half
   - `ferris_right.uf2` → Right half
5. Auto-reboots when done

### Build Manually:
```bash
# Requires ZMK environment
west init -l config/
west update
west build -b nice_nano_v2 -- -DSHIELD=ferris_left
# Repeat for right half


🔹 Based on @filterpaper's work
🔹 License: MIT (see SPDX header)
