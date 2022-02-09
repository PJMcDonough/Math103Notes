% Composition of functions and function algebra §1.4 
% Patrick McDonough for Prof. West
% 2022-02-02

This whole section is largely an exercise in language learning.

We define the ordinary addition subtraction multiplication and division for functions.
These can be seen as simple shorthand for writing the $(x)$ part multiple times.

We define the composition of two functions $(f\circ g)(x) = f(g(x))$ which should not be confused with function multiplication $(f\cdot g)(x)=(fg)(x)=f(x)g(x)$. 
We will not usually use $\circ$-notation because writing $f(g(x))$ is usually clearer.

# Example 1
Consider $f(x) = x-1$ and $g(x) = x^2 - 1$. We have that

$$(f+g)(x) = f(x) + g(x) = (x-1) + (x^2 -1) = x^2 + x -2 $$
$$(f-g)(x) = f(x) - g(x) = (x-1) - (x^2 -1) = -x^2 + x$$
$$(f\cdot g)(x) = f(x)g(x) = (x-1)(x^2-1) = x^3 -x^2 -x + 1$$
$$(f/g)(x) = \frac{f(x)}{g(x)} = \frac{x-1}{x^2-1} = \frac{1}{x+1}$$

In the last example we should note that the domain excludes $1$, not just $-1$ because of the unsimplified form.
Remember to use parenthesise. Failing to do this will usually give the wrong answer.

# Example 2
Consider $f(x)=\frac{5}{x-1}$ and $g(x)=\frac{4}{3x-2}$
Find the domain $(f\circ g)$.

We start by rewriting as $f(g(x))$.
Next we note that $g$'s domain is all real numbers $x$ where $3x-2\ne 0$.
So, $g$'s domain is all real numbers except $\frac{2}{3}$.
Similarly, $f$'s domain is all real numbers except $1$.
To find the domain overall, we note that the restriction on the domain of $f$ means that $g(x)\ne 1$.
By algebra we can conclude that that $2$ is not in the domain of $f(g(x))$.
So the domain of $f(g(x))$ is all real numbers except $2$ and $\frac{2}{3}$, or equivalently $(-\infty,\frac{2}{3})\cup(\frac{2}{3},2)\cup(2,+\infty)$.

# Applications
There are plenty of applications of composition of functions in real life, although they are not normally expressed as such.
The total pre-tax price of a product as a function of the number you buy is a function, and so is the amount of sales tax given a total price.
The composition of these two functions gives the total cost to buy it. 
