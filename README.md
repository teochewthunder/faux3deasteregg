# Faux 3D Easter egg

This simulates a 3D effect for an Easter egg, in CSS. The process is like this:

## Static
1. Make an egg-shaped div and make sure the `overflow` property is set to `hidden`.
2. Create a random pattern for the egg, and ensure that *when laid end-to-end with a copy of itself, the pattern lines up nicely*.
3. Place the joined pattern within the egg-shaped div.
4. Put a translucent div on top of the egg, with a radial background.
5. Add a shadow at the base of the egg.

## Animation
1. Manipulate the `margin-left` or `margin-right` properties ot the joined pattern to look as if the egg is spinning! 
