% Polynomials and Power functions  §§3.4-3.4
% Patrick McDonough for Prof. West
% 2022-02-21

Power functions are functions fo the form $f(x)=Kx^p$. A power function has only one term. 
An geometrical aplication of power functinos is the volume of a sphere: $V(r)=\frac 43 \pi r^3$.
In this case the coeficient is $\frac 43 \pi$.
The following are also power functions.
$$
f(x) = 1\quad
f(x) = x\quad
f(x) = x^2\quad
f(x) = \frac 1x\quad
f(x) = \frac 1{x^2}\quad
f(x) = \sqrt x\quad
$$
Recall that $\sqrt{x}=\sqrt[2]{x}$, and $\sqrt[n]{x}=x^{\frac 1n}$. 
The mnemonic for this is that power rhymes with flower, and both go above as opposed to roots which go below.
Also recall that $x^{-n}=\frac 1{x^n}$.
We can rewrite the above as follows.
$$
f(x) = 1x^0\quad
f(x) = 1x^1\quad
f(x) = 1x^2\quad
f(x) = 1x^{-1}\quad
f(x) = 1x^{-2}\quad
f(x) = 1x^\frac 12\quad
$$

Consider the functions $f(x)=-2x^6-x^5+3x^4+x^3$ and $g(x)=3x^5-4x^4+2x^2+1$.
The leading term is known as the term with the highest exponent.
The coefficient of the leading term is called the leading coefficient.
Constants are zeroth degree terms.

As $x$ gets a large positive value, the value of a polynomial will become large and take a sign according to part before the slash in the following chart. 
The sign after the slash indicates what happens when given a large negative value.

|	|even degree	|odd degree	|
|---	|	---	|	----	|
|LT (+)	|+/+ 		|+/-		|
|LT (-)	|-/-		|-/+		|

As the absolute value of the input to the polynomial gets larger, all the terms except for the leading term start to have a relatively smaller effect on the output.
Here's why.
When we factor $x^5$ out of $g(x)$, we get $g(x)=x^5(3-\frac 4x+\frac 2{x^3}+\frac1{x^5})$.
As $x\rightarrow\infty$, $(3-\frac 4x+\frac 2{x^3}+\frac1{x^5})\rightarrow 3$.
What this fancy math notation means is that all of $\frac 1{x^n}$ terms become very close to zero, so the bit in parentheses, in some sense for large $x$, may as well be three.
A similar argument works for very negative x.

We can see from the chart that $f$ goes down to the right and down to the left, whereas $g$ goes up on the right and down on the left.

# Graphing Polynomials
Consider $f(x)=-3x^2(x-1)(x+4)$.
For the $y$-intercept, set $x=0$ and find $y$.
In this case, that's just $f(0)=0$.
We can also find our $x$ intercepts by setting $f(x)=0$.
Since $f$ is given in factored form, we can read off the x coordinates of the x intercepts.
They are $0,1,-4$.
Since we are multiplying a second degree polynomial by two first degree polynomials, we get a polynomial with degree $2+1+1=4$.
If we really wanted to we could show this by explicitly multiplying.
From this, and the sign, we can see the end behavior is down on both sides (see above chart).

When we write out a polynomial in a factored form and we have $n$ copies of a given term, we way that term has multiplicity $n$.
The root $0$ has multiplicity $2$ and the roots $1$ and $-4$ have multiplicity $1$.
Consider an function of the form $f(x)=(x-k)^np(x)$ where $p$ is a polynomial with no roots near $k$.
Then near $k$, $f(x)$ is small, and all values of $p(x)$ near zero are, for purposes of multiplication near-enough to constant. 
Therefore, we can treat $f$ in this area as a polynomial and use the above table to note that for odd multiplicity, $f$ crosses the $x$-axis, and even multiplicity it bounces off it.
We can use this to draw all the crossings.
