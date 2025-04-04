# VSCODE Settings

⚙️ This is my personal Visual Studio Code settings which is cleaner than the default settings, I think 😆

## Fonts

- English: <a href="https://www.nerdfonts.com/font-downloads" alt="Nerd Fonts URL">Nerd Fonts</a> <i>(Choose the one you prefer!)</i>
- Khmer: <a href="https://fonts.google.com/specimen/Kantumruy+Pro" alt="Kantumruy Pro fonts">Kantumruy Pro</a> <i>(free version of Krasar Font!)</i>

## Applying Settings

Start applying settings based on your OS: <i>(Each command will backup your old settings in case you need it later.)</i>

### Windows

```powershell
code --install-extension esbenp.prettier-vscode; code --install-extension Catppuccin.catppuccin-vsc; code --install-extension Catppuccin.catppuccin-vsc-icons; mv $env:APPDATA/Code/User/settings.json $env:APPDATA/Code/User/settings.json.bak; irm "https://github.com/samithseu/vscode-settings/raw/main/settings.json" -OutFile $ENV:APPDATA/code/user/settings.json; irm "https://github.com/samithseu/vscode-settings/raw/main/keybindings.json" -OutFile $ENV:APPDATA/code/user/keybindings.json
```

### Mac

```bash
code --install-extension esbenp.prettier-vscode && code --install-extension Catppuccin.catppuccin-vsc && code --install-extension Catppuccin.catppuccin-vsc-icons && mv $HOME/Library/Application\ Support/Code/User/settings.json $HOME/Library/Application\ Support/Code/User/settings.json.bak && curl -o $HOME/Library/Application\ Support/Code/User/settings.json https://github.com/samithseu/vscode-settings/raw/main/settings.json && curl -o $HOME/Library/Application\ Support/Code/User/keybindings.json https://github.com/samithseu/vscode-settings/raw/main/keybindings.json
```

### Linux

```bash
code --install-extension esbenp.prettier-vscode && code --install-extension Catppuccin.catppuccin-vsc && code --install-extension Catppuccin.catppuccin-vsc-icons && mv $HOME/.config/Code/User/settings.json $HOME/.config/Code/User/settings.json.bak && curl -o $HOME/.config/Code/User/settings.json https://github.com/samithseu/vscode-settings/raw/main/settings.json && curl -o $HOME/.config/Code/User/keybindings.json https://github.com/samithseu/vscode-settings/raw/main/keybindings.json
```

## Result

<img src="SAMPLE.png" />
