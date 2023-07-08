---
permalink: /projects/
author_profile: true
classes: wide
intro:
  - excerpt: "In my spare time I enjoy learning new things, and then turning those things into small projects."

feature_row:
- image_path: /assets/geodesic.gif
  title: "Geodesics in 3D Point Clouds"
  excerpt: "I implemented an A-star algorithm to navigate any surface. Here my solver navigates the surface of the [**gyroid**](https://mathworld.wolfram.com/Gyroid.html) function, whose isosurface is approximated using a marching cubes algorithm, and a KD-Tree defines the connections between points. Check it out [**here**](https://github.com/AstroKriel/Geodesics)"

- image_path: /assets/mandelbulb.gif
  title: "Ray Marching a Mandelbulb"
  excerpt: "Ray marching is an efficient algorithm for rendering scenes like this mandelbulb, where a signed distance function (implicit representations of surfaces) exists for the (elements in the) scene. Check it out [**here**](https://github.com/AstroKriel/Mandelbulb)"

- image_path: /assets/mandelbrot.png
  title: "Zoom-in of the Mandelbrot"
  excerpt: "The mandelbrot is a classic. Here I play around with rendering a zoomed-in section of the fractal with Blinn-Phong shading for the fractal's escape time."

- image_path: /assets/circles.gif
  title: "Circle Packing"
  excerpt: "Circles on circles on circles!"

- image_path: /assets/chopsticks.png
  title: "Solving Chopsticks"
  excerpt: "I solve [**Chopsticks**](https://informatika.stei.itb.ac.id/~rinaldi.munir/Stmik/2021-2022/Makalah/Makalah-IF2211-Stima-2022-K1%20(56).pdf) using various searching algorithms, and show that only 557 unique game states exist, with a maximum of 13 moves before either reaching an end state or looping back onto a different game branch. Here, colours correspond with outcomes and player turns. Check it out [**here**](https://github.com/AstroKriel/Chopsticks/tree/master)"
---

{% include feature_row id="intro" type="center" %}
{% include feature_row type="left" %}

