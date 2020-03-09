6.2 Volumes

Find the area of the cross sections.
If we then slice up the figure into n parts (delta x) and find the sums of the volumes of all pieces,
we then have an approximation fo the volume.

Notice how as n approaches infinity (number of slices),
we will have a better approximation of the volume (the exact volume).

Defintion of Volume:
Let S be a solid that lies between x = a and x = b.
If the cross sectional area of S in the plane Px, through x and perpendicular to the x-axis is A(x),
where A is a continuous function, then the volume of S is V = lim n->0 (sigma A(xi^*) delta x) = integral of A(x)dx.

When using the formula V = integral A(x) dx,
remember that A(x) is the area of a moving cross section obtained by slicing through x perpendicular to the x-axis
for V = integral A(y) dy cross section by slicing through y perpendicular to y-axis.

Example I:
Show that the volume of a sphere is V = 4/3 pi*r^3.
V = 2 integral 0 -> r (A(x) dx)
A = pi r^2
Radius = x^2 + y^2 = r^2 (bigger circle) --> y = sqrtt(r^2 - x^2)
A(x) = pi(sqrt(r^2 - x^2)^2) = pi r^2 - pi x^2
V = 2 integral (pir^2 - pix^2)dx
= 2(pir^2x - pi/3x^3)
= 2(pir^3 - pi/3r ^3 - 0) = 2(2pi/3 r^3)
= 4pi/3 r^3

Example II:
Find the volume of the solid obtained by rotating about the x-axis the region under the curve sqrt(x) from 0 to 1.
I. Graph curve
II. Rotate about the axis specified
A = pi(sqrt(x))^2 = pi x
V = integral( pix dx)
= 1/2 pi x^2 = 1/2 pi - 0 = pi / 2

Example III:
Find the volume of the solid obtained through the region enclosed by y = x^2, y = x, rotated about y = -1.
x = x^2
x - x^2 = 0
x(1 - x) = 0
x = 0, 1

Radius of small circle = 1 + x^2
Radius of big circle = 1 + x

A big - A small = pi(1 + x)^2 - pi(1 + x^2)^2
= pi[1 + 2x + x^2 - 1 - 2x^2 - x^4]
= pi[-x^4 - x^3 + 2x]

V = pi integral(-x^4 - x^3 + 2x)dx = pi(-1/5 x^5 - 1/3 x^3 + x^2) = 7pi / 15