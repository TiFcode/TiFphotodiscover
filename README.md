# TiFphotodiscover

A one-screen tactile photo discovery game. Each round reveals a randomly selected Polaroid, fixed at a gentle random rotation on a natural wood table. Its image starts under a dense graphite-powder layer; repeated slow finger passes wear it away in bristled, uneven grains.

## Run

Open `index.html` in a modern browser, or serve the directory with any static HTTP server.

## Design notes

- The card is intentionally fixed: no dragging, panning, rotating, or pinch zooming.
- Graphite uses a procedural texture and a low-opacity multi-bristle erase operation, making one fast pass insufficient.
- The first layer leaves approximately 10% naturally irregular exposed flecks, then unlocks the next photo when 48% is uncovered.
