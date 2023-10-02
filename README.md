# My VSCode Settings 🌟

Welcome to my adorable VSCode settings repository! Here, you'll find my carefully crafted `settings.json` file that make my coding experience both efficient and cute! 😊

## 🌸 settings.json
<!-- SETTINGS_JSON -->

```json
// Version : 2023-10-02 23:33
{
  // Color Settings ===============================================================
  "workbench.colorCustomizations": {
    "editor.lineHighlightBorder": "#b300aa",
    "editorBracketMatch.border": "#fffb00",
    "editorBracketMatch.background": "#ffee00",
    "editor.lineHighlightBackground": "#803c6b",
    "activityBar.activeBackground": "#b16c8e",
    "activityBar.background": "#b16c8e",
    "activityBar.foreground": "#15202b",
    "activityBar.inactiveForeground": "#15202b99",
    "activityBarBadge.background": "#afc897",
    "activityBarBadge.foreground": "#15202b",
    "commandCenter.border": "#e7e7e799",
    "panel.border": "#b16c8e",
    "sash.hoverBorder": "#b16c8e",
    "sideBar.border": "#b16c8e",
    "statusBar.background": "#995174",
    "statusBar.foreground": "#e7e7e7",
    "statusBarItem.hoverBackground": "#b16c8e",
    "statusBarItem.remoteBackground": "#995174",
    "statusBarItem.remoteForeground": "#e7e7e7",
    "tab.activeBorder": "#b16c8e",
    "titleBar.activeBackground": "#995174",
    "titleBar.activeForeground": "#e7e7e7",
    "titleBar.inactiveBackground": "#99517499",
    "titleBar.inactiveForeground": "#e7e7e799"
  },

  // Editor Settings ===============================================================
  "editor.autoIndent": "full",
  "editor.cursorBlinking": "smooth",
  "editor.fontFamily": "Cascadia Mono",
  "editor.fontLigatures": true,
  "editor.mouseWheelZoom": true,
  "editor.multiCursorModifier": "alt",
  "editor.renderControlCharacters": true,
  "editor.renderWhitespace": "all",
  "editor.smoothScrolling": true,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.tabSize": 2,
  "editor.fontWeight": "900",
  "editor.minimap.enabled": false,
  "editor.suggestSelection": "first",
  "editor.formatOnPaste": true,
  "editor.formatOnType": true,
  "editor.inlineSuggest.enabled": true,
  "editor.guides.indentation": true,
  // Turn scroll off. 😄
  "editor.cursorSurroundingLines": 100,

  // Files Settings =================================================================
  "files.eol": "
",
  "files.trimTrailingWhitespace": true,
  "files.autoSave": "onFocusChange",

  // Window and UI Settings ========================================================
  "window.title": "${rootName}${separator}${activeEditorShort}",
  "window.menuBarVisibility": "toggle",
  "window.openFilesInNewWindow": "on",
  "window.startupEditor": "none",

  // Explorer and Sidebar Settings ==================================================
  "explorer.openEditors.visible": 1,
  "explorer.sortOrder": "type",
  "workbench.sideBar.location": "right",
  "workbench.tree.indent": 15,

  // Search and Quick Open Settings ===============================================
  "search.quickOpen.includeSymbols": true,
  "search.showLineNumbers": true,

  // Terminal Settings ============================================================
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.copyOnSelection": true,
  "terminal.integrated.fontSize": 13,
  "terminal.integrated.tabFocusMode": false,

  // Todo Highlighter Settings ======================================================
  "todohighlight.isEnable": true,
  "todohighlight.isCaseSensitive": true,
  "todohighlight.keywords": [
    {
      "text": "TODO:",
      "color": "blue",
      "overviewRulerColor": "grey"
    },
  ],
  "todohighlight.defaultStyle": {
    "color": "red",
    "cursor": "pointer",
    "isWholeLine": true
  },
  "todohighlight.include": [
    "**/*.js",
    "**/*.jsx",
    "**/*.ts",
    "**/*.tsx",
    "**/*.html",
    "**/*.php",
    "**/*.css",
    "**/*.scss"
  ],
  "todohighlight.exclude": [
    "**/node_modules/**",
    "**/bower_components/**",
    "**/dist/**",
    "**/build/**",
    "**/.vscode/**",
    "**/.github/**",
    "**/_output/**",
    "**/*.min.*",
    "**/*.map",
    "**/.next/**"
  ],
  "todohighlight.maxFilesForSearch": 5120,
  "todohighlight.toggleURI": false,

  // Extension Settings ===========================================================
  "extensions.ignoreRecommendations": true,
  "extensions.autoUpdate": false,
  "extensions.autoCheckUpdates": true,

  // Git Settings ==================================================================
  "git.autofetch": true,

  // Workbench Settings ===========================================================
  "workbench.commandPalette.preserveInput": true,
  "workbench.editor.closeOnFileDelete": true,
  "workbench.editor.enablePreview": false,
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "workbench.editor.highlightModifiedTabs": true,
  "workbench.editor.labelFormat": "short",
  "workbench.editor.revealIfOpen": true,
  "workbench.editor.tabSizing": "shrink",
  "workbench.editor.limit.enabled": true,

  // Zen Mode Settings ============================================================
  "zenMode.fullScreen": true,
  "zenMode.hideActivityBar": false,
  "zenMode.hideStatusBar": false,
  "zenMode.hideTabs": false,
  "zenMode.centerLayout": false,
  "zenMode.silentNotifications": false,
  "zenMode.hideLineNumbers": false,

  // Miscellaneous Settings ========================================================
  "update.mode": "manual",
  "telemetry.telemetryLevel": "off",
  "gitlens.telemetry.enabled": false,
  "notebook.breadcrumbs.showCodeCells": false,

  // Debug Settings ===============================================================
  "debug.javascript.autoAttachFilter": "disabled",

  // Screencast Mode Settings ======================================================
  "screencastMode.fontSize": 20,
  "screencastMode.keyboardOverlayTimeout": 500,
  "screencastMode.mouseIndicatorSize": 30,
  "screencastMode.verticalOffset": 80,
  "screencastMode.mouseIndicatorColor": "#6495ed"
}
```
