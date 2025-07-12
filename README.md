# Origin to Bounding Box Corner

A simple Blender addon that lets you set the origin of any mesh object to any bounding box corner (positive or negative X, Y, Z), and then move the object so its origin is at world origin (0,0,0).

Ideal for modular, game-ready assets and anyone who wants full control over object origins.

---

## Features

- Toggle between +X/-X, +Y/-Y, +Z/-Z to select the bounding box corner
- One-click "Set to Bounding Box" button
- Moves object origin and clears location (Alt+G)
- Works with single or multiple selected objects
- Easy panel under **3D Viewport > Sidebar (N-panel) > Tool Tab**

---

## Installation

1. **Download** [`origin_to_bbox_corner.zip`](./origin_to_bbox_corner.zip) from this repository.
2. In Blender, go to **Edit > Preferences > Add-ons > Install…**
3. Select the downloaded ZIP file and click "Install Add-on".
4. Enable **Origin to Bounding Box Corner** in the add-on list.
5. Find the panel in the **Tool** tab (N-panel) in the 3D Viewport.

---

## Usage

1. Select one or more mesh objects in Object Mode.
2. Open the Tool tab in the 3D Viewport’s sidebar.
3. In the "Origin to Bounding Box Corner" panel, toggle X, Y, Z to pick your desired bounding box corner (each axis toggles positive/negative).
4. Click **Set to Bounding Box**.
5. The selected object(s) will have their origin set and will be moved so their origin is at world (0,0,0).

---

## Why?

- For modular asset workflows
- Grid snapping in game engines
- Consistent, predictable origin placement

---

## License

[GPL-3.0 License](./LICENSE)

---

## Credits

- Z4RUS
- Gemini
- ChatGPT

---

## Feedback & Issues

If you find bugs or have suggestions, please open an [issue](https://github.com/Z4RU5/origin-to-bbox-corner/issues) or create a pull request!

---

*Happy blending!*

