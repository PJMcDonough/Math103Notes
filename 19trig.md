% Trigonometry (Chapter 5)
% Patrick McDonough for Prof. West
% 2022-04-04


# §5.1 Angles
We frequently use the following Greek Letters for angle names in trigonometry.

|Letter| Name|
|-----|-----|
|$\theta$ | theta|
|$\phi$ | phi|
|$\alpha$ | alpha|
|$\beta$ | beta|
|$\gamma$ | gamma|

We will be discussing angle between rays.
A ray is 

Standard Position is when we place the angle at the origin, and align the initial (AB of ABC) side with the $x$-axis pointing in the $+x$ direction.
The other ray (BC of ABC) is the is terminal side.
Positive angles are counter-clockwise.

In addition to the normal degree system, we also use radians.
The two most useful conversions are $90º=\frac 12\pi$ in radians, and $360º=2\pi$.
A radian is the angle you get when you rap a string with the length of the radius of a circle around a cure and connect the outer point to the center to the other outer point on the at the other end of the string.
One radian is aproximately 57.2958º.

Choosing 360º is not a bad choice at all, because it allows for simple divisibility, but it also has disadvantages compared to radians.

The group activity wehre we all tried to replicate an angle was realy quite interesting.
We all measured slope.
One team was accurate to three decimal places (at least on paper). 

Using very precise instruments, machinists like Mr. West do something very similar to what we did here to do things like repairing molds.
They need to determine, for example the draft angle of a mold.
They use the tangent function $\tan$ for this

# Triangles, Circles, and Trigonometric functions (§5.2)
Mr. West also gives gives an explanation of this for a circle of radius $R$.
To recover that explanation, perform unit conversion.

If you draw a circle with radius 1 (i.e. a unit circle) at the origin and also draw a triangle with one leg on the $x$-axis starting at the origin going to a right angle with the final point on the circumference, you can see the correspondence between triangles and circles we use for trigonometry.
Mr. West has an interactive version of this.

If you measure the angle from the $x$-axis counterclockwise to the hypotenuse, and call it $\theta$, we have 
$$\begin{align}
\sin \theta &= y \\
\cos \theta &= x \\
\tan \theta &= \frac yx \\
\end{align}$$

If you go around the circle twice, that's 720º and that's OK.

Fun fact
$$
\frac 41    - \frac 43 +
\frac 45    - \frac 47 +
\frac 49    - \frac 4{11} +
\frac 4{13} - \frac 4{15} + \cdots
= \pi
$$

You can see by drawing a right triangle with two 45º angle, and using the Pythagorean theorem that $\sin(45º)=\cos(45º)=\frac{\sqrt{2}}{2}$.

Similar arguments can be used to find the other values on a unit circle, after bisecting an equilateral triangle.

A useful mnemonic device for remembering that $\cos$ is $x$-related and $sin$ is $y$-related is that the coastline is horizontal, and road sines are vertical.

The Pythagorean theorem on the triangle inscribed in the unit circle gives the Pythagorean identity $(\cos\theta)^2+(\sin\theta)^2=1$. 
We normally write this as $\cos^2\theta+\sin^2\theta=1$.

**Example:** If $\sin\theta=\frac 45$, find $\cos\theta$. By the Pythagorean identity, we have $(\frac 45)^2+\cos^2\theta=1$. Algebra gives $\cos^2=\frac{25}{25}-\frac{16}{25}=\frac{9}{25}$.
So $\cos\theta=\pm \frac 35$.

When you solve problems like the preceding example, you may be told what quadrant the answer is in. Quadrants are numbered Q1-Q4 starting with the Q1, the quadrant where both $x$ and $y$ are positive.

We have three more trigonometric functions secant, cosecant, an cotangent.
$$\begin{align}
\csc\theta&=\frac 1{\sin\theta}\\
\sec\theta&=\frac 1{\cos\theta}\\
\cot\theta&=\frac 1{\tan\theta}\\
\end{align}$$


# Right Angle Trig (§5.4)
Recall that for a triangle with opposite side $y$, adjacent $x$ and hypotenuse $r$,

$$\begin{align}
\sin \theta = \frac yr\\
\cos \theta = \frac xr\\
\tan \theta = \frac yx\\
\end{align}$$

This is equivalent to the circle definition.

## Example
Consider a right triangle with side lengths 3, 4, and 5. 
Call the angle between the leg of length 4 and the hypotenuse of length 5 $\theta$.

We can read of the diagram that.
$$\begin{align}
\sin \theta &= \frac 35\\
\cos \theta &= \frac 45\\
\tan \theta &= \frac 34\\
\tan \theta &= \frac 43\\
\sec \theta &= \frac 54\\
\sin \theta &= \frac 35\\
\end{align}$$

## Example
Consider a right triangle with angle $\theta=30º$ opposite of length 7, adjacent $a$ and hypotenuse $c$a.
We can note that, $\tan \theta = \frac 7a$ and $\frac 7c = \sin 7c$.
We can plug in and do a little algebra to get that $a$ and $c$ are, respectively, approximately 12.124 and exactly 14.
Using a unit circle we can find the exact answer $a=\frac 7{\sqrt 3}$

If we wanted to we could do this with another pair of trigonometric functions.

## Example
Consider a palm tree on flat ground.
We need to trim it to prevent it from blowing of chunks of flaming embers next time there is a fire.
We'd like to know how tall it is, so we can figure out the bill.
From 35 feet away from the center of the palm tree, at 5 feet above ground level, we measure the angle to the top of the tree from the horizontal as 58º.
We figure that the relevant ratio of the legs is given by the tangent function, so the hight is $5'+35'\tan58º$.
Therefore, the tree is 61 feet tall.

As a practical mater, you can calculate the ratio of the height of some other object to to the length of its shadow.
Multiplying this by the length of the shadow the palm tree casts gives you its height.


# Graphing
Like for other functions, we can make a table.
The range $\sin$ and $cos$ is $[-1,1]$, so we should make sure that, at the right places, our sine and cosine graphs bounce off $y=\pm 1$.
The $\sin$, $\cos$, and $\tan$ are periodic, meaning there values form a cycle.

As with all other functions, we can stretch vertically by multiplying after evaluation, and we can stretch vertically before evaluation.
We can also shift, as with other functions.
Because they are periodic, $\sin \theta = \sin(\theta+2\pi)$, $\cos \theta = \cos(\theta+2\pi)$, and $\tan \theta = \tan(\theta+2\pi)$.
The same logic applies to the other three trigonometric functions.

Sketching your function before you label it can often result in nicer graphs.

##General Formula
In $y=A\sin(Bx-C)+D$, we call $A$ the amplitude, and the output of the function goes up to $A$ and down to $-A$.
The period (how long it takes for the function to repeat) is given by $\frac{2pi}{\vert B\vert}$.
The phase shift (P.S.) is given by $\frac CB$.

# Final Project
There will be a final project worth 5% of your grade.
You can either do an artistic Desmos project or a given set of graphs.
