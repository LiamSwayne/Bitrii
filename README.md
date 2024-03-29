# Bitrii

A free, open source, low barrier to entry, pixel art rendering engine for creating animations that run in one HTML file.

**Why one file?** Single file animations are easy to share and host online.

**Why HTML?** The engine is written in JavaScript, but wrapped in an HTML file so it can be opened in web browsers by double-clicking. Also, animations can be run on all computers and operating systems without additional effort on the part of devs.

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
