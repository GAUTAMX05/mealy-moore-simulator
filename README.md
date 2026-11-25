# Mealy ⇄ Moore Machine Simulator

An interactive, dependency-free simulator for converting finite-state machines between Mealy and Moore forms. It includes editable transition tables, conversion steps, output tables, and draggable/zoomable state diagrams.

## Run locally

Open `index.html` directly in a modern browser, or serve this folder with a local web server:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Use

Choose a conversion direction, enter states and alphabet as comma-separated values, and edit transitions. Moore machines also require one output per state. Use **load example** to restore a working sample, then select **Convert**. Drag diagram nodes to rearrange them, drag the background to pan, and use the mouse wheel or zoom controls to zoom.

No build step or external dependencies are required.
