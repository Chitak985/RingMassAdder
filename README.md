# RingMassAdder
Adds the mass of rings around a body to it. This adds a tiny bit of realism to the game and doesn't affect that much. You can also configure this mod's effect on your planets using some variables.

## Configuring
To configure RingMassAdder, use `rmaRingPercent` and `rmaRingDensity` in Body/Rings/Ring.

`rmaRingPercent` is what percent of a ring's tile is actually filled. This is expressed in decimal and can be found by looking at your ring texture and dividing the amount of filled pixels by total pixels on a specific x coordinate (or you can eyeball it if you want). The default value is 1, assuming a fully filled ring.

`rmaRingDensity` is the average density of material the ring consists of and it is expressed in kilograms per meter squared, kg/m2. The default value is 1000 kg/m2.
