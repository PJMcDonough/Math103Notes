% Functions and Notation §§1.1-2
% Patrick McDonough for Prof. West
% 2022-01-26 -- 2022-01-31

# What is a function
The goal of this exercise is to write this in conversational language, not just read an obtuse definition from the internet.
A function is a relation (this has a technical mathematical definition, but we can thing of the common meaning here).
A function has the property that something goes in and something goes out, the output is unique given the input.
In mathematical writing, when we say that something has one of something we mean at least one. Otherwise, we say only or exactly.
Note that given an output, the input does not need to be unique.

## Examples
@ex. We can represent a relation using arrows from the inputs to the outputs. This is a common for functions.
@ex. A relation from people to their birthdays is a function because each person has only one birthday. The relation from birthdays to people is not a function if people share a birthday.
@ex. We can have tables 

|Domain | Range|
|-------|------|
|  7    |  4   |
|  3    |  3   |
|  11   |  4   |
|  0    |  3   |

@ex. We can also write this same function as a set of ordered pairs $\{(7,4),(3,3),(11,4),(0,3)\}$.
@ex. We can also represent functions as points on a graph i.e., an x-y plane. This gives us a way to check if a relation is a function: The vertical line test (VLT) i.e., 
if you have a graph of relation, then if and only if there is a vertical line which passes through more than one point in the relation, the relation is not a function.
@ex. We also define some functions with mathematical equations. For example,
consider the doubling function, $f(x)=2x$. We call this function notation. The
name of the function is $f$, but we could use some other letter or group of
letters if we wanted to. We can evaluate $f(3)$ by replacing each occurrence of x with $(3)$. This results in the value $2(3)=6$ not $23$.
@ex. For graphing see the professor's notes.
@ex. Given $f(x) = x^2$, $f(x+h)=(x+h)^2=x^2+2xh+h^2$. Remember the parentheses. It's not $x+h^2$.

## Evaluation vs solving
Evaluating a function for some input means determining the output of the function for the input.
Solving is a different operation.
It refers to the use of algebraic operations to find the value of some variable.

Take for example $p(x)=x^2+2x$.
We can evaluate $p(3)$ by substituting giving $p(3)=(3)^2+2(3)=9+6=15$.
To solve $p(x)=3$, we first substitute in the definition of $p(x)$.
$$x^2+2x=3$$
$$x^2+2x-3=0$$
$$(x+3)(x-1)=0$$
Then by the zero product property, either $x+3=0$ or $x-1=0$.
We get two solutions $x=-3$ and $x=1$.

# Domain and Range
## Interval and set builder Notation
See page 23 of the PDF version of the text for lots of examples of interval notation. An interval can be written as $(a,b)$, $(a,b]$, $[a,b)$, or $[a,b]$. 
The curly parentheses indicate $>$ and the square brackets indicate $\ge$. We also refer to these as exclusive and inclusive respectively. 
Do not use $[-\infty$ or $\infty]$. This doesn't make sense here. Instead we need to use  $(-\infty$ or $\infty)$.

## Finding Domain
The domain is the set of all valid inputs. 
Consider $g(x)=\frac{x+1}{x-3}$.
Dividing by zero is not defined, but dividing zero by a number other than zero is defined.
The function $g$ is not defined for $3$ because if $x-3=0$ then $x=3$.
This means that $3$ is not in the domain. All other real numbers are in the domain.
We say the domain is all real numbers except $3$, or, in interval notation, $(-\infty,3)\cup(3,\infty)$.

Consider $h(x)=\sqrt{4-x}$. Its domain is given by the inequality $4-x\ge 0$.
This is because of the square root. Solving gives $x\le 4$ and in interval notation this is $(-\infty,4]$. 

### Common restrictions on domain

1. Dividing by zero.
2. Even root (e.g. square root) of a negative number.
3. Common sense application-related issues e.g., age can never be negative.
4. Logarithms of non-positive numbers

## Finding Range
Consider $f(x)=x^2$.
Its domain is all real numbers by the above checklist.
Finding the range takes more work. 
We start by letting $y=f(x)$.
Then we almost solve for $x$.
$$y=x^2$$
$$\sqrt{y}=\sqrt{x^2}$$
$$\sqrt{y}=\pm x$$
Now we treat $y$ as the independent variable.
By using the checklist above on restrictions on domain, we can see that the only restriction is $y\ge 0$.
This is in fact the *range* of $f$.
This can also be done by graphing using [desmos](https://www.desmos.com/calculator).

# Reading graphs
Given a graph of $f(x)$, to evaluate the function, we can find the $y$-coordinate of the point on the curve at the given $x$-value.
We can also solve e.g., $f(x)=3$, by finding the $x$-coordinates corresponding to a $y$-coordinate of $3$.

# Common functions
Take a look at your book for some common functions and their graphs.

* Setting $f(x)$ to some constant gives a constant function e.g., $f(x)=3$, and It's graph is a horizontal line.
* The identity function is $f(x)=x$ and its graph a $45°$ line passing through the origin.
* The absolute value function is $f(x)=\vert x \vert$ and its graph is a V-shape.
* Quadratic functions are U shaped and possibly inverted
* The Cubic function are like the quadratic be it also have a $x^3$ term. In particular chicane
* Reciprocal has a vertical and a horizontal asymptote
* The square root function is only in the first quadrant. Domain and range
* Cube root function first and third quadrants. Domain and range. (also $x^\frac{1}{3}$ chicane

## Piecewise functions
$$
f(x)=
\begin{cases}
x^2 & x>1\\
2x & x \le 1\\
\end{cases}
$$
In Desmos, these can be graphed using separate formulas for each piece in the piecewise function.
The formulas for Desmos are $y=x^2\{x>1\}$ and $y=2x\{x\le 1\}$.

Piecewise functions have practical applications. Take for example a price listed as \$2.59, or for quantities of 4 or more \$1.99.
