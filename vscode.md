# Themes
- andromeda
- native macos
- material icon theme
- peacock
- FONT: `'Cascadia Code', 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'`

# Utils
- bracket pair colorizer 2
- docker
- dotenv
- draw.io
- eslint
- tslint
- git graph
- git blame
- image resizer - from menu
- live sass compiler
- live server
- live share
- live share audio
- markdown preview enhanced
- multiline tricks
- vscode-pdf
- rest client
- polacode
- prettier
- pylance
- deno
- remote - wsl
- remote - containers
- remote - ssh
- remote - ssh: editing configuration files

# Languages
- C/C++
- JS/TS
- TOML
- YAML
- GO & RECOMMENDED
- PYTHON
- VETUR

# View
- Drag "Timeline" tab of "Explorer" into the navbar right after "Source Control"

# Configuration (CTRL+SHIFT+P "Preferences: Open Settings (JSON)")
```json
{
    "workbench.colorTheme": "Native macOS - Dark Theme, Dark Editor",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.editor.enablePreview": false,
    "editor.fontFamily": "'Cascadia Code', 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",
    "editor.fontSize": 16,
    "editor.minimap.enabled": false,
    "editor.suggestSelection": "first",
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true,
        "source.organizeImports": true
    },
    "diffEditor.renderSideBySide": true,
    "window.zoomLevel": 0,
    "peacock.showColorInStatusBar": false,
    "liveServer.settings.donotShowInfoMsg": true,
    "eslint.alwaysShowStatus": true,
    "eslint.format.enable": true,
    "prettier.printWidth": 120,
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    },
    "[vue]": {
        "editor.defaultFormatter": "dbaeumer.vscode-eslint"
    },
    "python.languageServer": "Pylance",
    "python.analysis.autoImportCompletions": false,
    "python.analysis.memory.keepLibraryAst": true,
    "python.formatting.provider": "black",
    "python.formatting.blackArgs": ["--line-length=120"],
    "python.linting.mypyEnabled": true,
    "go.formatTool": "goimports",
    "go.autocompleteUnimportedPackages": true,
    "go.lintTool": "golangci-lint",
    "go.useLanguageServer": true,
    "go.useCodeSnippetsOnFunctionSuggest": true
}
```
