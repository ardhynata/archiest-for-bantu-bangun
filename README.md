# Archiest — Blueprint Budget Planner

Archiest is a browser-based blueprint and budget planning tool for designing room layouts, adjusting walls and openings, and reviewing structural and cost-related information in one workspace.

## Features

- Room-based floor-plan editing with drag, resize, and multi-select support
- Wall and boundary visualization for plan drafting
- Doors and windows/openings management
- Floor switching for multi-floor projects
- Budget and structural info panels
- Currency toggle between IDR and USD
- Undo and redo history
- Minimap for fast navigation
- Pan/zoom style workspace navigation
- Project import/export and local autosave
- Keyboard nudging for precise layout adjustments

## How to use

1. Open `archiest.html` in a modern web browser.
2. Start by adding rooms to the canvas.
3. Resize or move rooms to shape the blueprint.
4. Add doors and windows from room controls or the context menu.
5. Review the budget and structural panels as you edit.
6. Export your project when you need to back it up or share it.

## Getting started

### Option 1: Run locally
Just open the HTML file directly in your browser.

### Option 2: Host it as a static site
Place `archiest.html` on any static hosting service or web server and open the page from the hosted URL.

## Keyboard shortcuts

- `Space` + drag: pan the canvas
- `Middle mouse drag`: pan the canvas
- Arrow keys: move the selected room
- `Shift` + arrow keys: move in larger snap steps
- `Ctrl` / `Cmd` + arrow keys: move in major snap steps
- `Ctrl` / `Cmd` + `A`: select all
- `Delete` / `Backspace`: delete the selected room
- `Ctrl` / `Cmd` + `Z`: undo
- `Ctrl` / `Cmd` + `Y` or `Ctrl` / `Cmd` + `Shift` + `Z`: redo

## Project notes

- This app appears to be delivered as a single self-contained HTML file.
- Project state is persisted locally and can be exported/imported as project data.
- The interface includes visual helpers for dimensions, walls, columns, and layout scaling.

## File

- `archiest.html`
