# Visual Studio Code User Settings

Path:
- `%APPDATA%\Code\User\settings.json`
- `~/.config/Code/User/settings.json`

```jsonc
{
    // default stuff...

    "editor.fontSize": 13, // on Windows
    "editor.fontSize": 12, // on Linux

    "files.eol": "\n",
    "window.restoreWindows": "none",
    "files.hotExit": "off",
    "editor.rulers": [120],
    "[git-commit]": { "editor.rulers": [50] },

    "editor.formatOnSave": false,

    "[c][cpp]": {
        "editor.defaultFormatter": "xaver.clang-format",
        // "editor.formatOnSave": false,
    },

    "[javascript]": {
        "editor.maxTokenizationLineLength": 2500,
        "editor.defaultFormatter": "xaver.clang-format",
    },

    "gitlens.hovers.enabled": false,

    // clang-format
    // see infos at https://marketplace.visualstudio.com/items?itemName=xaver.clang-format
    "clang-format.executable": "${env.PROGRAMFILES}/LLVM/bin/clang-format.exe",
    "clang-format.style": "file",
    "clang-format.fallbackStyle": "none",
    "clang-format.formatOnSave": false,
    "clang-format.formatOnType": false,
    "clang-format.arguments": [
        "-assume-filename=${workspaceFolder}/.clang-format"
    ],
}
```

prevent opening last window: [https://stackoverflow.com/a/36797180](https://stackoverflow.com/a/36797180)

ruler customisation: [https://stackoverflow.com/a/60292520](https://stackoverflow.com/a/60292520)
