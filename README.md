# VSCODE

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

Show/Hide side bar and panel.

| Command | Key binding |
|---|---|
| Show Explorer | cmd+shift+e |
| Show Extensions | cmd+shift+x |
| Toggle Side Bar (Explorer/Extensions) | cmd+b |
| Toggle Terminal | ctrl+` |
| Toggle Panel (Problems/Terminal/etc) | cmd+j |

#### This setting dims all editors, panel, and side bar except the one in focus.

settings.json
```
  "accessibility.dimUnfocused.enabled": true,
```
<img width="1878" alt="image" src="https://github.com/liamhennebury/vscode/assets/80056604/f63ba1cd-b74c-4867-97a2-270ad0ae61a9">

