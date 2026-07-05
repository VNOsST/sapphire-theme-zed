# Sapphire Theme for Zed

A dark, vibrant blue theme for the [Zed](https://zed.dev) editor, faithfully ported from [Sapphire](https://marketplace.visualstudio.com/items?itemName=Tyriar.theme-sapphire) — a popular Visual Studio Code theme by [Daniel Imms](https://www.growingwiththeweb.com).

## About

Sapphire is a carefully crafted dark theme built around a deep blue background with a cohesive, high-contrast color palette. Every color is chosen with semantic meaning, making code easier to read and navigate at a glance.

This Zed port builds on a local opencode port of Sapphire that was completed previously for personal use and is also included in this repository. The opencode port's color definitions and semantic mappings (found in `opencode_ref/sapphire.json`) served as the direct reference for translating the theme into Zed's format, ensuring fidelity to the original VS Code experience while fully leveraging Zed's theming capabilities.

## Color Palette

| Role | Hex |
|------|-----|
| Background | `#080d14` |
| Panel | `#090f18` |
| Element | `#0c1420` |
| Primary | `#399EF4` |
| Cyan | `#21C5C7` |
| Green | `#4EB071` |
| Yellow | `#fff099` |
| Red | `#DA6771` |
| Magenta | `#B168DF` |
| Muted | `#535a6b` |

## Semantic Colors

Colors in Sapphire carry consistent meaning:

- **Keywords & operators** — blue (`#399EF4`)
- **Functions & methods** — yellow (`#fff099`)
- **Variables & parameters** — cyan (`#21C5C7`)
- **Types & classes** — green (`#4EB071`)
- **Strings & numbers** — red (`#DA6771`)
- **Comments** — muted (`#535a6b`, italic)
- **Escape sequences & conflicts** — magenta (`#B168DF`)

## Features

- Full editor, workbench, and terminal theming
- Multi-cursor player colors
- Git status indicators (created, modified, deleted, renamed, ignored)
- Semantic highlighting for errors, warnings, hints, and conflicts
- Carefully tuned syntax highlighting for Zed's Tree-sitter integration
- Dim/bright ANSI terminal color variants

## Installation

1. Open Zed
2. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
3. Run `theme: install from file`
4. Select the `sapphire.json` file from this repository

Alternatively, copy `sapphire.json` to your Zed themes directory:

- **macOS:** `~/.config/zed/themes/`
- **Linux:** `~/.config/zed/themes/`
- **Windows:** `%APPDATA%\Zed\themes\`

## Inspiration

This theme is a direct port of [Sapphire for VS Code](https://marketplace.visualstudio.com/items?itemName=Tyriar.theme-sapphire) by [Daniel Imms](https://github.com/Tyriar). The original was created using [vscode-theme-generator](https://github.com/Tyriar/vscode-theme-generator) and has over 120,000 installs on the VS Code Marketplace.

Full credit goes to Daniel Imms for the original design and color palette.

## License

[MIT](LICENSE)
