# VSCODE Settings

⚙️ This is my personal Visual Studio Code settings which is cleaner than the default settings, I think 😆

## Fonts

- English: <a href="https://www.nerdfonts.com/font-downloads" alt="Nerd Fonts URL">Nerd Fonts</a> <i>(Choose the one you prefer!)</i>
- Khmer: <a href="https://fonts.google.com/specimen/Kantumruy+Pro" alt="Kantumruy Pro fonts">Kantumruy Pro</a> <i>(free version of Krasar Font!)</i>

## Applying Settings

Start applying settings based on your OS: <i>(Each command will backup your old settings in case you need it later.)</i>

### Windows

```powershell
code --install-extension esbenp.prettier-vscode; code --install-extension Catppuccin.catppuccin-vsc; code --install-extension Catppuccin.catppuccin-vsc-icons; if (Test-Path "$env:APPDATA\Code\User\settings.json") { mv "$env:APPDATA\Code\User\settings.json" "$env:APPDATA\Code\User\settings.json.bak" } else { Write-Host "settings.json not found, skipping backup" }; irm "https://github.com/samithseu/vscode-settings/raw/main/settings.json" -OutFile "$env:APPDATA\Code\User\settings.json"; irm "https://github.com/samithseu/vscode-settings/raw/main/keybindings.json" -OutFile "$env:APPDATA\Code\User\keybindings.json"
```

### Mac

```bash
code --install-extension esbenp.prettier-vscode && code --install-extension Catppuccin.catppuccin-vsc && code --install-extension Catppuccin.catppuccin-vsc-icons && [ -f "$HOME/Library/Application Support/Code/User/settings.json" ] && mv "$HOME/Library/Application Support/Code/User/settings.json" "$HOME/Library/Application Support/Code/User/settings.json.bak" || echo "settings.json not found, skipping backup" && curl -L -o "$HOME/Library/Application Support/Code/User/settings.json" "https://github.com/samithseu/vscode-settings/raw/main/settings.json" && curl -L -o "$HOME/Library/Application Support/Code/User/keybindings.json" "https://github.com/samithseu/vscode-settings/raw/main/keybindings.json"
```

### Linux

```bash
code --install-extension esbenp.prettier-vscode && code --install-extension Catppuccin.catppuccin-vsc && code --install-extension Catppuccin.catppuccin-vsc-icons && [ -f "$HOME/.config/Code/User/settings.json" ] && mv "$HOME/.config/Code/User/settings.json" "$HOME/.config/Code/User/settings.json.bak" || echo "settings.json not found, skipping backup" && curl -L -o "$HOME/.config/Code/User/settings.json" "https://github.com/samithseu/vscode-settings/raw/main/settings.json" && curl -L -o "$HOME/.config/Code/User/keybindings.json" "https://github.com/samithseu/vscode-settings/raw/main/keybindings.json"
```

## Result

<img src="SAMPLE.png" />

## Other

<details>
  <summary>Personal extensions only! <i>(optional)</i> </summary>
  
  ```bash
  echo "adpyke.codesnap
amiralizadeh9480.laravel-extra-intellisense
antfu.goto-alias
astro-build.astro-vscode
bmewburn.vscode-intelephense-client
bradlc.vscode-tailwindcss
catppuccin.catppuccin-vsc
catppuccin.catppuccin-vsc-icons
codingyu.laravel-goto-view
csstools.postcss
damms005.devdb
dart-code.dart-code
dart-code.flutter
dbaeumer.vscode-eslint
dsznajder.es7-react-js-snippets
ecmel.vscode-html-css
editorconfig.editorconfig
esbenp.prettier-vscode
formulahendry.auto-rename-tag
github.copilot
github.copilot-chat
glitchbl.laravel-create-view
ihunte.laravel-blade-wrapper
jock.svg
mark-wiemer.vscode-autohotkey-plus-plus
mehedidracula.php-namespace-resolver
mikestead.dotenv
ms-python.debugpy
ms-python.python
ms-python.vscode-pylance
myriad-dreamin.tinymist
naoray.laravel-goto-components
nuxt.mdc
nuxtr.nuxt-vscode-extentions
nuxtr.nuxtr-vscode
onecentlin.laravel-blade
onecentlin.laravel-extension-pack
onecentlin.laravel5-snippets
pgl.laravel-jump-controller
qwtel.sqlite-viewer
ritwickdey.liveserver
ryannaddy.laravel-artisan
shufo.vscode-blade-formatter
supermaven.supermaven
tomoki1207.pdf
vue.volar
yoavbls.pretty-ts-errors
tamasfe.even-better-toml
" | xargs -n 1 code --install-extension
  ```
</details>
