
This github repo is in reference to the youtube video:
https://www.youtube.com/watch?v=gJU31hNhqOw

## Installation
``` shell
Install from windows store:
https://aka.ms/windowsterminal

If you can't then you can install via choco
choco install microsoft-windows-terminal

```

## Settings
``` shell
%LOCALAPPDATA%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json
```


## Themes
``` shell
"colorScheme" : "Solarized Light"
Campbell, One Half Dark, One Half Light, Solarized Dark, and Solarized Light.
```


## Setting your own Colors
``` shell

				#Powershell blue colors
                "background": "#013686",
                "background": "#012456",
```


## Setting a Background
``` shell
#Put image file in here:
%LOCALAPPDATA%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\RoamingState\

                "backgroundImage" : "ms-appdata:///roaming/mybackground.jpg",
                "backgroundImageOpacity" : 0.1,
                 "backgroundImageAlignment": "bottomRight",
                "backgroundImageStrechMode" : "uniform"
                # "none", "fill", "uniform", "uniformToFill"

```


## Default Keybinds
``` shell
ctrl + shift + 1-4 = new tab of the type
ctrl + shift + w = closeTab
ctrl + shift + tab = switch tabs

ctrl + +/- = adjust font size

alt+shift+ +/- = Panes

ctrl + shift + f = find
ctrl + shift + up/down  = scroll
```

## Custom Keybinds
``` shell
    "keybindings": [
        { "command" : "closeTab", "keys" : ["ctrl+w"] },
        { "command" : { "action": "splitPane", "argument": "vertical" }, "keys" : ["ctrl+shift+="] },
        { "command" : { "action": "splitPane", "argument": "horizontal" }, "keys" : ["ctrl+shift+-"] }            
    ]  
```


## Location for settings etc.
``` shell
%LOCALAPPDATA%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\

Additional Help
https://github.com/microsoft/terminal/blob/master/doc/cascadia/SettingsSchema.md
https://github.com/microsoft/terminal/blob/master/doc/user-docs/UsingJsonSettings.md

```