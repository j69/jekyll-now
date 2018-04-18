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

* Alignment
* Git indicators
* Python

additionaly for Ang6
* (Angular Language Service)
* (Angular v5 Snippets)
* (TSlint)

 and switch to flake8
 ⇧⌘P - python select linter, run linter

### Settings

Preferences -> Settings - User.

```javascript
{
    "files.autoSave": "onFocusChange",
    "editor.fontSize": 16,
    "explorer.confirmDelete": false,
    "workbench.statusBar.feedback.visible": false,
    "git.confirmSync": false,
    "python.linting.pydocstyleEnabled": true,
    "telemetry.enableCrashReporter": false,
    "editor.cursorBlinking": "phase",
    "telemetry.enableTelemetry": false,
    "files.trimTrailingWhitespace": true,
    "files.exclude": {
        "node_modules/": true,
        ".cache": true,
        ".idea": true,
        "venv": true,
        ".vscode": true,
        ".ropeproject": true,
        "**/._*": true,
        "**/*.pyc": true,
        "**/__pycache__": true,
    },
    "terminal.integrated.fontSize": 16,
    "terminal.integrated.cursorBlinking": true,
    "terminal.integrated.copyOnSelection": true,
    "terminal.integrated.cursorStyle": "block",
    "workbench.activityBar.visible": false,
    "editor.wordWrap": "bounded",
    "editor.wordWrapColumn": 120,
    "workbench.colorCustomizations": {
        "editor.selectionHighlightBorder": "#dfdfdf",
        "editor.selectionForeground": "#000000",
        "editor.lineHighlightBackground": "#007AD0"
    },
    "git.autofetch": true,
    "workbench.statusBar.visible": true,
    "editor.minimap.enabled": false,
    "python.linting.flake8Args": [
        "--max-line-length=120",
        "--ignore=E251",
        "--ignore=E203",
        "--ignore=E221",
        "--ignore=E251",
    ],
    "window.zoomLevel": 0
}
```