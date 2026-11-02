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

## Basic workflow

1. Load one or more product photos in the left panel, or import an existing `.spoj` project.
2. Crop and align the front, side, and top views.
3. Enter the product name, ID, material, type, standard, and other properties.
4. Calibrate the ruler against a real reference visible in the photo.
5. Use **Measure**, **Wizard**, or **Calculator** as needed.
6. Mark reviewed fields with the check controls.
7. Export a JPG, editable `.spoj`, or a complete ZIP package.

The built-in **Help** panel contains a more detailed walkthrough.

## Reusing settings and templates

- **`.spoj`** — imports a complete editable project, including its configuration and embedded images.
- **`.batch.spoj`** — open **Presets**, then use **Import Batch .SPOJ** to load a set of reusable presets.
- **Layout JSON** — open **Export / Import Layout**, select the sections you want, and import the layout file. Product values are not replaced unless the corresponding property sections are selected.
- **JSON configuration** — use **Import Config** for a full configuration without embedded images.
- **Template image** — load it in the template section and adjust its opacity to compare a photo with a reference outline.

Personal/company templates and photographs are intentionally not included in the public release. They are not required to run the editor and may contain private or third-party material.

## Data and safety notes

- Work is kept in the current browser session until you export it. Save a `.spoj` project regularly.
- A `.spoj`, `.batch.spoj`, or ZIP file is processed locally in the browser.
- Import only files you trust and verify all calculated or parsed engineering values before using them in real documentation.
- The mass calculator provides an estimate based on the entered geometry and density; it is not a substitute for measurement or engineering validation.

## Credits

**Idea, concept and design:** FajkPes  
**Coding:** ChatGPT Codex, Claude and Google Antigravity
