# VSCODE Settings

This is my personal Visual Studio Code settings. ⚙️

## Required Extensions

> [!IMPORTANT]
> Install these extensions first:
>
> - Color Theme: <https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc>
> - File Icon Theme: <https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc-icons>
> - CSS and JS Loader: <https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css>

## Appling Settings

1. Open your VSCODE, then press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>p</kbd>
2. Type in `Open User Settings (JSON)`
3. Paste the content from <a href="settings.json">settings.json</a> into your VSCODE settings.
4. Add the path of this file (<a href="vscode_custom_css/styles.css">styles.css</a>) properly into `"vscode_custom_css.imports":[]` of your VSCODE settings.

Example:

```json
"vscode_custom_css.imports": [
  "file:///yours/file/path/to/vscode_custom_css/styles.css"
]
```
