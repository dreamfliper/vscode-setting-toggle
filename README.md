# Setting Toggle

## Easily toggle any VS code setting at the **click of a button**!

This extension lets you toggle any custom boolean setting using the command or the button.

Now you can quickly toggle codeLens, minimap, word-wrap, or whatever setting you want without having to remember the keybinding ;). Or assign your own keybinding to the "Setting Toggle" command.

---
<img src="https://raw.githubusercontent.com/Ho-Wan/vscode-setting-toggle/master/images/setting-toggle-img1.png" alt="setting-toggle-image1"/>


---
Status bar shows toggled setting

<img src="https://raw.githubusercontent.com/Ho-Wan/vscode-setting-toggle/v1.0.1/images/setting-toggle-status.gif" alt="setting-toggle-status.gif"/>

---
## Requirements

- The toggled setting must be a boolean. codeLens is toggled by default.
``` JSON
    "editor.codeLens": false,
```
- To toggle a custom setting, set **"setting-toggle.setting:"** to the name of the custom setting in the user settings. eg.
``` JSON
    "setting-toggle.setting": "editor.minimap.enabled",
    "editor.minimap.enabled": false,
```
- Can only save one setting to toggle at a time. (May add more if there is demand, leave a message in the repository.)
---

<img src="https://raw.githubusercontent.com/Ho-Wan/vscode-setting-toggle/v1.0.1/images/setting-toggle.gif" alt="setting-toggle-demo.gif">

---
## Settings

- `setting-toggle.setting`: The title of the toggled setting. Default is "editor.codeLens".
- `setting-toggle.icon.enabled`: Show or hide the button icon. Default is on.

---
## Known Issues

- Changes to user settings must be saved before the setting is toggled using this extension; cannot write over a modified but unsaved settings.json file.

---
