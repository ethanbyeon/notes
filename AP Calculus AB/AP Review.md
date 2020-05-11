Limits
lim kf(x) = k lim f(x)
If lim f(x) = L && lim g(x) = L2, then lim[f(x) + g(x)] = L + L2 (also applies to products of limits)

If the highest power of x in a rational expression is...
1. in the numerator, the limit is infinity
2. in the denominator, the limit is zero
3. the same, the limit is the coefficient of the highest term in the numerator divided by the coefficient of the highest term in the denominator

Tips when evaluating limits:
1. Rationalization using conjugates
2. Factorization and cancellation
3. Alternate forms of trigonometric functions

Limits of Trig functions
1. lim sin x / x = 1
2. lim (cos x - 1) / x = 0
3. lim sin ax / x = a
4. lim sin ax / sin bx = a / b

Continuity
Defition of Continuity
1. f(c) exists
2. lim f(x) exists
3. lim f(x) = f(c)

Types of Discontinuities
Jump: a gap or break
Point: a missing point or hole
Essential: vertical asymptote
Removable: Rational expression with common factors int he numerator and denominator (bc these factors can be canceled)

The Defintion of the Deriviative
-> Difference Quotient
-> Differentiability: has to be continuous and differentiable

Basic Differentiation
Three Cases where a function is not differentiable:
1. Wherever the function isn't continuous
2. Wherever the graph of the function has a vertical tangent line
3. Wherever the graph of the fucntion has a sharp turn

Quotient Rule
LoDeHi - HiDeLo / Lo^2

Chain Rule
Used when you're given composite functions

Basic Applications of the Derivative
Normal Line: Line perpendicular to the tangent line at the same point (negative reciprocal)

The Mean Value Theorem For Derivatives (MVT)
Some point in the interval where the slope of the tangent line equals the slope of thee secant line that connects the endpoints of the interval
*Curve must be continuous on the interval and at the endpoints

Rolle's Theorem
A continuous, differentiable curve has a horizontal tangent between any two points where it crosses the x-axis

Finding a Csup
If the derivative approaches +infinity from one side and -infinity from the other, and if the funciton is continuous at that point, then the curve has a "cusp" at that point

Applied Maxima & Minima Problems
A max or min occurs where the derivative of the function at the point is zero or where the derivative of the function at the point fails to exist

Curve Sketching
1. Find the roots or x-intercepts
2. Test the first derivative
3. Test the second derivative
4. Test end behavior

Motion
Related Rates
1. Find the equation that relates to the question
2. Find the derivative of the related equation
3. Plug in the values for the rate of change

Position, Velocity, and Acceleration
Position: x(t)
Velocity: v(t) or derivative of x(t)
Acceleration: a(t) or second derivativeof x(t)

Derivatives of Exponential and Logarithmic Functions
ln x = 1 / x (incorporates Chain Rule)
e^x = e^x (incorporates Chain Rule)

The Derivative of loga x
loga x = ln x / ln a
loga x = 1 / xln a (incorporates Chain Rule)

The Derivative of a^x
a^x = e^(xln a) * ln a = a^x * ln a

Other Topics in Differential Calculus
The Derivative of an Inverse Function
Take the reciprocal of the derivative at that point's corresponding y-value
*Find the value, a, that gives you the value of x that the problem asks for. Then plug that value, a, into the reciprocal of the derivative of the inverse function.

Linearization
f(x + delta x) ~= f(x) + derivative of f(x) * delta x
dy = derivative of f(x) * dx

L'Hopital's Rule
A way to find the limit of certain kinds of expressions that are indeterminate forms (0/0 or infinity/infinity)
*If the limit of the function gives us an undefined expression -> we can take the derivative of the top and the derivative of the bottom and see if we get a determinate expression (and maybe repeat the process)

The Integral
The Antiderivative
-> Reverse in reverse

*Each function has more than one antiderivative (there are an infinite number of antiderivatives of a function)

integral f(x)dx = (x^n+1 / n+1) + C

integral kf(x)dx = k integral f(x)dx
integral(f(x) + g(x))dx = integral f(x)dx + integral g(x)dx
integral kdx = kx + C

1. Break equation into separate integrals
2. Integerate individually

u-Substitution
Used when the integrand is a composite function

1. Replace the function with u
2. Integrate the simpler function using the Power Rule

Definite Integrals
Area Under a Curve

If you use the left endpoints:
(b - a / n)[y0 + y1 + y2 + y3... + y(n - 1)]

If you use the right endpoints:
(b - a / n)[y1 + y2 + y3... + yn]

lim n->infinity (b - a / n)[y0 + y1 + y2 + y3... + y(n - 1)]

The Fundamental Theorem of Calculus
integral b a f(x)dx = F(b) - F(a)

Trapezoid Rule: 1/2 (b1 + b2)h

Mean Value Theorem For Integrals
Enables you to find the average value of a function

If f(x) is continuous [a, b], then at some point c in the interval [a, b]:
integral b a f(x)dx = f(c)(b - a)
Graphically, finding the area of a rectangle whose base is the interval and whose height is some value of f(x) that creates a rectangle with the same area as the area under the curve

Avg. value of f(x) on [a, b]:
f(c) = 1/(b - a) integral b a f(x)dx

The Second Fundamental Theorem of Calculus
If f(x) is continuous on [a, b], then the derivative of the function F(x) = integral x a f(t)dt is f(x)

Accumulation Functions
The value of the integral is the area under the curve from the constant to the value x. As x gets bigger, so does the area.

Inverse Trig Functions
1. Use algebra and u-substitution
2. Make the integrand conform to a pattern
