# SnapMark User Guide

SnapMark captures your Windows screen and lets you annotate it with marks that **stay editable** — boxes, arrows, text, redactions and more are separate objects, not pixels painted onto the picture. The original image is never modified.

[Other languages / Bahasa lain](../README.md)

## Contents

1. [Installing](#installing)
2. [Capturing the screen](#capturing-the-screen)
3. [Annotation tools](#annotation-tools)
4. [Keyboard shortcuts](#keyboard-shortcuts)
5. [Copying and saving](#copying-and-saving)
6. [Projects and history](#projects-and-history)
7. [Settings](#settings)
8. [Privacy](#privacy)
9. [Troubleshooting](#troubleshooting)

## Installing

Run the installer `SnapMark_x.y.z_x64-setup.exe`. It installs for your account only (no administrator rights needed). Afterwards SnapMark runs in the **system tray** (the icon area near the clock). If you can't see the icon, click the ^ arrow to show hidden icons.

Right-click the tray icon for the menu: **Capture**, **History**, **Open project…**, **Settings**, **Quit**.

## Capturing the screen

1. Press **Print Screen** (or click the tray icon, or choose **Capture**). The screen freezes for a moment; with several monitors, all of them are captured.
2. **Drag** to choose an area. You can change the area at any time, even after adding annotations: drag its **outline** to move it, drag a **handle** on a corner or side to resize it, or drag in the dark area outside to choose again. Arrow keys nudge the area; **Ctrl + arrow** resizes it; **Shift** makes the step 10 pixels.
3. Use the toolbar to add annotations.
4. Press **Enter** to copy to the clipboard, or **Ctrl+S** to save. **Esc** cancels.

The first Esc deselects objects; the next Esc closes SnapMark.

## Annotation tools

| Tool | Key | Notes |
|---|---|---|
| Select & edit | `V` | Click an object to select it; **Shift+click** adds/removes from the selection. Drag to move, pull a handle to resize. |
| Rectangle | `R` | **Shift** = square. Can be filled. |
| Ellipse | `E` | **Shift** = circle. |
| Line | `L` | **Shift** = lock to 45° angles. Styles: solid, double, dashed. |
| Arrow | `A` | **Shift** = 45°. Arrowhead on one or both ends. |
| Freehand pen | `P` | Free drawing. |
| Highlighter | `H` | Translucent marker. |
| Censor | `S` | Mosaic, blur, or **black block** (safest). Rectangle or brush shape. |
| Step number | `N` | Click to place 1, 2, 3… in order. |
| Text | `T` | Choose a background. **Ctrl+Enter** or **Esc** finishes. |

Color, line width, font size and bold are set in the toolbar; changes apply to the selected objects.

## Keyboard shortcuts

| Key | Action |
|---|---|
| `Enter` / `Ctrl+C` | Copy the result to the clipboard |
| `Ctrl+S` | Save PNG to the save folder |
| `Ctrl+Shift+S` | Save as… |
| `Ctrl+Alt+S` | Save a `.snapmark` project |
| `Ctrl+Z` / `Ctrl+Y` (or `Ctrl+Shift+Z`) | Undo / redo |
| `Ctrl+D` | Duplicate the selected objects |
| `Ctrl+A` | Select all objects |
| `Ctrl+]` / `Ctrl+[` | Bring to front / send to back |
| `Delete` / `Backspace` | Delete the selected objects |
| Arrows (`Shift` = 10 px) | Move selected objects; with none selected, move the area (with `Ctrl`: resize the area) |
| `Esc` | Deselect, then close |

## Copying and saving

The result is always **only the selected area**, at the screen's **original resolution**, exactly as you see it.

- **Copy** (Enter): goes to the clipboard, ready to paste.
- **Save** (Ctrl+S): straight to the save folder as `snapmark_20261125_143005.png` (date_time). Existing names are never overwritten (a suffix `_2`, `_3`, … is added). Default folder: `Pictures\SnapMark`.
- **Save as** (Ctrl+Shift+S): choose the name and folder yourself.

After a successful copy or save, SnapMark closes automatically.

## Projects and history

A **`.snapmark` project** stores the original image plus every annotation as an object, so you can reopen and edit it later. Save with **Ctrl+Alt+S**; open by double-clicking the file, or via tray → **Open project…**.

> **Be careful with redactions.** Because a project file keeps the *original* image, anything you redacted can still be seen by whoever opens that file. To share, use **Copy** or **Save PNG**, which contain only the redacted result. SnapMark warns you before saving a project that contains a redaction.

**History**: every Copy/Save is recorded automatically as an editable project (the last 50 by default, on this computer only). Open it from tray → **History** and click an item to edit it again.

## Settings

Tray → **Settings**.

| Setting | Description |
|---|---|
| Capture hotkey | Default `Print Screen`. Click **Change…**, then press the new combination (use Ctrl/Alt/Win so it doesn't interfere with typing). |
| Save folder | Where Ctrl+S saves. |
| Language | Bahasa Indonesia, English, Español, Deutsch, 日本語, 简体中文, Français, Italiano, Português (Brasil), 한국어, Русский, العربية, Nederlands, or same as Windows. |
| History | How many items are kept (0 = off, at most 500). |
| Start with Windows | SnapMark is ready as soon as you sign in. |
| Hint color | Color of the instruction text while selecting an area. |
| Theme | Same as Windows, Light, Dark, or Liquid Glass. |
| Updates | Check & install automatically every 6 hours, or press **Check now**. |

Updates are downloaded from the official release, installed without an installer window, and SnapMark reopens by itself; your settings and history are kept. An update waits until you finish editing.

## Privacy

- Screenshots and projects **never leave your computer**.
- No telemetry. The only network access is the update check.

## Troubleshooting

**Print Screen does nothing / the hotkey isn't active.** Windows 11 can claim that key for its own capture tool (Snipping Tool). In SnapMark Settings click **Open Windows keyboard settings**, then turn off the option that makes the Print Screen key open that tool (its name and location vary between Windows versions). Or pick another hotkey.

**The tray icon is missing.** Click the ^ arrow on the taskbar; drag the SnapMark icon out so it's always visible.

**Where data lives.** Settings: `%APPDATA%\app.snapmark.desktop\settings.json`. History: `%LOCALAPPDATA%\app.snapmark.desktop\history`.
