---
layout: page
title: VSCode
permalink: /vsc/
---

### Hot Keys
`shift+RMouse` = vertical select

`Ctrl + D` - select all vars

`Ctrl + H` — Replace

`Ctrl + Shift + D` - Copy code line

`F9 и Ctrl+F9` — sort strings ASC (!HUOM! = int as string)


### Plugins:
https://packagecontrol.io/ = look for new packages

`ctrl + shift +p`, type `ins`, select “Install Package”

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