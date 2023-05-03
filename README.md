# .vscode
Vs Code Configuration



# Settings.json
```json
{
  // "javascript.inlayHints.variableTypes.enabled": true,
  // "javascript.inlayHints.enumMemberValues.enabled": true,
  // "javascript.inlayHints.parameterNames.suppressWhenArgumentMatchesName": false,
  "javascript.inlayHints.parameterNames.enabled": "all",
  "javascript.inlayHints.functionLikeReturnTypes.enabled": true,
  "typescript.preferences.importModuleSpecifier": "project-relative",
"typescript.preferences.importModuleSpecifierEnding": "js",
  "task.quickOpen.history": 0,
  "editor.bracketPairColorization.enabled": true,
  "editor.renderWhitespace": "all",
  "editor.minimap.enabled": false,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "terminal.integrated.scrollback": 2000,
  "task.autoDetect": "off",
  "task.problemMatchers.neverPrompt": {
    "shell": true
  },
  "[yaml]": {
    "editor.quickSuggestions": {
      "other": true,
      "comments": false,
      "strings": true
    }
  },
  "git.autofetch": true,
  "terminal.integrated.fontSize": 14,
  "files.exclude": {
    "**/.git": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": true,
    "**/node_modules": true
  },
  "[javascript]": {
    "editor.tabSize": 2,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.tabSize": 2
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },
  "workbench.editor.showTabs": true,
  "terminal.integrated.fontFamily": "Menlo for Powerline,Monospace",
  "workbench.colorCustomizations": {
    "terminal.background": "#131212",
    "terminal.foreground": "#6bb8e6",
    "terminal.ansiBlack": "#000000",
    "terminal.ansiBrightBlack": "#4b4b4b",
    "terminal.ansiBlue": "#bceafa",
    "terminal.ansiBrightBlue": "#77dcff",
    "terminal.ansiCyan": "#a3e9d4",
    "terminal.ansiBrightCyan": "#a3e9d5",
    "terminal.ansiGreen": "#68f400",
    "terminal.ansiBrightGreen": "#dcf152",
    "terminal.ansiMagenta": "#f58a8d",
    "terminal.ansiBrightMagenta": "#ffb4b8",
    "terminal.ansiRed": "#ff4c41",
    "terminal.ansiBrightRed": "#ff7c77",
    "terminal.ansiWhite": "#ffffff",
    "terminal.ansiBrightWhite": "#ffffff",
    "terminal.ansiYellow": "#ffe100",
    "terminal.ansiBrightYellow": "#fff68b"
  },
  "gitlens.views.commits.showBranchComparison": false,
  "editor.semanticHighlighting.enabled": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "githubIssues.queries": [
    {
      "label": "My Issues",
      "query": "default"
    },
    {
      "label": "Created Issues",
      "query": "author:${user} state:open repo:${owner}/${repository} sort:created-desc"
    }
  ],
  "terminal.integrated.profiles.osx": {
    "zsh": {
      "path": "/bin/zsh",
      "args": ["-l", "-i"]
    }
  },
  "terminal.integrated.defaultProfile.osx": "zsh",
  "terminal.integrated.env.osx": {
    "PATH": "${env:PATH}:/usr/local/bin"
},
  "editor.renderControlCharacters": true,
  "editor.inlineSuggest.enabled": true,
  "emmet.includeLanguages": {
    "marko": "html"
},
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.codeActionsOnSave": {
    "source.fixAll": true,
    "source.fixAll.eslint": true
    // "source.organizeImports": true
  },
  "prettier.bracketSpacing": true,
  "workbench.colorTheme": "GitHub Dark Dimmed",
  "editor.suggestSelection": "first",
  "gitlens.gitCommands.skipConfirmations": ["fetch:command", "switch:command", "stash-push:command"],
  "prettier.printWidth": 150,
  "window.commandCenter": true,
  "workbench.iconTheme": "material-icon-theme",
  "githubPullRequests.pullBranch": "never",
  // "tabnine.experimentalAutoImports": true,
  "javascript.suggestionActions.enabled": false,
  "[python]": {
    "editor.defaultFormatter": "ms-python.python",
    "editor.formatOnType": true
  },
"window.zoomLevel": 2,
  "tabnine.experimentalAutoImports": true
}

```


# Tasks.json


```json

{
  "version": "2.0.0",
  "tasks": [
    {
      "label": "Name of task",
      "type": "shell",
      "command": "npm",
      "args": ["run", "watch"],
      "group": "build",
      "options": {
        "cwd": "${workspaceFolder}/<>/"
      },
      "presentation": {
        "reveal": "always",
        "panel": "shared",
        "group": "groupA"
      }
    },
    {
      "label": "Name of task",
      "type": "shell",
      "command": "npm",
      "args": ["run", "dev"],
      "group": "build",
      "options": {
        "cwd": "${workspaceFolder}/<>/"
      },
      "presentation": {
        "reveal": "always",
        "panel": "shared",
        "group": "groupA"
      }
    },

  ]
}


```
