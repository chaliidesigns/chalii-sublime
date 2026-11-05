<h1 align="center">🎨 Chalii Themes - Sublime Text</h1>

<p align="center">
  Premium light and dark color schemes for Sublime Text 3 / 4 with warm orange accents and excellent readability.<br>
  The Sublime Text port of the <a href="https://github.com/chaliidesigns/chalii-themes">Chalii Themes</a> family, mirrored here for Package Control.
</p>

<p align="center">
  <a href="#-features">✨ Features</a> •
  <a href="#-quick-start">🚀 Quick Start</a> •
  <a href="#-manual-install">📥 Manual Install</a> •
  <a href="#-structure">🏗️ Structure</a> •
  <a href="https://github.com/chaliidesigns/chalii-themes">🧩 Source Repo</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Sublime%20Text-3%20%7C%204-FF9800?logo=sublimetext&logoColor=white" alt="Sublime Text 3 / 4">
  <img src="https://img.shields.io/badge/Package%20Control-Chalii%20Themes-ff711a" alt="Package Control">
  <img src="https://img.shields.io/badge/format-.sublime--color--scheme-0e0e0f" alt="sublime-color-scheme">
  <img src="https://img.shields.io/badge/Version-1.0.0-ff711a" alt="Version 1.0.0">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="MIT">
</p>

---

## 🌟 Highlights

- ☀️🌙 **Two variants** - **Chalii Light** and **Chalii Dark**, sharing one brand palette
- 🟠 **Warm orange accents** on a clean white or deep `#0e0e0f` background
- 🔁 **Generated, not hand-edited** - both schemes are built from `source/palette.json` in the main [chalii-themes](https://github.com/chaliidesigns/chalii-themes) repo
- 📦 **Package Control ready** - ships `package.json` metadata plus install/update messages

## ✨ Features

- Modern `.sublime-color-scheme` JSON format (Sublime Text 3.1+ and 4)
- Full editor UI colouring: gutter, selection, line highlight, find highlights, brackets, guides and diff markers
- Scope-based syntax colouring consistent with the VS Code, JetBrains, Zed and Neovim ports of Chalii Themes
- Works on macOS, Linux and Windows (`"platforms": ["*"]`)

## 🚀 Quick Start

### Install via Package Control

1. Open the command palette: <kbd>Cmd</kbd>/<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>
2. Run **Package Control: Install Package**
3. Choose **Chalii Themes**
4. Activate via **Preferences → Select Color Scheme…** and pick _Chalii Light_ or _Chalii Dark_

Or set it directly in **Preferences → Settings**:

```json
{
  "color_scheme": "Chalii Dark.sublime-color-scheme"
}
```

## 📥 Manual Install

Copy the two `.sublime-color-scheme` files in this directory into your Sublime Text **User** package directory:

- macOS: `~/Library/Application Support/Sublime Text/Packages/User/`
- Linux: `~/.config/sublime-text/Packages/User/`
- Windows: `%APPDATA%\Sublime Text\Packages\User\`

Then activate with **Preferences → Select Color Scheme…**.

## 🏗️ Structure

```
chalii-sublime/
├── Chalii Dark.sublime-color-scheme    # Generated dark scheme
├── Chalii Light.sublime-color-scheme   # Generated light scheme
├── package.json                        # Package Control metadata (name, labels, ST versions)
├── messages.json                       # Package Control message index
├── messages/
│   ├── install.txt                     # Shown after install
│   └── 1.0.0.txt                       # Release notes
└── LICENSE                             # MIT
```

> **Source of truth:** the `.sublime-color-scheme` files here are generated artifacts. Edit `source/palette.json` in [chalii-themes](https://github.com/chaliidesigns/chalii-themes) and run `npm run build:sublime` there, then sync the output into this repo. Please open issues and pull requests against [chalii-themes](https://github.com/chaliidesigns/chalii-themes/issues).

## 📄 License

[MIT](LICENSE) © Chalii Designs

## 👤 Author

**Chalii Designs** - design & engineering studio by Chalii wa UX/UI - [@chaliiwaui](https://github.com/chaliiwaui)

- 📧 Email: me@makindajackson.com
- 💼 LinkedIn: [Jackson Makinda](https://linkedin.com/in/makindajack)
- 🎨 Dribbble: [@makindajack](https://dribbble.com/makindajack)
- 🐦 Twitter: [@makindajack](https://twitter.com/makindajack)

Part of the **Chalii** design ecosystem - [Themes](https://github.com/chaliidesigns/chalii-themes) • [Icons](https://github.com/chaliidesigns/chalii-icons) • [Sublime Icons](https://github.com/chaliidesigns/chalii-icons-sublime) • [Zed](https://github.com/chaliidesigns/chalii-zed) • [Obsidian](https://github.com/chaliidesigns/chalii-obsidian)

---

Built with ❤️ in Dar es Salaam, Tanzania 🇹🇿
