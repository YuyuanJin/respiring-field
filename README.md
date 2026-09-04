# Respiring Field / 息流

An interactive creative-coding study of a slowly evolving, domain-warped noise field.

**[Open the live artwork](https://yuyuanjin.github.io/respiring-field/)**

The field is rendered in a WebGL fragment shader and can be explored through a compact DialKit control panel. Adjust its scale, drift, warp, isolines, grain, palette, or seed, then export the current frame as a PNG.

## Built with

- p5.js and WebGL/GLSL
- React
- DialKit

## Run locally

From this directory:

```sh
python3 -m http.server 4173
```

Then open <http://127.0.0.1:4173/>.

The accompanying concept and visual-system notes are in [breathing-noise-philosophy.md](./breathing-noise-philosophy.md).
