# My Visual Studio Code Settings

I personally use this settings for my VS Code

## My Settings

```js
{
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "blade.format.enable": true,
    "breadcrumbs.enabled": true,
    "dart.closingLabels": false,
    "dart.previewFlutterUiGuides": true,
    "debug.toolBarLocation": "floating",
    "editor.autoIndent": "advanced",
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
    "editor.cursorBlinking": "solid",
    "editor.cursorStyle": "line",
    "editor.cursorWidth": 5,
    "editor.detectIndentation": false,
    "editor.fontFamily": "Dank Mono, Menlo, Monaco, 'Courier New', monospace",
    "editor.fontLigatures": true,
    "editor.fontSize": 16,
    "editor.fontWeight": "400",
    "editor.formatOnPaste": false,
    "editor.formatOnSave": true,
    "editor.formatOnType": false,
    "editor.glyphMargin": true,
    "editor.letterSpacing": 0.5,
    "editor.lineHeight": 25,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.renderWhitespace": "all",
    "editor.scrollBeyondLastLine": false,
    "editor.selectionHighlight": false,
    "editor.snippetSuggestions": "bottom",
    "editor.suggestSelection": "first",
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
                        "storage.type",
                        "support.class",
                        "support.type",
                        "variable.language",
                        "variable.parameter"
                    ],
                    "settings": {
                        "fontStyle": "italic"
                    }
                }
            ]
        }
    },
    "emmet.includeLanguages": {
        "javascript": "javascriptreact"
    },
    "emmet.showSuggestionsAsSnippets": true,
    "eslint.alwaysShowStatus": true,
    "eslint.run": "onType",
    "explorer.confirmDragAndDrop": false,
    "files.eol": "\n",
    "files.exclude": {
        "**/.classpath": true,
        "**/.dart_tool": true,
        "**/.factorypath": true,
        "**/.idea": true,
        "**/.next/**": true,
        "**/.project": true,
        "**/.settings": true,
        "**/node_modules/**": true,
        "**/plugins": true,
        "apk": true,
        "vendor": true
    },
    "files.insertFinalNewline": true,
    "files.trimFinalNewlines": true,
    "files.trimTrailingWhitespace": true,
    "intelephense.completion.fullyQualifyGlobalConstantsAndFunctions": true,
    "intelephense.completion.insertUseDeclaration": true,
    "intelephense.completion.triggerParameterHints": true,
    "intelephense.diagnostics.undefinedMethods": false,
    "intelephense.diagnostics.undefinedFunctions": false,
    "intelephense.diagnostics.undefinedTypes": false,
    "intelephense.files.exclude": [
        "**/.DS_Store/**",
        "**/.git/**",
        "**/.hg/**",
        "**/.svn/**",
        "**/CVS/**",
        "**/bower_components/**",
        "**/database/migrations/**",
        "**/node_modules/**",
        "**/resources/views/**",
        "**/storage",
        "**/storage/**",
        "**/storage/framework/views/**",
        "**/tests/**",
        "_ide_helper.php",
        "_ide_helper_models"
    ],
    "intelephense.format.enable": true,
    "intelephense.stubs": [
        "Core",
        "PDO",
        "Phar",
        "Reflection",
        "SPL",
        "SimpleXML",
        "Zend OPcache",
        "apache",
        "bcmath",
        "bz2",
        "calendar",
        "com_dotnet",
        "ctype",
        "curl",
        "date",
        "dba",
        "dom",
        "enchant",
        "exif",
        "fileinfo",
        "filter",
        "fpm",
        "ftp",
        "gd",
        "hash",
        "iconv",
        "imap",
        "interbase",
        "intl",
        "json",
        "ldap",
        "libxml",
        "mbstring",
        "mcrypt",
        "meta",
        "mssql",
        "mysqli",
        "oci8",
        "odbc",
        "openssl",
        "pcntl",
        "pcre",
        "pdo_ibm",
        "pdo_mysql",
        "pdo_pgsql",
        "pdo_sqlite",
        "pgsql",
        "posix",
        "pspell",
        "readline",
        "recode",
        "redis",
        "regex",
        "session",
        "shmop",
        "snmp",
        "soap",
        "sockets",
        "sodium",
        "sqlite3",
        "standard",
        "superglobals",
        "sybase",
        "sysvmsg",
        "sysvsem",
        "sysvshm",
        "tidy",
        "tokenizer",
        "wddx",
        "xml",
        "xmlreader",
        "xmlrpc",
        "xmlwriter",
        "zip",
        "zlib"
    ],
    "intelephense.telemetry.enabled": false,
    "intelephense.trace.server": "messages",
    "javascript.updateImportsOnFileMove.enabled": "always",
    "material-icon-theme.folders.associations": {
        "bloc": "controller",
        "global_state": "global",
        "state": "controller",
        "ui": "layout",
        "widgets": "components"
    },
    "newFile.defaultBaseFileName": "project",
    "newFile.expandBraces": false,
    "newFile.relativeTo": "file",
    "newFile.rootDirectory": "~",
    "newFile.showPathRelativeTo": "project",
    "php-docblocker.author": {
        "email": "asyrafhussin4@gmail.com",
        "name": "Asyraf Hussin"
    },
    "php-docblocker.qualifyClassNames": true,
    "php-docblocker.returnGap": true,
    "php.suggest.basic": false,
    "php.validate.enable": false,
    "phpcs.autoConfigSearch": true,
    "phpcs.enable": true,
    "phpcs.ignorePatterns": [
        "**/.DS_Store/**",
        "**/.git/**",
        "**/.hg/**",
        "**/.svn/**",
        "**/CVS/**",
        "**/bower_components/**",
        "**/database/migrations/**",
        "**/node_modules/**",
        "**/resources/views/**",
        "**/storage/**",
        "**/storage/framework/views/**",
        "**/tests/**",
        "**/vendor",
        "_ide_helper.php",
        "_ide_helper_models"
    ],
    "phpcs.showSources": true,
    "phpcs.showWarnings": true,
    "phpcs.standard": "./phpcs.xml",
    "prettier.prettierPath": "/usr/local/lib/node_modules/prettier",
    "search.collapseResults": "alwaysCollapse",
    "search.exclude": {
        "**/.git": true,
        "**/bower_components": true,
        "**/node_modules": true,
        "**/storage": true,
        "**/tests": true,
        "_ide_helper.php": true,
        "_ide_helper_models.php": true,
        "package-lock.json": true
    },
    "search.showLineNumbers": true,
    "terminal.integrated.fontFamily": "Dank Mono",
    "terminal.integrated.fontSize": 14,
    "terminal.integrated.macOptionIsMeta": true,
    "typescript.updateImportsOnFileMove.enabled": "always",
    "vsicons.dontShowNewVersionMessage": true,
    "workbench.colorTheme": "One Dark Flatland Monokai",
    "workbench.editor.enablePreview": false,
    "workbench.editor.enablePreviewFromQuickOpen": false,
    "workbench.editor.tabCloseButton": "right",
    "workbench.fontAliasing": "auto",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "newUntitledFile",
    "workbench.tree.renderIndentGuides": "always",
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
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
