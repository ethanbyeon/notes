# 6.1 Areas Between Curves
Definition: The area between two curves is defined as  
A = lim (n -> infinity) Sigma [f(xi*) - g(xi*)] delta x  

Definition: The area A of the region bounded by the curves y = f(x), y = g(x), and the lines x = a, x = b,
where f and g are continuous and f(x) >= g(x) for all x in [a, b], is  
A = integral (a, b) [f(X) - g(x)] dx  
*Curve on top - Curve on bottom  

Ex. 1:
Find the area of the region enclosed by the parabolas  
y = x^2 and y = 2x - x^2  
  
First find the points of intersection as these will be our lower and upper limits.   

x^2 = 2x - x^2  
2x^2 - 2x = 0 -> 2x(x - 1) = 0  
x = 0, 1  

A = integral(0, 1) [(2x - x^2) - x^2] dx  
= integral(0, 1) 2x - 2x^2 dx  
= 2 * integral(0, 1) x - x^2 dx  
= 2[1/2x^2 - 1/3x^3]  
= 2[1/2(1)^2 - 1/3(1)^3 - 0]  
= 2[1/2 - 1/3]  
= 2[1/6]  
= 1/3  
  
If we are asked to find the area between two curves f(x) and g(x) where f(x) >= g(x) for some values of x but g(x) >= f(x) for other values of x, we then split the region S into several regions S1, S2, ...  
with area A1, A2, . . .  The area of region S becomes the sum of A1, A2, . . .  
  
Ex. 2:  
Find the area of the region bounded by  
y = sin x, y = cos x, x = 0, x = pi / 2  
Find any points of intersetion (if any) between the curves from 0 to pi / 2  
*cos x = sin x only when x = pi / 4  

So integral(0, pi / 2) [f(x) - g(x)] dx  
= integral(0, pi / 2) (cos x - sin x) dx + integral(pi / 4, pi / 2) (sin x - cos x) dx  
= [sin x + cos x] + [-cos x - sin x]  
= (sin(pi / 4) + cos(pi / 4)) - (sin 0 + cos 0) + (-cos(pi / 2) - sin(pi / 2)) - (-cos(pi / 4) - sin(pi / 4))  
= (sqrt(2) / 2) + (sqrt(2) / 2) - (0 + 1) + (0 - 1) - (- (sqrt(2) / 2) - (sqrt(2) / 2))  
= sqrt(2) - 1 - 1 + sqrt(2)  
= 2(sqrt(2)) - 2