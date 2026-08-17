# Lucasta Grid Drawer

**Vector grid editor** for level prototyping, geometric structures, and freehand drawing.

Built as a single HTML file. No build step. No dependencies. Open it and draw.

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Pure HTML/JS/SVG](https://img.shields.io/badge/stack-HTML%20%2B%20JS%20%2B%20SVG-4f8cff)

---

## Features

- **Vector SVG canvas** — infinite zoom without pixelation
- **Tools:** Select, Pencil, Line, Bézier, Rectangle, Triangle, Circle, Pixel, Eraser, Pan
- **Pencil modes:**
  - **Legacy** — firm straight polylines
  - **Smooth** — auto-smoothed cubic curves
- **True cubic Bézier** paths
- **Transform:** move, scale, rotate (15° snap + exact angle)
- **Style:** stroke color, fill, thickness, grid size, snap-to-grid
- **Project format:** `.lgd` (JSON) — save / load full scenes
- **Export:** PNG
- **Undo / Redo**
- Glow strokes, clean dark UI

---

## Quick start

1. Download or clone this repo
2. Open `lucasta-grid-drawer.html` in any modern browser  
   (Chrome, Firefox, Edge, Safari)
3. Draw

Optional: use a local server (Live Server, `npx serve`, etc.) if you prefer.

---

## Controls

### Tools

| Tool        | Shortcut | Description                          |
|-------------|----------|--------------------------------------|
| Select      | `V`      | Move, scale, rotate objects          |
| Pencil      | `P`      | Freehand (Legacy or Smooth)          |
| Line        | `L`      | Straight segment                     |
| Bézier      | `B`      | Cubic curves (click points, Enter/double-click to finish) |
| Rectangle   | `R`      | Box                                  |
| Triangle    | `T`      | Triangle                             |
| Circle      | `C`      | Circle / ellipse                     |
| Pixel       | —        | Fill one grid cell                   |
| Eraser      | `E`      | Delete object under cursor           |
| Pan         | `H`      | Move the view                        |

### General

| Action              | Input                    |
|---------------------|--------------------------|
| Undo / Redo         | `Ctrl+Z` / `Ctrl+Y`      |
| Delete selection    | `Delete` / `Backspace`   |
| Deselect / cancel   | `Escape`                 |
| Finish Bézier       | `Enter` or double-click  |
| Zoom                | Mouse wheel              |
| Quick delete        | Right-click on object    |

---

## Pencil modes

Located in the **Style** panel:

- **Legacy** — straight, firm polylines. Best for structures and clean geometry.
- **Smooth** — Chaikin-style smoothing + cubic Bézier rendering. Best for organic shapes.

Both can live in the same project. Each path stores its own `smooth` flag.

---

## File format (`.lgd`)

JSON document containing:

- Project name & version
- Grid size
- Camera state
- Full object list (type, geometry, colors, thickness, rotation, smooth flag, …)

Open and save from the top bar. Fully portable.

---

## Recommended workflows

**Level prototype (GD-style)**  
Grid 32/64 → Snap ON → Rectangles + Triangles + Circles → Pencil Legacy for guides → Select to tweak → Save `.lgd`

**Organic / art**  
Pencil **Smooth** or Bézier tool → thicker stroke → mix with shapes as needed

**Precise structures**  
Legacy only + Line + Rectangle → Snap ON → no fill

---

## Project structure

```
lucasta-grid-drawer/
├── lucasta-grid-drawer.html   # The editor (open this)
├── README.md
├── LICENSE                    # MIT
└── docs/
    └── Lucasta_Grid_Drawer_Ultimate_Guide.txt
```

---

## Browser support

Modern evergreen browsers with SVG + ES6 support.  
No external libraries required.

---

## License

MIT © 2026 Lucastahg

Free to use, modify, distribute, and sell.  
See [LICENSE](LICENSE) for full text.

---
Thanks For Using!
