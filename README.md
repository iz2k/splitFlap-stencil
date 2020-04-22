# Flip-stencil

The flip-stencil is part of the Flip-Clock v2 project. It basically includes 3D design and print files for stencil tools that allow makers paint their own flip digits with spray paint.

The flip-stencil project includes:

- Stencils for two digit numers from 00 to 59.
- Stencils for weather icons corresponding to the darksky API.
- Generic base for flap-24 and flap-60 (specific flaps for 24 and 60 flap drums of Flip-Clock v2 project)

## Printing parts

### Stencils

As the base and the stencil are just tools for painting, there is no big difference on the resolution and material used for this. In my case, I have printed the stencils and the bases at 0.3mm of resolution with PLA.

<img src="_img\print-base.jpg" style="zoom:50%;" />

### Flaps

Printing the flaps is a more difficult step, as the final look of the flaps is important. The flaps are very thin pieces of plastic, so one option is to print them horizontal, laying on the print bed. However, this is not the best option, as the final look on the bottom side and the top side of the flap will differ substantially.

After several trials, I found that the best option is to print them vertically, so that the look will be completely symmetric. In this case, take care with the slicer in order to allow thin walls. Otherwise, the slicer will increase the thickness of the flaps to improve printability. In  my case, using PrusaSlicer with thin walls activated did a great job. I printed the flaps on black PLA with a resolution of 0.15mm. The width of the axle  of the flaps is of 0.45mm, so better use a resolution multiple of this value.

<img src="_img\print-flaps.jpg" style="zoom:50%;" />

## Painting flaps

In order to paint the flaps, just place two flaps inside each base and fit in a stencil on it. You can do it with a single base, ore with multiple bases to paint more flaps in paralel. In this case, I am printing flaps with numbers from 00 to 23 (for hour display), so I am using 12 bases.

Take into account, that each flap will have par of a number in one side, and part of a different number in the other side. One easy way to keep things organized is to print even numbers first, and odd numbers in a second round reorganizing the flaps.

<img src="_img\palce-in-base.jpg" style="zoom:50%;" />

Then place the stencials over a protected surface. Spraying paint will not only paint the numbers, but will also mess up the surrounding area. Cleaning it up after is not as easy, so it is better to prevent in advance.

<img src="_img\place-in-protected-area.jpg" style="zoom:50%;" />

Then apply the spray paint gently so that the numbers can be read correctly within the stencil.

<img src="_img\apply-spray.jpg" style="zoom:50%;" />