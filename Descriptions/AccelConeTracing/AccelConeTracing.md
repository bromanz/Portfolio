# Acceleration Structures for Cone Tracing
## Summary
Ray and path tracing are well-known and evolved algorithms for rendering photo-realistic images.
To this day, state-of-the-art production renderers utilize advanced path tracing techniques. However,
after decades of research, path tracing has still difficulties to create noise-free images for interactive
real-time applications. Stochastic sampling often requires too many rays to facilitate effects like soft shadows
or glossy reflections without noise in real-time. An already proposed solution to this problem
is cone tracing. By generalizing rays to cones, it inherently integrates the effects mentioned above.
Furthermore, it eliminates the noise of the stochastic component, since it replaces infinitesimal rays
by approximating the integral over directions inside a cone, preventing subsampling. However, the
potential of cone tracing is still vague because acceleration structures have not been researched.
This lack of investigation limits the possibilities to conduct performance comparisons. Therefore,
this thesis focuses on applying efficient acceleration structures from ray to cone tracing. A Bounding
Volume Hierarchy and k-dimensional-tree were implemented to analyze the applicability of these
structures. Accordingly, this project compares ray and cone tracing performance with these accelerators.

## Achievements
* Created a GPU ray- and cone tracing framework in Unity3D in a team of two.
* Building of kd-tree and SBVH (Stich et al.) in Unity3D on the CPU.
* Implemented various traversal algorithms for rays and cones on the GPU.

## My responsibilities
* This was my master thesis, so basically everything.

## Media

