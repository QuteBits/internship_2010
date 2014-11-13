Internship (Raytrix, 2010)
===

Research work during my three months internship by Raytrix GmbH (Kiel, Germany - 2010).

**The problem:** When you try to visualize a picture using a lazer, the picture is viewed as a collection of points the lazer has to go through. You compute a path that covers all the points and the lazer has to be really quick to go through this path at a reasonable FPS rate. One of the problems is of physical nature: if you compute a path with many sharp turns, the lazer has to slow down on each turn and speed up between them. Which makes edgy paths slow and, well, you might have guessed it already: the lazer will break eventually.

**The result:** The idea was to smooth the paths and, as a consequence, speed up the whole process. The proposed solution was to define the path using Bernstein polynoms (order 3) and then use pythagorean-hodograph curves for optimization. Why exactly these curves? Because they have a nice property that you can quickly compute the overall length of the path constructed with these curves. It all worked nicely in a three-dimensional space. But as we had to add another dimension - it turned out, an unforeseen symmetry constraint had to be satisfied. And it wasn't possible with chosen Bernsten polynoms. Enjoy.

## Contact:
qute.bits (gmail)
