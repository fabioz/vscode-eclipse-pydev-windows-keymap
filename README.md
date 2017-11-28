# vscode-eclipse-pydev-windows-keymap README

The idea behind the keybindings is making it as similar as possible to Eclipse on Windows with some customizations from PyDev.

-- Note that the bindings used are the ones from Eclipse on Windows even on different platforms.

## Keyboard shortcuts notes:

Keyboard shortcuts defined here try to follow Eclipse/PyDev on Windows as close as possible, however, some differences are noted because some actions may not have an exact match.

- Open File: usually unbound on Eclipse, set to Ctrl+Alt+O
- Save As: usually unbound on Eclipse, set to Ctrl+Alt+S

- There's no differentiation between a simple find and a find/replace in eclipse, so, accelerators after the find is available are bound.
    I.e.: Ctrl+F opens find window and then:
        - Alt+E goes to replace
        - Alt+R goes to replace (actually differs from Eclipse, but there's no replace without going to next in VsCode)
        - Alt+N finds next
        - Alt+D replaces and goes to next
        - Alt+A replaces all

- Shift+Alt+A cannot be used to rectangular selection because VsCode doesn't really have a start/begin mode for rectangular select and it's not possible to do "shift+alt+a+down" as a single command, as that'd be 2 keystrokes (so, it was kept as the default "ctrl+shift+alt+arrow keys).

## Release Notes

See CHANGELOG.md for information on releases.

## Keybindings mapped