# .vscode
Vs Code Configuration

# Settings.json
```json
{
  "editor.renderWhitespace": "none",
  "editor.minimap.enabled": false,
  "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "task.problemMatchers.neverPrompt": {
    "shell": true
  },
  "javascript.updateImportsOnFileMove.enabled": "always",
  "[yaml]": {
    "editor.quickSuggestions": {
      "other": true,
      "comments": false,
      "strings": true
    }
  },
  "git.autofetch": true,
  "typescript.preferences.importModuleSpecifier": "relative",
  // "editor.codeActionsOnSave": { "source.organizeImports": true },
  "editor.formatOnSave": true,
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
    "editor.tabSize": 2
  },
  "[typescriptreact]": {
    "editor.tabSize": 2
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },
  "workbench.editor.showTabs": true
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
