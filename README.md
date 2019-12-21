# My Visual Studio Code Settings

I personally use this settings for my VS Code

## My Settings

```js
{
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "breadcrumbs.enabled": true,
    "dart.closingLabels": false,
    "dart.previewFlutterUiGuides": true,
    "debug.toolBarLocation": "floating",
    "editor.autoIndent": "full",
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
    "editor.cursorBlinking": "solid",
    "editor.cursorStyle": "line",
    "editor.cursorWidth": 5,
    "editor.fontFamily": "Dank Mono, Menlo, Monaco, 'Courier New', monospace",
    "editor.fontLigatures": true,
    "editor.fontSize": 16,
    "editor.fontWeight": "400",
    "editor.formatOnPaste": true,
    "editor.formatOnSave": true,
    "editor.formatOnType": false,
    "editor.glyphMargin": true,
    "editor.letterSpacing": 0.5,
    "editor.lineHeight": 25,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.renderWhitespace": "all",
    "editor.scrollBeyondLastLine": false,
    "editor.selectionHighlight": false,
    "editor.snippetSuggestions": "top",
    "editor.tokenColorCustomizations": {
        "[One Dark Flatland Monokai]": {
            "textMateRules": [
                {
                    "scope": "entity.name.type",
                    "settings": {
                        "fontStyle": ""
                    }
                },
                {
                    "scope": [
                        "support.class",
                        "support.type",
                        "storage.type",
                        "variable.language",
                        "variable.parameter",
                    ],
                    "settings": {
                        "fontStyle": "italic"
                    }
                }
            ]
        }
    },
    "eslint.alwaysShowStatus": true,
    "eslint.run": "onType",
    "explorer.confirmDragAndDrop": false,
    "files.exclude": {
        "**/.next/**": true,
        "**/apk": true,
        "**/node_modules/**": true,
        "**/plugins": true
    },
    "files.insertFinalNewline": true,
    "files.trimFinalNewlines": true,
    "files.trimTrailingWhitespace": true,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "prettier.prettierPath": "/usr/local/lib/node_modules/prettier",
    "search.showLineNumbers": true,
    "terminal.integrated.fontFamily": "Dank Mono",
    "terminal.integrated.fontSize": 14,
    "terminal.integrated.macOptionIsMeta": true,
    "vsicons.dontShowNewVersionMessage": true,
    "workbench.colorTheme": "One Dark Flatland Monokai",
    "workbench.editor.enablePreview": false,
    "workbench.editor.tabCloseButton": "right",
    "workbench.fontAliasing": "auto",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "newUntitledFile",
    "workbench.tree.renderIndentGuides": "always",
    "zenMode.centerLayout": false
}
```

## Install Extensions

Using bash (Linux, OSX and WSL)

```bash
cat extensions.txt | xargs code --list-extensions {}
```

Windows with PowerShell

```bash
cat extensions.txt |% { code --install-extension $_}
```
