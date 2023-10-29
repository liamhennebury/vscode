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
<img width="1160" alt="image" src="https://github.com/liamhennebury/vscode/assets/80056604/2c0c9754-4266-4de3-80fa-3448abdca280">

Disabled:
<img width="1180" alt="image" src="https://github.com/liamhennebury/vscode/assets/80056604/f032fe8c-cbd0-4e5b-bfb7-c7e012430fdb">
