Code Name: COMMANDO

This is a small excerpt from our work (we were 2 devs) at Simthetiq.

A bit of background:
https://www.simthetiq.com/fr/systeme-visuel-x2/

Simthetiq is in the simulation industry and for a couple years they were into visual for the civil aviation.
Simthetiq has a mature product called X2 visual system which is used by the flight simulation industry to train pilots.

The visual system is not cutting edge AAA game quality but quite impressive when combined with a full moving simulator.

I designed, lead the team and coded a fair part of the whole project Commando (which is a major refactoring of the original engine)

Major features:
- Geodetic 3d engine which modelized 100% of the earth surface
        - lowest resolution being 15 meters per pixel.
        - lowest heightmap resolution being 30 meters per pixel
        - whole earth landcover at 150 meters per pixel.
- Physically simulated light scattering atmosphere
- Volumetric clouds
        - texture based (easy to modelize shapes)
- Realtime 60Hz in all conditions
- Dynamic streaming of 3d assets, no loading screens.
- Editor built around the engine, so artist could work directly with the engine and immediately see end results.