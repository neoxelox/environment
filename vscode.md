# Themes

- Default Dark Modern - Built In
- Material Icon Theme - Philipp Kief

# Extensions

- Better C++ Syntax - Jeff Hykin
- C/C++ - Microsoft
- Container Tools - Microsoft
- CMake - Twxs
- CMake Tools - Microsoft
- Dev Containers - Microsoft
- Dotenv Official +Vault - Dotenv
- EditorConfig for VS Code- EditorConfig
- ESLint - Microsoft
- Espressif IDF - Espressif Systems
- Even Better TOML - Tamasfe
- Git Blame - Wade Anderson
- Git Graph - Mhutchie
- Go - Go Team at Google
- Jupyter (Extension Pack) - Microsoft
- Live Sass Compiler - Glenn Marks
- Live Server - Ritwick Dey
- Makefile Tools - Microsoft
- GitHub Markdown Preview (Extension Pack) - Matt Bierner
- Peacock - John Papa
- Polacode - P & P
- PostCSS Language Support - Csstools
- Prettier - Prettier
- Pylance - Microsoft
- Pyright - Microsoft
- Python - Microsoft
- Python Debugger - Microsoft
- Remote - SSH - Microsoft
- Remote - SSH: Editing Configuration Files - Microsoft
- Remote Explorer - Microsoft
- Ruff - Astral Software
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

> This configuration also applies to Cursor
> Espressif IDF extension configuration is generated automatically and depends on the system

```json
{
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[dockercompose]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[go]": {
    "editor.defaultFormatter": "golang.go"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonl]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[python]": {
    "editor.defaultFormatter": "charliermarsh.ruff"
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[postcss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[svelte]": {
    "editor.defaultFormatter": "svelte.svelte-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[yaml]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "diffEditor.renderSideBySide": true,
  "dotenv.enableAutocloaking": false,
  "editor.bracketPairColorization.enabled": true,
  "editor.codeActionsOnSave": {
    "source.fixAll": "explicit",
    "source.organizeImports": "explicit"
  },
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.fontFamily": "Menlo, Monaco, 'Courier New', monospace",
  "editor.fontSize": 14,
  "editor.formatOnSave": true,
  "editor.guides.bracketPairs": "active",
  "editor.guides.bracketPairsHorizontal": "active",
  "editor.guides.highlightActiveBracketPair": true,
  "editor.guides.highlightActiveIndentation": true,
  "editor.guides.indentation": true,
  "editor.tokenColorCustomizations": { "textMateRules": [] },
  "editor.inlineSuggest.enabled": true,
  "editor.minimap.enabled": false,
  "editor.quickSuggestions": {
    "comments": "on",
    "other": "on",
    "strings": "on"
  },
  "editor.suggestSelection": "first",
  "eslint.format.enable": true,
  "eslint.validate": ["javascript", "javascriptreact", "typescript", "typescriptreact", "html", "vue", "svelte"],
  "go.formatTool": "goimports",
  "go.lintTool": "golangci-lint",
  "go.toolsManagement.autoUpdate": true,
  "go.useLanguageServer": true,
  "liveServer.settings.donotShowInfoMsg": true,
  "peacock.showColorInStatusBar": false,
  "prettier.endOfLine": "auto",
  "prettier.printWidth": 120,
  "prettier.semi": true,
  "prettier.singleQuote": false,
  "prettier.tabWidth": 2,
  "prettier.trailingComma": "all",
  "prettier.useTabs": false,
  "python.analysis.autoImportCompletions": false,
  "python.analysis.typeCheckingMode": "strict",
  "python.languageServer": "Pylance",
  "ruff.fixAll": true,
  "ruff.enable": true,
  "ruff.lineLength": 120,
  "jupyter.askForKernelRestart": false,
  "redhat.telemetry.enabled": false,
  "scss.lint.unknownAtRules": "ignore",
  "sql-formatter.dialect": "sql",
  "sql-formatter.linesBetweenQueries": 1,
  "sql-formatter.uppercase": true,
  "svelte.enable-ts-plugin": true,
  "tailwindCSS.experimental.configFile": {
    ".tailwindrc.cjs": "**/*",
    "tailwind.config.cjs": "**/*",
    "tailwind.config.js": "**/*",
    "tailwind.config.ts": "**/*"
  },
  "liveSassCompile.settings.showOutputWindowOn": "Error",
  "cmake.showOptionsMovedNotification": false,
  "window.zoomLevel": 0,
  "workbench.colorTheme": "Default Dark Modern",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.editor.enablePreview": false,
  "workbench.startupEditor": "none",
  "cursor.cpp.enablePartialAccepts": true,
  "cursor.general.gitGraphIndexing": "enabled",
  "cursor.diffs.useCharacterLevelDiffs": true,
  "cursor.terminal.usePreviewBox": true,
  "cursor.cmdk.useThemedDiffBackground": true
}
```
