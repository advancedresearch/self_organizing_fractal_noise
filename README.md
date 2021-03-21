# Self-Organizing Fractal Noise
Research on self-organizing fractal noise

![boolean fractal noise](https://github.com/advancedresearch/self_organizing_fractal_noise/blob/master/images/boolean-fractal-noise.png)
###### Boolean Fractal Noise using a simple self-organizing non-deterministic algorithm

### Videos

- [Boolean Fractal Noise](https://www.youtube.com/watch?v=3-x_FXgWqLA)
- [Continuous Fractal Noise - 2 bit](https://www.youtube.com/watch?v=8fQYQm74Arc)
- [Continuous Fractal Noise - 4 bit](https://www.youtube.com/watch?v=aPPpjYyqgbM)
- [Continuous Fractal Noise - 8 bit](https://www.youtube.com/watch?v=N47nV-qbTIk)
- [Continuous Fractal Noise - 16 bit](https://www.youtube.com/watch?v=9k5yTErsfbU)
- [Continuous Fractal Noise - 32 bit](https://www.youtube.com/watch?v=mrfTdTlXrko)
- [Continuous Fractal Noise - 64 bit](https://www.youtube.com/watch?v=SxlmPGjzGFE)
- [Continuous Fractal Noise - 128 bit](https://www.youtube.com/watch?v=-aN8dU34fkA)

### Introduction

[Gradient noise](https://en.wikipedia.org/wiki/Gradient_noise) rescaled and added into itself to produce Fractal Noise (also called [Pink noise](https://en.wikipedia.org/wiki/Pink_noise)):

![Fractal noise](https://noiseposti.ng/assets/images/general/Simplex-Fractal-128.png)

Fractal Noise is one of the most common signals in biological systems.
Using Gradient noise (specific examples of which include [Simplex Noise](https://en.wikipedia.org/wiki/Simplex_noise) and [Perlin Noise](https://en.wikipedia.org/wiki/Perlin_noise)) as building block is an efficient way of constructing Fractal Noise.
However, other ways of constructing Fractal Noise are interesting for research because they lead to better understanding.

This research project studies Fractal Noise from the perspective of [self-organized criticality](https://en.wikipedia.org/wiki/Self-organized_criticality),
in particular phase-shifted solutions of long-term behavior.
With other words, the noise is a temporary step of a dynamical system evolving,
where different "solutions", that are identical except for a phase shift, "fight" over available space.

The boundary between phase-shifted solutions of long-term behavior is fractal-shaped.
Fractal Noise is constructed by visualizing the phase over the space.
With other words, this approach constructs Fractal Noise indirectly, explaining it in terms of an underlying space.

For example, a chess pattern is a solution of the underlying space that gives rise to Boolean Fractal Noise.
Since there are two solutions of a chess pattern, the two solutions are labeled with white and black color.

### To learn more

- [Sequences for learning about Self-Organizing Fractal Noise](https://github.com/advancedresearch/self_organizing_fractal_noise/blob/master/sequences.md)

### More Resources

- [Pink noise - Wikipedia article](https://en.wikipedia.org/wiki/Pink_noise)
- [Perlin noise - Wikipedia article](https://en.wikipedia.org/wiki/Perlin_noise)
- [Self-organized criticality - Wikipedia article](https://en.wikipedia.org/wiki/Self-organized_criticality)
- [Self-organized Criticality: An explanation of 1/f noise - Slides](https://courses.physics.illinois.edu/phys596/fa2016/StudentWork/team7_final.pdf)
