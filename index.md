# Portfolio

Seth Rader

[GitHub](https://github.com/4LT) \|
[Linked In](https://www.linkedin.com/in/seth-rader-50b81996)

## Software Ray Tracer

### Pipeline

<img src="rayt.png" />

<https://github.com/4LT/GI>

Full rendering pipeline converting a scene description to pixel buffer.
Includes global illumination techniques for reflection, refraction, and shadow
rays.

### K-d Tree

<img src="bunny.png" />

<https://github.com/4LT/GI>

Scene optimization using K-dimensional tree resulting in 150x speed-up on render
of "Stanford Bunny".  Conventionally, scene would be bisected in X/Y/Z direction
by round-robin; I opted for a heuristic selecting X, Y, or Z to minimize the
number of duplicated triangles.  For each dimension, planes are placed at the 
median of the triangle centroids in that dimension.

## gif2spr

<img src="gif2spr.png" />

<https://github.com/4LT/gif2spr>

CLI and GUI application for converting animated .gif (GIF89) images to Quake and
Half-Life sprites.  GUI is an easy-to-use front-end over the CLI built with
Tcl/Tk.

## Quake Maps/Modding

Quake 1 singleplayer map and scripting contributions.

### Askisi Gamma

<img src="4ltsp01_1.jpg" />

<img src="4ltsp01_2.jpg" />

<https://www.slipseer.com/index.php?resources/askisi-gamma.94/>

### Mod Jam 2022 Contribution: Leading Shot Turrets

<img src="mj2022_1.png" />

<img src="mj2022_2.png" />

<https://www.slipseer.com/index.php?resources/modding-jam-2022.186/>

### Quake 25th Anniversary Contribution: Grotto Gristle

<img src="q25.jpg" />

<https://www.quaddicted.com/reviews/q25_limits_v1.2.html>

## ShaderToy Shaders

<img src="shadertoy.jpg" />

<https://www.shadertoy.com/user/4LT>

Experiments with visual feedback effects, ray tracing, and SDFs, animation,
and audio visualization.

## Pipe Cleaner (WIP)

<img src="pipe-cleaner.png" />

<https://github.com/4LT/pipe-cleaner>

Wireframe shoot-em-up wherein ships are flown on the inside surface of a
cylinder.  So far only a renderer is implemented with minimal input support.
Renderer serves as an abstraction over the Rust
[wgpu](https://crates.io/crates/wgpu) library, and leverages instanced rendering
to reduce draw calls.
