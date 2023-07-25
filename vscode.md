# Themes

- Default Dark+ Experimental - Built In
- Material Icon Theme - Philipp Kief

# Extensions

- Better C++ Syntax - Jeff Hykin
- Even Better TOML - Tamasfe
- C/C++ - Microsoft
- CMake - Twxs
- CMake Tools - Microsoft
- Dev Containers - Microsoft
- Docker - Microsoft
- Dotenv Official +Vault - Dotenv
- ESLint - Microsoft
- Espressif IDF - Espressif Systems
- Git Blame - Wade Anderson
- Git Graph - Mhutchie
- Go - Go Team at Google
- Live Sass Compiler - Glenn Marks
- Live Server - Ritwick Dey
- Makefile Tools - Microsoft
- Markdown Preview Enhanced - Yiyi Wang
- Peacock - John Papa
- Polacode - P & P
- PostCSS Language Support - Csstools
- Prettier - Prettier
- Pylance - Microsoft
- Python - Microsoft
- Remote - SSH - Microsoft
- Remote - SSH: Editing Configuration Files - Microsoft
- Remote Explorer - Microsoft
- SQL Formatter - Adpyke
- Stylelint - Stylelint
- Svelte for VSCode - Svelte
- Tailwind CSS IntelliSense - Tailwind Labs
- Thunder Client - Ranga Vadhineni
- Vscode-PDF - Tomoki1207
- YAML - Red Hat

# View

- Drag "Timeline" tab of "Explorer" into the navbar right after "Source Control"

# Configuration (CTRL+SHIFT+P "Preferences: Open Settings (JSON)")

```json
{
  "workbench.colorTheme": "Default Dark+ Experimental",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.editor.enablePreview": false,
  "editor.fontFamily": "'Cascadia Code', 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",
  "editor.fontSize": 16,
  "editor.minimap.enabled": false,
  "editor.suggestSelection": "first",
  "editor.inlineSuggest.enabled": true,
  "editor.quickSuggestions": {
    "strings": true
  },
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.fixAll.stylelint": true,
    "source.organizeImports": true
  },
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active",
  "diffEditor.renderSideBySide": true,
  "window.zoomLevel": 0,
  "peacock.showColorInStatusBar": false,
  "liveServer.settings.donotShowInfoMsg": true,
  "sql-formatter.uppercase": true,
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
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[svelte]": {
    "editor.defaultFormatter": "svelte.svelte-vscode"
  },
  "[dockercompose]": {
    "editor.defaultFormatter": "ms-azuretools.vscode-docker"
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[yaml]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "scss.lint.unknownAtRules": "ignore",
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
  "go.useCodeSnippetsOnFunctionSuggest": true,
  "go.toolsManagement.autoUpdate": true,
  "svelte.enable-ts-plugin": true
}
```
