---
layout: page
title: Visual Stusio Code settings
permalink: /vsc/
---

### Hot Keys

* ⌘P Quick Open, Go to File…
* ⌘, User Settings
* ⌥↓ / ⌥↑ Move line down/up
* ⇧⌥↓ / ⇧⌥↑ Copy line down/up
* ⇧⌘K Delete line
* ⌘/ Toggle line comment
* ⌘G Fin next
* ⇧⌥ + drag mouse Column (box) selection
* ⌃Space Trigger suggestion

### Terminal
Use iTerm2 for CLI RUN and DB BROWSE

### Plugins:

* Auto Rename Tag
* Dracula Official (soft theme)
* Rainbow CSV

additionaly for Angular!
* (Angular Language Service)
* (Angular v5 Snippets)
* (TSlint)

### Settings

Preferences -> Settings - User.

```javascript
{
    "files.autoGuessEncoding": true,
    "explorer.confirmDelete": false,
    "git.confirmSync": false,
    "telemetry.enableCrashReporter": false,
    "editor.cursorBlinking": "phase",
    "telemetry.enableTelemetry": false,
    "files.trimTrailingWhitespace": true,
    "files.exclude": {
        ".cache": true,
        ".ropeproject": true,
        ".vscode": true,
        "**/__pycache__": true,
        "**/._*": true,
        "**/.idea": true,
        "**/.pytest_cache": true,
        "**/*.pyc": true,
        "node_modules/": true,
        "venv": true
    },
    "terminal.integrated.fontSize": 16,
    "terminal.integrated.cursorBlinking": true,
    "terminal.integrated.copyOnSelection": true,
    "terminal.integrated.cursorStyle": "block",
    "editor.wordWrap": "on",
    "editor.wordWrapColumn": 100,
    "git.autofetch": true,
    "window.zoomLevel": 0,
    "workbench.activityBar.visible": true,
    "files.associations": {
        "*.txt": "c"
    },
    "editor.multiCursorModifier": "ctrlCmd",
    "git.enableSmartCommit": true,
    "workbench.statusBar.feedback.visible": false,
    "files.autoSave": "afterDelay",
    "editor.fontSize": 18,
    "search.location": "panel",
    "workbench.colorTheme": "Dracula Soft",
    "editor.mouseWheelZoom": true,
    "workbench.sideBar.location": "left",
    "window.titleBarStyle": "native",
    "editor.minimap.enabled": false,
    "search.showLineNumbers": true,
    "editor.suggestSelection": "first"
}
```