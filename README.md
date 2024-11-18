# VSCODE Settings

This is my personal Visual Studio Code settings. ⚙️

## Required Extensions

> [!IMPORTANT]
>
> - Color Theme: <a href="https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc">Catppuccin.catppuccin-vsc</a>
> - File Icon Theme: <a href="https://marketplace.visualstudio.com/items?itemName=Catppuccin.catppuccin-vsc-icons">Catppuccin.catppuccin-vsc-icons</a>
> - CSS and JS Loader: <a href="https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css">be5invis.vscode-custom-css</a>

## Applying Settings

1. Open your vscode, then press <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>p</kbd>
2. Type in `Open User Settings (JSON)`
3. Paste the content from <a href="settings.json">settings.json</a> into your vscode settings.
4. Add the path of <a href="vscode_custom_css/styles.css">styles.css</a> file properly into `"vscode_custom_css.imports"` of your vscode settings.

Example:

```json
"vscode_custom_css.imports": [
  "file:///yours/file/path/to/vscode_custom_css/styles.css"
]
```
