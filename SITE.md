# Lunaris DWM

A lightweight, keyboard-driven X11 window manager for the [Lunaris desktop](https://lunaris.shahinabdi.com). This repository builds on **dwm 6.8** with practical workflow improvements and the scripts that power its interactive status bar.

## Highlights

- **Fast and minimal:** retains dwm's small, compile-time-configured design.
- **Interactive status bar:** click and scroll controls for network, audio, brightness, battery, keyboard layouts, and the calendar.
- **Keyboard profiles:** AZERTY by default, with a QWERTY build option and matching workspace and monitor shortcuts.
- **Configurable workspaces:** customize workspace icons and application rules, with settings that can be changed without editing source files.
- **Useful helpers:** commands for status actions, keyboard setup, workspace management, and discovering keybindings.

## Build

Install the Xlib development headers, adjust `config.mk` for your system, then build and install:

```sh
make clean install
```

For the Lunaris startup setup, see [`.xinitrc`](./.xinitrc). The complete desktop configuration and installer live in the companion [Lunaris repository](https://github.com/shahinabdi/lunaris).

See the [README](./README) for configuration and usage details, and the [changelog](./CHANGELOG.md) for release history.
