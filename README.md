# ChatGPT Mocha Wide – UserStyle

A polished **UserStyle for ChatGPT** inspired by the **Catppuccin Mocha** palette. Designed for long sessions, wide screens, dark mode, and a cleaner visual hierarchy.

## ✨ Features

- **Wide (semi-edge) layout** – reduces unnecessary side margins
- **Dark glass cards** for user and assistant messages
- **Atmospheric Catppuccin Mocha background** with subtle mauve and teal gradients
- **Themed sidebar** with hover states and active conversation highlighting
- **Darker, cleaner composer** with stronger teal borders
- **Smooth Mocha fade** between the conversation and composer
- **Themed `+` tools menu**
- **Themed chat context menus and submenus**
- **Themed profile menu**
- **Themed model / mode selector**
- **Catppuccin styling for code blocks and inline code**
- **Clean bottom UI** with the ChatGPT disclaimer hidden
- **Styled turn-action buttons and tooltips**
- **Cross-browser scrollbar styling** for Firefox/Zen and Chromium
- Safe for syntax highlighting and long code blocks

## 🖥️ Supported Browsers

- Firefox
- Zen Browser
- Chromium-based browsers:
  - Chrome
  - Edge
  - Brave
  - Vivaldi
  - Arc

> Optimized for **ChatGPT dark mode**.

## 📦 Installation

### UserStyles.world

Install directly from the published UserStyles.world page.

### Manual installation

1. Install a userstyle manager such as **Stylus**
2. Import the `.user.css` file
3. Enable the style for `chatgpt.com`

## 🎨 Customization

Most colors and visual settings are defined as CSS variables inside `:root`.

You can easily customize:

- Catppuccin accent colors
- Card opacity
- Border intensity
- Composer styling
- Sidebar accents
- Menu hover intensity
- Scrollbar size and colors

## 🆕 Current version

Major compatibility update for the current ChatGPT interface.

- Updated selectors for the current ChatGPT DOM
- Restored wide assistant and user message cards
- Updated support for the current composer structure
- Added Catppuccin Mocha styling to the sidebar
- Added styling for conversation and project rows
- Added styling for global menus and nested submenus
- Added styling for profile and model/mode menus
- Updated the `+` tools menu
- Restored the smooth Mocha composer/footer fade
- Removed the current ChatGPT disclaimer
- Improved Firefox/Zen and Chromium compatibility

## 📝 Notes

- Designed for **dark mode**
- CSS-only — no JavaScript
- ChatGPT frequently changes its DOM, so occasional selector updates may be required
- The style aims to preserve ChatGPT functionality while changing its visual presentation

## 📄 License

MIT
