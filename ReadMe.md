# AutoHotkey-Template

An AutoHotkey v2 script template providing a structured, modifier-layer hotkey taxonomy for building keyboard automation systems on Windows.

## Purpose

Most AutoHotkey scripts grow organically into hard-to-maintain monoliths.
This template is my own code section & keyboard modifier-layer system that has emerged over time.
May this template assist others in staying organized.

## Features

- AHK v2 syntax throughout
- Structured modifier-layer hotkey taxonomy
- Organized function subcategories
- Disabled code block pattern for safe scaffolding
- Dependency and metadata documentation standard

## Modifier Layer Taxonomy

| Layer | Modifier | Intended Use |
|---|---|---|
| Remapped Keys | varies | Key reassignments |
| GUI Commands | Alt + Click | Mouse-driven UI actions |
| Simple Commands | Alt + Shift | Lightweight single actions |
| Process Commands | Ctrl + Shift | Loop or input-driven processes |
| Text | Ctrl + Alt + Shift | Text entry and manipulation |
| Operating System | Win + Ctrl | OS-level controls |
| Applications | Win + Alt | Application-specific actions |
| Desktop Applications | Win + Ctrl + Shift | Classic/desktop app launchers |
| Modern Applications | Win + Alt + Shift | UWP/modern app launchers |
| Algorithms | Win + Ctrl + Alt | Complex multi-step routines |

## Requirements

- [AutoHotkey v2](https://www.autohotkey.com/docs/v2/)

## Usage

1. Download `AutoHotkey-Template.ahk`.
2. Rename it to reflect your script's purpose.
3. Fill in each section with your hotkeys and functions.
4. Optionally place the renamed file in your Windows Startup folder:
   `%USERPROFILE%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup`.

## Startup Note

Windows can run multiple `.ahk` files simultaneously, each with its own tray icon.
Files with the `.ahk` extension run by double-clicking.
AutoHotkey can run scripts located in any folder.

## License

MIT
