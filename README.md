# VSCODE Settings

This is my personal Visual Studio Code settings. ⚙️

## Required Extensions

> [!IMPORTANT]
>
> ### Extensions to install:
>
> - Color Theme: <https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc>
> - File Icon Theme: <https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc-icons>
> - CSS and JS Loader: <https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css>

## Appling Settings

1. Open your vscode, then press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>p</kbd>
2. Type in `Open User Settings (JSON)`
3. Paste the content from <a href="settings.json">settings.json</a> into your vscode settings.
4. Add the path of <a href="vscode_custom_css/styles.css">styles.css</a> file properly into `"vscode_custom_css.imports"` of your vscode settings.

Example:

```json
"vscode_custom_css.imports": [
  "file:///yours/file/path/to/vscode_custom_css/styles.css"
]
```
