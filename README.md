# Bitrii

A free, open source, low barrier to entry, pixel art rendering engine for creating games that run in one HTML file.

**Why one file?** Single file games are easy to share and host online.

**Why HTML?** The games and engine are written in JavaScript, but are wrapped in an HTML file so they can be opened in web browsers by double-clicking. Also, games can be run on all computers and operating systems without additional effort on the part of game devs.

To contribute, read [CONTRIBUTING.md](./CONTRIBUTING.md)

Roadmap:
- [x] Fullscreen button
- [x] Display
- [ ] Layer system
  - [ ] Base layer system
    - [x] Layers, ordering or layers, and ability to access previous and next layers
    - [x] Render layers to display
    - [ ] Experiment with image generation rather than cells <details><summary></summary>Currently every pixel is a div, but creating an image and setting the pixels in that image to specific values may yield astronomical performance gains.</details>
    - [ ] Create startup animation <details><summary></summary>does not use layer system, instead is built from scratch and runs in a for loop)</details>
  - [ ] Collision groups (layers can collide with other layers in the same collision group)
  - [ ] Outline layers <details><summary></summary>Layers that are dynamic outlines of other layers.</details>
