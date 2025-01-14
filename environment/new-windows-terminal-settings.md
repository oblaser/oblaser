
```jsonc
{
    // ...

    "copyFormatting": "none",
    "copyOnSelect": false,
    "initialPosition": "20,20",
    "initialRows": 60,

    "profiles": 
    {
        "defaults": 
        {
            "cursorHeight": 15,
            "cursorShape": "vintage",
            "font": 
            {
                "cellHeight": "1",
                "face": "Consolas",
                "size": 10.5
            },
            "padding": "1"
        },

        // ...
    }

    // ...
}
```

```jsonc
{
    "$help": "https://aka.ms/terminal-documentation",
    "$schema": "https://aka.ms/terminal-profiles-schema",
    "actions": 
    [
        {
            "command": "find",
            "id": "User.find",
            "keys": "ctrl+shift+f"
        },
        {
            "command": 
            {
                "action": "splitPane",
                "split": "auto",
                "splitMode": "duplicate"
            },
            "id": "User.splitPane.A6751878",
            "keys": "alt+shift+d"
        },
        {
            "command": 
            {
                "action": "copy",
                "singleLine": false
            },
            "id": "User.copy.644BA8F2",
            "keys": "ctrl+c"
        },
        {
            "command": "paste",
            "id": "User.paste",
            "keys": "ctrl+v"
        }
    ],
    "copyFormatting": "none",
    "copyOnSelect": false,
    "defaultProfile": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
    "initialPosition": "20,20",
    "initialRows": 60,
    "newTabMenu": 
    [
        {
            "type": "remainingProfiles"
        }
    ],
    "profiles": 
    {
        "defaults": 
        {
            "cursorHeight": 15,
            "cursorShape": "vintage",
            "experimental.retroTerminalEffect": false,
            "font": 
            {
                "cellHeight": "1",
                "face": "Consolas",
                "size": 10.5
            },
            "padding": "2"
        },
        "list": 
        [
            {
                "commandline": "%SystemRoot%\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
                "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
                "hidden": false,
                "name": "Windows PowerShell"
            },
            {
                "commandline": "%SystemRoot%\\System32\\cmd.exe",
                "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
                "hidden": false,
                "name": "Eingabeaufforderung"
            },
            {
                "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
                "hidden": false,
                "name": "Azure Cloud Shell",
                "source": "Windows.Terminal.Azure"
            },
            {
                "guid": "{2c4de342-38b7-51cf-b940-2309a097f518}",
                "hidden": false,
                "name": "Ubuntu",
                "source": "Windows.Terminal.Wsl"
            },
            {
                "guid": "{1eb055c6-2f8f-5895-b18f-3c0e54095403}",
                "hidden": false,
                "name": "Developer Command Prompt for VS 2022",
                "source": "Windows.Terminal.VisualStudio"
            },
            {
                "guid": "{3663017f-14a2-568b-b973-46c5871968c2}",
                "hidden": false,
                "name": "Developer PowerShell for VS 2022",
                "source": "Windows.Terminal.VisualStudio"
            },
            {
                "guid": "{7364cda6-3aa8-57b3-a5f9-7a5ad7512d9b}",
                "hidden": true,
                "name": "Developer Command Prompt for VS 2019",
                "source": "Windows.Terminal.VisualStudio"
            },
            {
                "guid": "{b6e369c4-1943-5c7a-b05a-0ab0142d64a3}",
                "hidden": true,
                "name": "Developer PowerShell for VS 2019",
                "source": "Windows.Terminal.VisualStudio"
            },
            {
                "guid": "{aa51e366-4812-58ce-b167-08d8963eaf2e}",
                "hidden": true,
                "name": "Developer Command Prompt for VS 2019 (2)",
                "source": "Windows.Terminal.VisualStudio"
            },
            {
                "guid": "{b3353941-2603-5f89-89c6-c48bb1cb40c2}",
                "hidden": true,
                "name": "Developer PowerShell for VS 2019 (2)",
                "source": "Windows.Terminal.VisualStudio"
            }
        ]
    },
    "schemes": [],
    "themes": []
}
```
