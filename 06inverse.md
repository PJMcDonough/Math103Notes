% Inverse functions §1.7
% Patrick McDonough for Prof. West
% 2022-02-07 - 2022-02-09 

It makes sense mnemonically to think of these of these as undoing functions.
Consider the function $f(x)=2x$ which is of course the doubling function.
To undo it, we use the undoubling  function.
When we want to notate an inverse function of $f$ we write $f^{-1}$.
So, we have $f^{-1}(x)=\frac{1}{2}$.
Graphically we can think of this as reflecting about the line $y=x$.

Consider the following method for finding the function $f^{-1}$ given $f$.

1. Replace $f(x)$ with $y$
2. Swap $x$ and $y$.
3. Solve for $y$
4. Replace $y$ with $f^{-1}(x)$

There is an important note about this notation. We have $x^{-1}=\frac{1}{x}$, but as a general rule, $f^{-1}(x)\ne \frac{1}{f(x)}$.
For that meaning, write $\left(f(x)\right)^{-1}=\frac{1}{f(x)}$.

To check if $f$ and $g$ are inverses, verify that for all $x$ that $f(g(x))=g(f(x))=x$. 
Consider $f=2x$, $g=\frac{1}{2}x$.

$$\begin{align}
f(g(x))&=&f(\frac{1}{2}x)\\
&=&2(\frac{1}{2}x)\\
&=&x\\
g(f(x))&=&g(2x)\\
&=&\frac{1}{2}(2x)\\
&=&x\\
\end{align}
$$

We have verified that these are inverses.

We have a function to convert from °F to °C.
It's $C(x)= \frac{5}{9}(x-32)$.
We want to find the function to go the other way.
For the example of 20°C, we could write

$$
\begin{align}
20&=\frac{5}{9}(x-32)\\
20&=\frac{5}{9}(x)-\frac{160}{9}\\
20+\frac{160}{9}&=\frac{5}{9}(x)\\
\frac{9}{5}(20+\frac{160}{9})&=x\\
\frac{180}{5}+ \frac{160}{5}&=x\\
36+32x&=x\\
x&=68\\
\end{align}
$$

More generally, we can do this as

$$
\begin{align}
C(x)&=\frac{5}{9}(x-32)\\
y&=\frac{5}{9}(x-32)\\
x&=\frac{5}{9}(y-32)\\
x&=\frac{5}{9}y-\frac{160}{9}\\
x+\frac{160}{9}&=\frac{5}{9}y\\
\frac{9}{5}(x+\frac{160}{9})&=y\\
\frac{9}{5}x+32&=y\\
C^{-1}(x)&=\frac{9}{5}x+32\\
\end{align}
$$

We can verify the inverse we just calculated as $C^{-1}(C(x))=C^{-1}(\frac{5}{9}(x-32))=\frac{9}{5}(\frac{5}{9}(x-32)+32= x-32+32=x$ and perform a similar calculation to verify $C(C^{-1}(x))=x$
Also note that the inverse $C^{-1}$ can be used to reproduce the result we got in the algebra above

A function is an inverse of some other function if and only if it is one to one.
We define one-to-one functions by the condition different inputs have different outputs.
The function $f(x)=x^2$ over the domain of the real numbers is not one to one because $f(1)=f(-1)=1$.
One-to-one functions that are hard to reverse are important to cryptography, which is an incredibly economically important field.
It's based on number theory, an area of math which was, at one point, famous for having no commercial applicability.

The origami method for inverting a function is a neat visual way to do it.
The basic idea is that inverting a function is the same thing as reflecting it across the line $y=x$.
By making a fold along this line, we can invert the function.
I have provided a [Desmos example](https://www.desmos.com/calculator/ur1a4twnmt) of how this works.
