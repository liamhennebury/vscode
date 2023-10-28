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

#### Builtin key bindings:

| Command | Key binding |
|:---|:---|
| Open next editor tab | alt+cmd+right |
| Open previous editor tab | alt+cmd+left |
| Move editor tab into next group | ctrl+cmd+right |
| Move editor tab into previous group | ctrl+cmd+left |
| Close editor tab | cmd+w |
| Show Explorer | cmd+shift+e |
| Show Extensions | cmd+shift+x |
| Toggle Side Bar (Explorer/Extensions) | cmd+b |
| Toggle Terminal | ctrl+` |
| Toggle Panel (Problems/Terminal/etc) | cmd+j |

#### Dim all editors, panel, and side bar except the one in focus.

settings.json
```
  "accessibility.dimUnfocused.enabled": true,
```

Enabled:
<img width="1878" alt="image" src="https://github.com/liamhennebury/vscode/assets/80056604/f63ba1cd-b74c-4867-97a2-270ad0ae61a9">

Disabled:
<img width="1889" alt="image" src="https://github.com/liamhennebury/vscode/assets/80056604/fce92ae8-372e-40ff-90c9-c26ef22a0a95">
