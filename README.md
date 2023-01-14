# Manifolds-in-Data-Science

How do I spatially represent my data in an accurate and meaningful way? 

Manifolds describe a vast number of geometric surfaces. To be a manifold, there’s one important rule that needs to be satisfied. The best way to understand this property is through example. Manifolds exist in any dimension, but for the sake of simplicity, let’s think about a three-dimensional space.

Suppose there is a small ant walking along a manifold in three dimensions. This manifold could be curvy, twisty, or even have holes in it. Now here’s the rule: From the point of view of the ant, everywhere it walks should look like a flat plane.

If you’re looking for an application I think this is one that all of us can relate to; we live on a manifold! A sphere is one of the simplest examples of a manifold in three dimensions.

Can you think of surfaces that are not manifolds? These surfaces will have problems at some “sharp” points. Below are the first few that come to mind for me:

A cube. If you walk along a side and get to an edge, things will be too sharp and will no longer look like a plane.
The landscape of a mountain. Assuming that the peak is perfectly sharp, at this point things will not look like a plane.
An hourglass. Assuming that the intersection of the two halves is a single point, the rule will be broken here.

## Intution of Manifolds 
The common theme of these examples is that they are somewhat smooth — meaning that there are no sharp spikes or edges. The overall shape of the object can be amorphous, which is nice when describing datasets that don’t have rigid boundaries.

