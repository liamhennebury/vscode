# VSCODE - Tips & Tricks

## Mouse-less navigation

Moving between windows/tabs

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
  "key": "alt+-",
  "command": "workbench.action.decreaseViewWidth"
},
{
  "key": "alt+=",
  "command": "workbench.action.increaseViewWidth"
},
{
  "key": "alt+[",
  "command": "workbench.action.decreaseViewHeight"
},
{
  "key": "alt+]",
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
