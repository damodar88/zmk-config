# ZMK Config for Ferris Keyboard (Dvorak Layout)

This repository contains a ZMK firmware configuration for a Ferris keyboard with a Dvorak layout, optimized for Git, IntelliJ, and Linux workflows.

## Features

- **Dvorak layout** with home row mods (HRML/HRMR)
- **Layer-based workflow** with dedicated layers for:
  - **Git commands** (clone, checkout, commit, push, etc.)
  - **IntelliJ shortcuts** (search, refactor, debug, etc.)
  - **Linux commands** (ls, pwd, mkdir, grep, etc.)
  - **Navigation** (arrows, word navigation)
  - **Symbols and numbers**
- **Combo keys** for quick access to common commands
- **Macros** for complex key sequences
- **Bluetooth support** with multiple device switching

## Layers

1. **BASE**: Default Dvorak layer with home row mods
2. **CMK**: Command layer for Linux/IntelliJ commands
3. **NUM**: Number layer with common editor shortcuts
4. **SYM**: Symbol layer with Git commands
5. **FNC**: Function layer with special characters and Bluetooth controls

## Installation

1. Clone this repository
2. Build with ZMK (requires ZMK setup)
3. Flash to your Ferris keyboard

## Customization

Edit the `.dtsi` files to modify:
- Key positions
- Tap/hold timing
- Combo keys
- Macros

## License

MIT License (see SPDX-License-Identifier in source)

---

**Note**: This configuration is based on the work of @filterpaper and has been customized for Dvorak layout with Git/IntelliJ/Linux workflows.
