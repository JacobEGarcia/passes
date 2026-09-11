# PASSES

A first-person game inside a render that was abandoned mid-pass.
The world exists twice - once in full global illumination, once as raw clay -
and some of it only exists in one. Cross it, gather 12 photons, finish the render.

Inspired by Gleb Alexandrov's Eevee demo reel ("How far Blender has come!").

## Play
- WASD move, SPACE jump, SHIFT sprint, MOUSE look
- Q switches the render pass (GI / RAW). Hidden bridges are solid only in RAW.
- M toggles sound. R restarts after the final frame.
- Touch: left stick moves, right side drags look, JUMP / PASS buttons.

Four zones after the reel: Temple of Light (GI), Glass Atrium, Fur Hollow, Flood Basin.

## Stack
Three.js (jsDelivr CDN), no build step, no assets - all geometry, water, fur,
light and audio are procedural. Deploys as a static site on GitHub Pages.
