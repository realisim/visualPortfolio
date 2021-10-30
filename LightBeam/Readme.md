Light Beam

After reading Physically Based Rendering by Matt Pharr, I was quite hyped to make a little CPU ray tracer and experiement with PBR materials.

The project diverged as I tried to improve the speed of ray tracing (multi threaded), which is displayed by the videos.

Then I was intrigued by rendering polygons, since classic quadratics rendering (spheres and planes) was pretty obvious to me.
This lead to a lot of maths, since this is all done from scratch.
It made it very obvious that accelration structures such has an octree was mandatory.

The code can be found here:
https://github.com/realisim/realisim2/tree/master/Projects/LightBeam