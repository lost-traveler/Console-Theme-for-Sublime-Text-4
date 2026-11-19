# Console

<img width="1408" height="881" alt="Screenshot" src="https://github.com/user-attachments/assets/78806c44-c970-4a5c-b180-3b627244f8a4" />



A dark, high-contrast UI theme and color scheme for **Sublime Text 4**, featuring a pure black (`#000000`) background, warm copper (`#a97759`) base text, and a 16-color syntax palette.

## Origin

**Console** is derived from a theme originally created by me, **Luis Mercado,** for the `cyberspace.online` community (and also adapted for Ghostty under the same name). The original description for that community reads:

> A theme for ᑕ¥βєяรקค¢є, inspired by old-school and obscure operating system command lines from the ’80s and ’90s, such as Plan 9 and the PC-88/98 DOS environments, among others.

## What's Included

- **`Console.sublime-color-scheme`** — Syntax highlighting and editor color scheme.
- **`Console.sublime-theme`** — Matching UI theme (sidebar, tabs, status bar, panels, and command palette), extending `Default Dark.sublime-theme`.

## Installation

### Via Package Control

1. Open the Command Palette (`Cmd + Shift + P` on macOS, `Ctrl + Shift + P` on Windows/Linux).
2. Run **`Package Control: Install Package`**.
3. Search for **`Console`** (or the published package name) and press `Enter`.

### Manual Installation

1. Open your Sublime Text packages folder via **Sublime Text > Settings... > Browse Packages...** (`Preferences > Browse Packages...` on Windows/Linux).
2. Copy `Console.sublime-color-scheme` and `Console.sublime-theme` into `Packages/User/` (or into a `Packages/Console/` folder).

## Activation

From the Command Palette (`Cmd + Shift + P` / `Ctrl + Shift + P`):

1. Run **`UI: Select Color Scheme`** and choose **`Console`**.
2. Run **`UI: Select Theme`** and choose **`Console.sublime-theme`**.

Or add both directly to your `Preferences.sublime-settings`:

```json
{
    "color_scheme": "Console.sublime-color-scheme",
    "theme": "Console.sublime-theme"
}
```

## Author

Created by **Luis Mercado**.
