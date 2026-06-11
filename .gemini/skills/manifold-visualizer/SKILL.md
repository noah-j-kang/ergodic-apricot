---
name: manifold-visualizer
description: Builds React components optimized for rendering high-dimensional projection graphs and coordinate mappings. Triggered when building the canvas, graph views, or visual maps.
---

# Core Mandates
- Use React with strict TypeScript typing definitions.
- For dense scatter plots (thousands of points representing topological coordinates), optimize rendering using HTML5 `<canvas>` or custom lightweight WebGL contexts over standard SVG elements to prevent DOM thrashing.
- Implement efficient click/hover coordinate matching using spatial partitioning algorithms or standard radius bounding boxes.
- Rely on Tailwind CSS utility formatting for all adjacent layout structures, control cards, and HUD overlays.
- Ensure state handling for coordinate updates, selection trajectories, and zoom scaling maps to local states or context cleanly.