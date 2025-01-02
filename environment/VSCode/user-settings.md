# Visual Studio Code User (or Workspace/Project) Settings

Path:
- `%APPDATA%\Code\User\settings.json`
- `~/.config/Code/User/settings.json`

```jsonc
{
    // maybe default stuff
    // ...

    // my settings

    // "editor.fontSize": ?, // e.g. Windows 13, Linux 12
    "editor.formatOnSave": false,
    "editor.renderWhitespace": "all",
    "editor.rulers": [ 120 ],

    "files.associations": {
        "*.pjob": "shellscript",
        "potorooJob*": "shellscript",
        "*.h": "c",
    },
    "files.eol": "\n",
    "files.hotExit": "off",

    "window.restoreWindows": "none",



    // language specific

    "[c][cpp]": {
        "editor.defaultFormatter": "xaver.clang-format",
        // "editor.formatOnSave": true,
    },

    "[git-commit]": {
        "editor.rulers": [ 50 ],
    },

    "[bat]": {
        "editor.wordWrap": "wordWrapColumn",
        "editor.wordWrapColumn": 180,
    },

    "[javascript]": {
        "editor.defaultFormatter": "xaver.clang-format",
        "editor.maxTokenizationLineLength": 2500,
    },

    "[markdown]": {
        "editor.wordWrap": "wordWrapColumn",
        "editor.wordWrapColumn": 120,
    },



    // extensions

    "gitlens.hovers.enabled": false,

    // see infos at https://marketplace.visualstudio.com/items?itemName=xaver.clang-format
    // "clang-format.executable": "${env.PROGRAMFILES}/LLVM/bin/clang-format.exe",
    "clang-format.style": "file",
    "clang-format.fallbackStyle": "none",
    "clang-format.formatOnSave": false,
    "clang-format.formatOnType": false,
    "clang-format.arguments": [ "-assume-filename=${workspaceFolder}/.clang-format" ],



    // automatically added by VS Code

}
```

prevent opening last window: [https://stackoverflow.com/a/36797180](https://stackoverflow.com/a/36797180)

ruler customisation: [https://stackoverflow.com/a/60292520](https://stackoverflow.com/a/60292520)
