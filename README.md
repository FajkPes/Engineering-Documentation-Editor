# Engineering Documentation Editor

A highly configurable, offline-first editor for creating consistent product and engineering documentation cards from photographs, dimensions, and reusable layouts.

I created this application to document screws, nuts, spacers, rivets, and other workshop parts without rebuilding the same document layout by hand every time. The editor is flexible enough to document many other products or objects as well.

## What it can do

- Build a documentation card from up to three independently adjustable images.
- Crop, rotate, pan, scale, recolor, sharpen, and align each image.
- Manage editable properties, legends, section separators, and review marks.
- Calibrate an on-canvas ruler and measure distances in millimeters.
- Calculate screw or nut dimensions, volume, and estimated mass.
- Fill calculator results into the matching documentation properties.
- Guide a new document through a step-by-step wizard.
- Save complete reusable presets and transfer them as `.batch.spoj` files.
- Import and export editable `.spoj` projects, JPG images, JSON configurations, layouts, and complete ZIP packages.
- Undo and redo edits, configure snapping and guides, and customize colors, typography, panels, and overlays.
- Attempt to extract calculator values from a `.pxz` archive or JSON manifest. Parser results must always be verified.

## Download and start

1. Download `Engineering-Documentation-Editor-v7.15.zip` from the latest release.
2. Extract the entire ZIP. Do not run the app from inside the archive.
3. Double-click `Start Engineering Documentation Editor.bat`, or open `index.html` directly.

The application needs no installation, Node.js, Python, or internet connection. JSZip is bundled locally for `.spoj`, `.batch.spoj`, and ZIP support. A modern desktop browser is recommended.

[Detailed documentation](README-DETAILS.md) · [All releases](https://github.com/FajkPes/Engineering-Documentation-Editor/releases)

## Credits

**Idea, concept and design:** FajkPes  
**Coding:** ChatGPT Codex, Claude and Google Antigravity
