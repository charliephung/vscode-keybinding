// Place your key bindings in this file to override the defaultsauto[]

```javascript
[
  {
    "key": "ctrl+s",
    "command": "editor.action.formatDocument",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+s",
    "command": "workbench.action.files.saveFiles",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+numpad_multiply",
    "command": "workbench.action.joinAllGroups"
  },
  {
    "key": "ctrl+shift+h",
    "command": "editor.action.triggerParameterHints",
    "when": "editorHasSignatureHelpProvider && editorTextFocus"
  },
  {
    "key": "ctrl+s",
    "command": "workbench.action.files.saveAll"
  },
  {
    "key": "ctrl+delete",
    "command": "cursorHome",
    "when": "textInputFocus"
  },
  {
    "key": "ctrl+pageDown",
    "command": "cursorEnd",
    "when": "textInputFocus"
  },
  {
    "key": "ctrl+home",
    "command": "cursorTop",
    "when": "textInputFocus"
  },
  {
    "key": "ctrl+end",
    "command": "cursorBottom",
    "when": "textInputFocus"
  },
  {
    "key": "ctrl+numpad1",
    "command": "workbench.action.focusFirstEditorGroup"
  },

  {
    "key": "ctrl+numpad0",
    "command": "workbench.action.focusSideBar"
  },

  {
    "key": "ctrl+numpad2",
    "command": "workbench.action.focusSecondEditorGroup",
    "when": "editorFocus"
  },

  {
    "key": "ctrl+numpad3",
    "command": "workbench.action.focusThirdEditorGroup",
    "when": "editorFocus"
  },

  {
    "key": "ctrl+numpad4",
    "command": "workbench.action.focusFourthEditorGroup"
  },

  {
    "key": "ctrl+numpad5",
    "command": "workbench.action.focusFifthEditorGroup"
  },

  {
    "key": "ctrl+numpad6",
    "command": "workbench.action.focusSixthEditorGroup"
  },

  {
    "key": "ctrl+numpad7",
    "command": "workbench.action.focusSeventhEditorGroup"
  },

  {
    "key": "ctrl+numpad8",
    "command": "workbench.action.focusEighthEditorGroup"
  },

  {
    "key": "alt+numpad0",
    "command": "workbench.action.lastEditorInGroup"
  },
  {
    "key": "ctrl+numpad_divide",
    "command": "workbench.action.splitEditor"
  },
  {
    "key": "alt+numpad1",
    "command": "workbench.action.openEditorAtIndex1"
  },

  {
    "key": "alt+numpad2",
    "command": "workbench.action.openEditorAtIndex2"
  },

  {
    "key": "alt+numpad3",
    "command": "workbench.action.openEditorAtIndex3"
  },

  {
    "key": "alt+numpad4",
    "command": "workbench.action.openEditorAtIndex4"
  },

  {
    "key": "alt+numpad5",
    "command": "workbench.action.openEditorAtIndex5"
  },

  {
    "key": "alt+numpad6",
    "command": "workbench.action.openEditorAtIndex6"
  },

  {
    "key": "alt+numpad7",
    "command": "workbench.action.openEditorAtIndex7"
  },

  {
    "key": "alt+numpad8",
    "command": "workbench.action.openEditorAtIndex8"
  },

  {
    "key": "alt+numpad9",
    "command": "workbench.action.openEditorAtIndex9"
  },
  {
    "key": "ctrl+d ctrl+right",
    "command": "deleteAllRight",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+k ctrl+k",
    "command": "-deleteAllRight",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+d ctrl+d",
    "command": "editor.action.deleteLines",
    "when": "editorFocus"
  },
  {
    "key": "ctrl+shift+k",
    "command": "-editor.action.deleteLines",
    "when": "editorFocus"
  },
  {
    "key": "ctrl+d ctrl+left",
    "command": "deleteAllLeft"
  }
]
```
