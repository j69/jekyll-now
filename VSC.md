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
* ⌘↑ / ⌘↓ Go to beginning/end of file
* ⌘/ Toggle line comment
* ⇧⌥A Toggle block comment
* ⌥Z Toggle word wrap
* ⇧⌥ + drag mouse Column (box) selection
* ⌘F Find
* ⌥⌘F Replace
* ⌃Space Trigger suggestion
* ⇧⌥F Format document
* ⌘K ⌘F Format selection
* ⌃Tab / ⌃⇧Tab Open next / previous
* ⌃` Show integrated terminal



### Plugins:

* Alignment
* Angular Language Service
* Angular v5 Snippets
* Atom One Dark theme
* MagicPython
* Python
* select highlight in minimap
* TSlint

 and switch to pycodestyle (old pep8)
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
    "editor.renderWhitespace": "boundary",
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
        // "editor.background": "#1B1B1B",
        "editor.lineHighlightBackground": "#5f43bb"
    },
    "workbench.colorTheme": "Atom One Dark",
    // "python.linting.pydocstyleArgs": [
        // "--max-line-length=120",
        // "--ignore=E241",
        // "--ignore=E203",
    // ],
}
```