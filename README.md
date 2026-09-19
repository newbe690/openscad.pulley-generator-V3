# openscad.pulley-generator V3


This is a generic version of [http://thingiverse.com/thing:16627](http://thingiverse.com/thing:16627)

Changes for this version:

Add bolt holes, head recesses, and retainer/idler grooves to parametric pulley

- Add configurable bolt holes around the shaft (PCD, count, diameter)
- Add optional head recess for bolts: cylindrical (DIN 912) or 45° countersink (DIN 7991)
- Extend retainer/idler options with value 2 = groove for a separate retainer/idler
- Grooves are cut BEFORE teeth to avoid hanging tooth tips
- Groove radial width = *_ht, axial depth = *_width (separate parameters)
- Groove outer radius = pulley_OD/2 + 1 to cleanly clear tooth tips

![sample](https://user-images.githubusercontent.com/8453489/129447605-69126f5d-a0a7-474f-9418-da2978a2a65b.png)


Enjoy!
