# Tesla Model 3 MCU CAD Lab — Stage 1

A mobile-friendly, standalone interactive schematic viewer for a 2024 refreshed Model 3 MCU concept.

## Open the viewer
Visit the repository's `index.html` file to inspect the source. To publish it as a shareable web page, enable GitHub Pages in the repository settings and select the `main` branch and `/(root)` folder.

## Current scope
- Isometric concept assembly: enclosure, PCB, shield/thermal layer, connectors, mounts, harness placeholder, and lid
- Drag to rotate; mouse wheel to zoom
- Exploded view, wireframe, select/isolate/hide/show/reset controls
- Responsive layout for phones and desktop browsers
- No build step or external JavaScript dependencies

## Accuracy and safety note
This is a concept schematic, not Tesla's official CAD and not a verified reproduction. Dimensions, internal component placement, connectors, and fasteners have not been verified against official drawings. Do not use it for manufacture, repair, or safety decisions.

## Next phase
Replace schematic blocks with measured geometry, add per-part CAD source (for example STEP/STL/OpenSCAD where practical), and validate against reliable teardown references and measured dimensions.
