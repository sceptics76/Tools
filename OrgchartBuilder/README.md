# Org Chart Builder

Build an org chart in the browser without Visio. Everything is in one file, `index.html`.

## Features

- Add people with a name, role and department. Departments are colour-coded.
- **Drag a card onto the middle of another card** to make that person its manager.
- **Drag a card to the left or right edge of a peer** to reorder. The person's whole team moves with them.
- **Paste a list** to add many people at once, either as an indented outline or as spreadsheet rows (Name, Role, Manager, Department).
- Collapse teams, stack small teams vertically, and undo or redo changes.
- Light and dark mode, switched with the sun/moon button on the toolbar and remembered in your browser.
- Export to PNG, SVG, CSV, or a text outline you can paste back in later.

## Paste format

```
Maya Okafor - Chief Executive Officer
  Hannah Lee - Chief Financial Officer [Finance]
    Arjun Mehta - Financial Controller
  Chris Wong - Head of Marketing [Marketing]
```

Indent a line to make that person report to the line above. `[Department]` at the end is optional.

## Keyboard

| Key | Action |
| --- | --- |
| Enter (while editing) | Add a peer |
| Ctrl+Enter (while editing) | Add a direct report |
| Ctrl+Z / Ctrl+Shift+Z | Undo / redo |
| Delete | Delete the selected person |
| Ctrl+scroll | Zoom |

## Where your data is kept

Changes are kept in your browser's local storage on this device. To keep a copy or move it to another computer, use **Export → Copy as text outline** or **CSV**, then use **Paste a list → Replace the whole chart** to load it again.
