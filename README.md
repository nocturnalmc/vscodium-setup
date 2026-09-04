# VSCodium Setup

## Extensions list

### Add extension marketplace according to this guide

https://github.com/VSCodium/vscodium/blob/master/docs/index.md#how-to-use-a-different-extension-gallery

Create product.json inside "~/.var/app/com.vscodium.codium/config/VSCodium" for VSCodium Flatpak

1. Atom One Light Theme by Mahmoud Ali
2. Auto Rename Tag by Jun Han
3. Better Comments by Aaron Bond
4. Codex – OpenAI’s coding agent by OpenAI
5. GitLens — Git supercharged by GitKraken
6. Material Icon Theme by Philipp Kief
7. One Dark Pro by binaryify
8. Prettier - Code formatter by Prettier
9. Tailwind CSS IntelliSense by Tailwind Labs
10. VSCode Shell-like Formatter by lumirelle

### Download JetBrainsMono Nerd Font from https://www.nerdfonts.com/font-downloads

### Extras

Add these at end of settings.json

```json
  "editor.fontSize": "number your desired font size",
  "window.zoomLevel": "number your desired zoom level"
```

### VSCode on Windows Specific

Add these to settings.json :

```json
"terminal.integrated.defaultProfile.windows": "Git Bash",
"telemetry.telemetryLevel": "off"
```
