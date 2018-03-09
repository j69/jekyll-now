---
layout: page
title: VSCode
permalink: /vsc/
---

### Hot Keys

⌘P Quick Open, Go to File…
⌘, User Settings
⌥↓ / ⌥↑ Move line down/up
⇧⌥↓ / ⇧⌥↑ Copy line down/up
⇧⌘K Delete line
⌘↑ / ⌘↓ Go to beginning/end of file
⌘/ Toggle line comment
⇧⌥A Toggle block comment
⌥Z Toggle word wrap
⇧⌥ + drag mouse Column (box) selection
⌘F Find
⌥⌘F Replace
⌃Space Trigger suggestion
⇧⌥F Format document
⌘K ⌘F Format selection
⌃Tab / ⌃⇧Tab Open next / previous
⌃` Show integrated terminal



### Plugins:

* Angular Language Service
* Angular v5 Snippets
* Atom One Dark theme
* Debugger for Chrome???
* MagicPython
* Python
* npm???
* npm Intellisense???
* TSlint
* flask-snippets
* dash
* go support

after this install:
 pip install pylint

 to use venv from terminal
 To use a specific interpreter, select the Python: 
 Select Interpreter command from the Command Palette (⇧⌘P).

### Settings

Preferences -> Settings - User.

```javascript
{
    "files.autoSave": "onFocusChange",
    "editor.fontSize": 14,
    "explorer.confirmDelete": false,
    "workbench.statusBar.feedback.visible": false,
    "git.confirmSync": false,
    "python.linting.pydocstyleEnabled": true,
    "workbench.colorTheme": "Atom One Dark",
    "telemetry.enableCrashReporter": false,
    "editor.renderWhitespace": "boundary",
    "editor.cursorBlinking": "phase",
    "telemetry.enableTelemetry": false,
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
    "workbench.activityBar.visible": false,
    "editor.wordWrap": "bounded",
    "editor.wordWrapColumn": 120,
    "workbench.colorCustomizations": {
        "editor.background": "#1B1B1B",
        "editor.lineHighlightBackground": "#342565"
    },
}
```