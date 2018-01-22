# atom-keyboard-macros package

Keyboard macro extension for Atom.

# New Features

In version 0.6.0 or later, it also records the operation of the search & replace view.

# Shortcuts

```alt-,```  start recording

```alt-.```  stop recording

```alt-/```  execute macro

```alt-shift-/```  execute macro N times

```alt-b```  execute macro to the end of file (crash?)

```alt-shift-b``` execute macro from the beginning to the end of file (crash?)

# Other Methods

- atom-keyboard-macros:name_last_kbd_macro
    Give a command name to the most recently defined keyboard macro.
    You can execute it, in command palette, use 'atom-keyboard-macros:{a-command-name}'.

- atom-keyboard-macros:execute_named_macro
    Execute a named keyboard macro(see atom-keyboard-macros:name_last_kbd_macro).

- atom-keyboard-macros:save
    Save all named macros

- atom-keyboard-macros:quick_save
    Quick save all named macros

- atom-keyboard-macros:load
    Load saved macros

- atom-keyboard-macros:quick_load
    Load quick_saved macros
