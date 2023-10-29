# VSCODE

NOTE: Key bindings are for macOS (alt refers to the option key).

## Mouse-less navigation

#### The following key bindings allow for movement through the UI without needing the mouse.

keybindings.json
```
{
  "key": "ctrl+up",
  "command": "workbench.action.navigateUp"
},
{
  "key": "ctrl+down",
  "command": "workbench.action.navigateDown"
},
{
  "key": "ctrl+left",
  "command": "workbench.action.navigateLeft"
},
{
  "key": "ctrl+right",
  "command": "workbench.action.navigateRight"
},
{
  "key": "ctrl+=",
  "command": "workbench.action.evenEditorWidths"
},
{
  "key": "alt+[",
  "command": "workbench.action.decreaseViewWidth"
},
{
  "key": "alt+]",
  "command": "workbench.action.increaseViewWidth"
},
{
  "key": "alt+-",
  "command": "workbench.action.decreaseViewHeight"
},
{
  "key": "alt+=",
  "command": "workbench.action.increaseViewHeight"
}
```

#### Builtin key bindings (\* denotes key binding also works in Chrome) :

| Command | Key binding |
|:---|:---|
| Open next editor tab * | alt+cmd+right |
| Open previous editor tab * | alt+cmd+left |
| Close editor tab * | cmd+w |
| Move editor tab into next group | ctrl+cmd+right |
| Move editor tab into previous group | ctrl+cmd+left |
| Open recently used editor tabs in group | ctrl+tab |
| Split Editor | cmd+\ |
| Split Editor Down | cmd+k+\ |
| Open file | cmd+p |
| Show Explorer | cmd+shift+e |
| Show Extensions | cmd+shift+x |
| Show Search | cmd+shift+f |
| Toggle Side Bar (Explorer/Extensions/Search) | cmd+b |
| Toggle Terminal | ctrl+` |
| Toggle Panel (Problems/Terminal/etc) | cmd+j |

#### Dim all editors, panel, and side bar except the one in focus.

settings.json
```
  "accessibility.dimUnfocused.enabled": true,
```

Enabled:
<img width="1160" alt="enabled" src="https://github.com/liamhennebury/vscode/assets/80056604/c5513b5e-b9c5-473e-abf0-b800fca7f949">

Disabled:
<img width="1180" alt="disabled" src="https://github.com/liamhennebury/vscode/assets/80056604/a0471ba5-7a27-439e-be53-d17cf4ed66cc">
