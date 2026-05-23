# Dolphin to Windows 11 Transformation Guide

A complete, pixel-perfect transformation guide for KDE Plasma 6.6.4 to make Dolphin look and behave like the Windows 11 File Explorer.

## Features

* **Chrome-style Tab Bar**: Implements trapezoidal, sloped tabs with active/inactive states.
* **Fluent Design Layout**: Reconfigures toolbars for the classic Windows 11 address bar and command strip sequence.
* **Custom Styling**: Uses a full QSS stylesheet to unify scrollbars, context menus, and sidebars.
* **Iconography**: Includes instructions for integrating Win11-style icons and action overlays.

## Prerequisites

* **KDE Plasma Version**: 6.6.4.
* **Basic Terminal Knowledge**: Familiarity with navigating the file system and editing config files.

## Quick Start

1. **Layout**: Use the "Configure Toolbars" menu in Dolphin to realign your buttons to the Windows 11 sequence.
2. **KWin Rules**: Apply a window rule to remove the standard titlebar, allowing for custom tab integration.
3. **Styling**: Save the provided QSS code to `~/.config/dolphin.qss`.
4. **Launch**: Update your `.desktop` entry to load the stylesheet automatically: `Exec=dolphin --stylesheet ~/.config/dolphin.qss %u`.

## Full Documentation

For the complete, step-by-step technical guide including all CSS and configuration files, please view the [Guide]([index.html](https://vrunox-9714.github.io/dolphin-win11-theme) file included in this repository.

---
