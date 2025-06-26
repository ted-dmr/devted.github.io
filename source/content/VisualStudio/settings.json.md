```json
{

  "editor.cursorStyle": "line",

  "editor.cursorBlinking": "expand",

  "editor.suggestSelection": "first",

  "editor.tabCompletion": "on",

  "editor.insertSpaces": true,

  "editor.detectIndentation": false,

  "editor.fontSize": 16,

  "editor.fontFamily": "'Consolas','Fira Code','JetBrains Mono','Consolas', 'monospace'",

  "editor.fontWeight": "350",

  "editor.fontLigatures": "'ss01','ss02','ss03','ss04','ss05','ss06','zero','cv01','cv02','cv06','cv09','cv14','cv17'",

  "editor.smoothScrolling": true,

  "editor.mouseWheelZoom": true,

  /* "editor.tokenColorCustomizations": {

        "comments": "#55f",

        "strings": "#0f0",

        "keywords": "#c0c",

        "types": "#f84",

        "variables": "#aff",

        "functions": "#0ff",

        "numbers": "#ff0",

        "textMateRules": [{

                "scope": "keyword.operator",

                "settings": {

                    "foreground": "#f00"

                }

            }, {

                "scope": "punctuation",

                "settings": {

                    "foreground": "#f00"

                }

            }, {

                "scope": "variable.other.constant",

                "settings": {

                    "foreground": "#5bc"

                }

            }, {

                "scope": "variable.other.property",

                "settings": {

                    "foreground": "#ccc"

                }

            }, {

                "scope": "variable.parameter",

                "settings": {

                    "foreground": "#fc7"

                }

            }

        ]

    }, */

  "editor.bracketPairColorization.enabled": true,

  "editor.guides.bracketPairs": true,

  // "editor.guides.bracketPairsHorizontal": true,

  "editor.guides.highlightActiveBracketPair": true,

  "editor.inlineSuggest.enabled": true,

  "editor.unicodeHighlight.nonBasicASCII": false,

  /* "editor.language.colorizedBracketPairs": [

        ["[", "]"],

        ["(", ")"],

        ["{", "}"],

        [" <", ">\n"]

    ], */

  "explorer.incrementalNaming": "smart",

  "workbench.editor.tabSizing": "shrink",

  "workbench.colorTheme": "One Dark Pro Darker",

  /* "workbench.colorCustomizations": {

        "[Default Dark+]": {

            "editor.background": "#000"

        },

        "editorBracketHighlight.foreground1": "#c000ff",

        "editorBracketHighlight.foreground2": "#00f",

        "editorBracketHighlight.foreground3": "#00c0ff",

        "editorBracketHighlight.foreground4": "#00ff80",

        "editorBracketHighlight.foreground5": "#ffff00",

        "editorBracketHighlight.foreground6": "#ff4000",

        "editorBracketHighlight.foreground7": "#ff0080",

        "editorBracketHighlight.unexpectedBracket.foreground": "#f00"

    }, */

  /* "indentRainbow.colors": [

        "rgba(192, 0, 255, .25)",

        "rgba( 0, 0, 255, .25)",

        "rgba( 0, 192, 255, .25)",

        "rgba( 0, 255, 128, .25)",

        "rgba( 64, 255, 0, .25)",

        "rgba(255, 255, 0, .25)",

        "rgba(255, 64, 0, .25)",

        "rgba(255, 0, 128, .25)"

    ], */

  "files.exclude": {

    ".creator/": true,

    ".eslintignore": true,

    ".npmignore": true,

    ".prettierrc.json": true,

    ".prettierignore": true,

    ".nvmrc": true,

    ".editorconfig": true,

    "**/.DS_Store": true,

    "**/.git": true,

    "**/.vs": true,

    "**/.vscode": true,

    "**/.vsconfig": true,

    "**/*.meta": true,

    "library/": true,

    "local/": true,

    "temp/": true

  },

  "search.exclude": {

    "**/node_modules": true,

    "**/bower_components": true,

    "**/*.code-search": true,

    /* cocos creator */

    // "build/": true, // remove for pixi project

    "temp/": true,

    "library/": true,

    "**/*.anim": true

  },

  "search.useIgnoreFiles": true,

  "files.autoSave": "afterDelay",

  "files.autoSaveDelay": 180000, // ms: 1000 * 60 * 3

  "files.trimTrailingWhitespace": true,

  "files.trimFinalNewlines": true,

  "javascript.format.insertSpaceAfterConstructor": false,

  /* prettier */

  "prettier.useTabs": false,

  "prettier.tabWidth": 4,

  "prettier.singleQuote": true,

  "prettier.printWidth": 10,

  "prettier.bracketSpacing": false,

  /* Format code */

  "editor.formatOnPaste": false,

  "editor.formatOnSave": true,

  "editor.formatOnType": false,

  "code-runner.saveFileBeforeRun": true,

  "code-runner.executorMap": {

    "javascript": "node",

    "java": "cd $dir && javac $fileName -d ../bin/ && cd ../bin; java $fileNameWithoutExt; cd ../src",

    "c": "cd $dir && gcc $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",

    "cpp": "cd $dir && g++ $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",

    "objective-c": "cd $dir && gcc -framework Cocoa $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",

    "php": "php",

    "python": "python3 -u",

    "go": "go run",

    "shellscript": "bash",

    "csharp": "scriptcs",

    "typescript": "ts-node",

    "r": "Rscript"

  },

  "liveServer.settings.donotVerifyTags": true,

  "liveServer.settings.donotShowInfoMsg": true,

  "emmet.showSuggestionsAsSnippets": true,

  "emmet.excludeLanguages": [

    "markdown",

    "php"

  ],

  "emmet.triggerExpansionOnTab": true,

  "github.copilot.enable": {

    "*": true,

    "plaintext": false,

    "markdown": false,

    "scminput": false

  },

  "git-graph.defaultColumnVisibility": {

    "Commit": true,

    "Date": true,

    "Author": true

  },

  "javascript.updateImportsOnFileMove.enabled": "always",

  "rust-analyzer.hover.actions.references.enable": true,

  "vsintellicode.modify.editor.suggestSelection": "choseToUpdateConfiguration",

  "editor.codeActionsOnSave": {

    "source.fixAll.eslint": "explicit",

    // "source.addMissingImports.ts": "explicit",

    // "source.organizeImports": "explicit"

  },

  "eslint.workingDirectories": [

    {

      "mode": "auto"

    }

  ],

  "eslint.options": {

    "extensions": [

      ".js",

      ".jsx",

      "ts",

      "tsx"

    ]

  },

  "eslint.validate": [

    "javascript",

    "javascriptreact",

    "typescript",

    "typescriptreact"

  ],

  "eslint.format.enable": true,

  "eslint.alwaysShowStatus": true,

  "eslint.debug": true,

  "eslint.trace.server": "off",

  "typescript.preferences.importModuleSpecifier": "relative",

  "typescript.updateImportsOnFileMove.enabled": "always",

  "[typescript]": {

    // "editor.formatOnSave": true,

    "editor.defaultFormatter": "vscode.typescript-language-features"

  },

  // "[typescriptreact]": {

  //     // "editor.formatOnSave": true,

  //     "editor.defaultFormatter": "esbenp.prettier-vscode"

  // },

  "[jsonc]": {

    "editor.defaultFormatter": "vscode.json-language-features",

    "editor.tabSize": 2

  },

  "[javascript]": {

    "editor.defaultFormatter": "dbaeumer.vscode-eslint"

  },

  // "[javascriptreact]": {

  //     "editor.defaultFormatter": "esbenp.prettier-vscode"

  // },

  "[json]": {

    "editor.defaultFormatter": "vscode.json-language-features",

    "editor.tabSize": 2

  },

  "[shellscript]": {

    // "editor.defaultFormatter": "foxundermoon.shell-format"

  },

  "[html]": {

    "editor.defaultFormatter": "vscode.html-language-features"

  },

  "[yaml]": {

    "editor.defaultFormatter": "esbenp.prettier-vscode"

  },

  "[css]": {

    "editor.defaultFormatter": "vscode.css-language-features"

  },

  /* git config */

  "git.autoStash": true,

  "git.fetchOnPull": true,

  "git.pruneOnFetch": true,

  "git.verboseCommit": true,

  "git.autorefresh": true,

  "git.autofetch": true,

  "git.ignoreWindowsGit27Warning": true,

  /* google translate */

  "google-translate.firstLanguage": "en",

  "google-translate.serverDomain": "https://translate.google.com",

  "google-translate.secondLanguage": "vi",

  /* terminal config */

  "terminal.integrated.fontFamily": "'Consolas','Opens Sans'",

  "terminal.integrated.fontSize": 14,

  "terminal.integrated.cursorStyle": "block",

  "terminal.integrated.enableMultiLinePasteWarning": "never",

  "terminal.integrated.profiles.windows": {

    "Git Bash": {

      "path": [

        "D:\\tools\\Git\\bin\\bash.exe"

      ],

      "args": [

        "--login"

      ],

      "source": "Git Bash",

      "icon": "terminal-bash"

    },

    "PowerShell": {

      "source": "PowerShell",

      "icon": "terminal-powershell"

    },

    "Command Prompt": {

      "path": [

        "${env:windir}\\Sysnative\\cmd.exe",

        "${env:windir}\\System32\\cmd.exe"

      ],

      "args": [],

      "icon": "terminal-cmd"

    }

  },

  "terminal.integrated.defaultProfile.windows": "Git Bash",

  "terminal.integrated.defaultProfile.linux": "Git Bash",

  "terminal.integrated.defaultProfile.osx": "Git Bash",

  "terminal.integrated.suggest.builtinCompletions": {

    "pwshCode": false,

    "pwshGit": false

  },

  /* Line ending */

  "files.eol": "\n", // Unix

  "editor.renderWhitespace": "none",

  "code-eol.newlineCharacter": "¬",

  "code-eol.returnCharacter": "¤",

  "code-eol.crlfCharacter": "¤¬",

  "yaml.schemas": {

    // "file:///c%3A/Users/Admin/.vscode/extensions/atlassian.atlascode-3.0.10/resources/schemas/pipelines-schema.json": "bitbucket-pipelines.yml"

  },

  "atlascode.bitbucket.enabled": true,

  "atlascode.jira.enabled": false,

  "debug.javascript.autoAttachFilter": "disabled",

  "redhat.telemetry.enabled": true,

  "debug.internalConsoleOptions": "neverOpen",

  "sync.quietSync": true,

  "projectManager.git.baseFolders": [

    "d:\\workspace"

  ],

  "projectManager.git.ignoredFolders": [

    "node_modules",

    "out",

    "typings",

    "test"

  ],

  "projectManager.tags": [

    "Work",

    "Learning"

  ],

  "bookmarks.label.suggestion": "useWhenSelected",

  "turboConsoleLog.quote": "'",

  "projectManager.any.baseFolders": [

    "D:\\Workspace"

  ],

  "projectManager.any.ignoredFolders": [

    "node_modules",

    "out",

    "typings",

    "test",

    ".git",

    ".idea"

  ],

  "projectManager.any.maxDepthRecursion": 1,

  /* Trailing whitespace */

  "trailing-spaces.includeEmptyLines": false,

  "trailing-spaces.trimOnSave": true,

  /* todo tree */

  "todo-tree.highlights.customHighlight": {

    "TODO": {

      "background": "yellow"

    },

    "BUG": {

      "icon": "bug"

    },

    "FIXME": {

      "icon": "flame"

    }

  },

  /* File Watcher config */

  // "filewatcher.commands": [

  //     /* Auto reload build with cocos creator */

  //     {

  //         "match": "\\.ts|\\.js",

  //         "isAsync": true,

  //         "cmd": "curl http://localhost:7456/update-db", /* cocos creator v2.* */

  //         // "cmd": "curl http://localhost:7456/asset-db/refresh" /* cocos creator v3.* */,

  //         "event": "onFolderChange"

  //     }

  // ],

  /* Polacode */

  "polacode.backgroundColor": "#1E1F2B",

  /* spellcheck */

  "cSpell.enabledFileTypes": [

    "!markdown",

    "!plaintext"

  ],

  "cSpell.userWords": [

    "allways",

    "bigwin",

    "ccclass",

    "Childs",

    "copyfiles",

    "Deactive",

    "dpjled",

    "drawcall",

    "endindex",

    "endregion",

    "esbenp",

    "Fetchable",

    "FIXEDH",

    "FIXEDW",

    "FIXEDWH",

    "fnames",

    "fontfaceobserver",

    "Freegame",

    "freespin",

    "grted",

    "Gsap",

    "ingame",

    "interactable",

    "KAIO",

    "Minigame",

    "minigames",

    "onfade",

    "onloaderror",

    "onorientation",

    "onplayerror",

    "onpos",

    "onrate",

    "onseek",

    "onstereo",

    "onunlock",

    "onvolume",

    "outfile",

    "payline",

    "Paylines",

    "paytable",

    "phong",

    "Pixi",

    "pixijs",

    "renderable",

    "Respin",

    "ROBOTO",

    "skel",

    "spector",

    "spritesheet",

    "Tinify",

    "topo",

    "tsup",

    "unclipping",

    "unlimit",

    "Unlocker",

    "webpackbar",

    "winline",

    "Winlines"

  ],

  /* trusted files */

  "security.workspace.trust.untrustedFiles": "open",

  "workbench.list.defaultFindMode": "filter",

  "cSpell.enabled": true,

  "git.confirmSync": false,

  "npm.keybindingsChangedWarningShown": true,

  "gitlens.advanced.messages": {

    "suppressLineUncommittedWarning": true

  },

  "editor.acceptSuggestionOnEnter": "smart",

  "tabnine.experimentalAutoImports": true,

  /* auto check error */

  // "typescript.tsserver.experimental.enableProjectDiagnostics": true

  "turboConsoleLog.logType": "warn",

  "turboConsoleLog.includeFileNameAndLineNum": false,

  "turboConsoleLog.insertEmptyLineAfterLogMessage": true,

  "CodeGPT.maxTokens": 2048,

  "explorer.confirmDragAndDrop": false,

  "git.branchProtection": [

    "master",

    "main",

    "prod",

    "product",

    "production"

  ],

  "git.rebaseWhenSync": true,

  "diffEditor.renderSideBySide": false,

  "diffEditor.ignoreTrimWhitespace": true,

  "cSpell.diagnosticLevel": "Warning",

  "cSpell.showAutocompleteSuggestions": true,

  "typescript.preferences.quoteStyle": "single",

  "javascript.preferences.quoteStyle": "single",

  "javascript.format.semicolons": "insert",

  "typescript.format.semicolons": "insert",

  "workbench.productIconTheme": "fluent-icons",

  "typescript.tsserver.log": "verbose",

  "terminal.integrated.scrollback": 100000,

  "npm.packageManager": "yarn",

  "peacock.favoriteColors": [

    {

      "name": "Angular Red",

      "value": "#dd0531"

    },

    {

      "name": "Azure Blue",

      "value": "#007fff"

    },

    {

      "name": "JavaScript Yellow",

      "value": "#f9e64f"

    },

    {

      "name": "Mandalorian Blue",

      "value": "#1857a4"

    },

    {

      "name": "Node Green",

      "value": "#215732"

    },

    {

      "name": "React Blue",

      "value": "#61dafb"

    },

    {

      "name": "Something Different",

      "value": "#832561"

    },

    {

      "name": "Svelte Orange",

      "value": "#ff3d00"

    },

    {

      "name": "Vue Green",

      "value": "#42b883"

    }

  ],

  "sakai-icons.hidesExplorerArrows": false,

  "workbench.iconTheme": "bearded-icons",

  "editor.inlineSuggest.showToolbar": "always",

  "github.copilot.editor.enableAutoCompletions": true,

  "debug.showVariableTypes": true,

  "diffEditor.experimental.useTrueInlineView": true,

  "workbench.editorAssociations": {

    "*.copilotmd": "vscode.markdown.preview.editor",

    "*.zip": "default"

  },

  "remove-empty-lines.allowedNumberOfEmptyLines": 1,

  "remove-empty-lines.runOnSave": true,

  "explorer.confirmPasteNative": false,

  "explorer.confirmDelete": false,

  "[markdown]": {

    "editor.defaultFormatter": "yzhang.markdown-all-in-one"

  },

  "git.openRepositoryInParentFolders": "never",

  "better-comments.tags": [

    {

      "tag": "TODO:",

      "color": "#EA580C",

      "strikethrough": false,

      "backgroundColor": "transparent"

    },

    {

      "tag": "FIXME:",

      "color": "#FF2D00",

      "strikethrough": false,

      "backgroundColor": "transparent"

    },

    {

      "tag": "BUG:",

      "color": "#9333EA",

      "strikethrough": false,

      "backgroundColor": "transparent"

    },

    {

      "tag": "HACK:",

      "color": "#C026D3",

      "strikethrough": false,

      "backgroundColor": "transparent"

    },

    {

      "tag": "NOTE:",

      "color": "#2563EB",

      "strikethrough": false,

      "backgroundColor": "transparent"

    },

    {

      "tag": "INFO:",

      "color": "#0EA5E9",

      "strikethrough": false,

      "backgroundColor": "transparent"

    },

    {

      "tag": "IDEA:",

      "color": "#FFF",

      "strikethrough": false,

      "backgroundColor": "#EAB308"

    }

  ],

  "workbench.sideBar.location": "right",

}
```