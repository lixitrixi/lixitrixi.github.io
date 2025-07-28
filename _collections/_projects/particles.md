---
title: Particle Masks
date_start: 2022-05-01
date_end: 2022-05-01
source: https://github.com/lixitrixi/particle-masks
tags: graphics simulation python
---
This was a small but memorable project built using Pygame, a game development library for Python. It was inspired by a math course I was taking at the time, which introduced vector fields and linked to [this interactive demonstration](https://anvaka.github.io/fieldplay/). Seeing a direct connection between programming and the course material, I decided to create my own version of the simulation.

After implementing the basic system, I experimented with sampling particle colors from an image to add visual richness:
<img src="/assets/img/starry-mask.png" width="600px" style="filter: brightness(1.8);">
<figcaption>The particles in this image sample their color from Van Gogh's <i>Starry Night</i></figcaption>

While the project was relatively small in scope, it helped me appreciate how computer graphics often rely on indirect and compositional techniques. Pixels don’t always originate from a single logical source—color, motion, and texture can be derived from entirely separate layers or data, then brought together to create the final effect.

This insight has been especially valuable as I continue experimenting with custom texture systems in game development.
