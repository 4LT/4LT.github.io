# Portfolio

Seth Rader

GitHub: https://github.com/4LT

Linked In: https://www.linkedin.com/in/seth-rader-50b81996

## Software Ray Tracer

### Pipeline

<img src="rayt.png" />

https://github.com/4LT/GI

Full rendering pipeline converting a scene description to pixel buffer.
Includes global illumination techniques for reflection, refraction, and shadow
rays.

### K-d Tree

<img src="bunny.png" />

https://github.com/4LT/GI

Scene optimization using K-dimensional tree resulting in 150x speed-up on render
of "Stanford Bunny".  Conventionally, scene would be bisected in X/Y/Z direction
by round-robin; I opted for a heuristic selecting X, Y, or Z to minimize the
number of duplicated triangles.  For each dimension, planes are placed at the 
median of the triangle centroids in that dimension.

