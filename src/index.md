# `shader-art` web component

`shader-art` is a web component which creates a canvas and runs a webgl animation in it.

The default geometry provided is 2 triangles.

## getting started

## predefined uniform variables

- `float time` - essentially, `performance.now()`)
- `float reducedMotion` - 1. when motion reduced, 0. otherwise
- `vec2 resolution` - the width and height of the canvas in CSS pixels
- `float pixelRatio` - the devicePixelRatio. 2 on retina screens, capped to 2
