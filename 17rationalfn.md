% Rational Funcionts (§3.7)
% Patrick McDonough for Prof. West
% 2022-03-21

**Definition:** A rational function is a function of the form $R(x)=\frac{P(x)}{Q(x)}$ where $P$ and $Q$ are polynomials and $Q(x)\ne 0$.

Note that $f(x) = \frac 1x$ is  a rational function because both $1$ and $x$ are polynomials because they are both monomials $1x^0$ and $1x^1$ respectively.

**New notation:** $x\rightarrow a^{-}$ means x gets closer from the negative (LH) side, $x\rightarrow a^{+}$ means x gets closer from the positive (RH) side $x\rightarrow a$ means x gets closer from both sides.

If we continue to consder $f(x)=\frac 1x$, by plugging in progressively smaller values, we can come to the conclusion that, as $x\rightarrow 0^+$ we have $f(x)\rightarrow\infty$.
Doing this for negative numbers gives if $x\rightarrow 0^-$, then $f(x)\rightarrow-\infty$.
Doing this yourself is instructive.
We can also see that  if $x\rightarrow \pm\infty$, then $f(x)\rightarrow 0$.

We can also graph.
This allows us to see that there are lines that the graph doesn't touch but keeps getting closer to.
These are called asymptotes.
There are both vertical and horizontal asymptotes abbreviated VA and HA respectively.
Functions have at most 2 HAs and rational functions have at most one HA, but a rational function my have any finite number of VAs, and some trig functions have infinitely many.
Functions can cross horizontal, but not vertical asymptotes.

#Rules for finding Asymptotes

## Vertical

To find the VA of a rational function, factor the numerator and denominator:

1. Factor the numerator and denominator
2. Note the domain restrictions of the function i.e., zeros of the denominator.
3. Reduce the expression (cancel)
4. The zeros of the new denominator are the $x$-location of the VA.

**Ex:** Consider $R(x)=\frac{x+2}{x^2-4}$.So,
$$\begin{align}
R(x)=\frac{x+2}{x^2-4}\\
R(x)=\frac{x+2}{(x+2)(x-2)} \text{Restrictions $x\ne \pm 2$}\\
R(x)=\frac{1}{x-2}\\
\end{align}$$
So,the equation of the VA is $x=2$, and we have a removable discontinutiy (i.e., a hole in the graph) at $x=-2$.
The VA and HA divide the plane into four parts.
You can plug in test values of $x$ on each side of the VA, and then note that it will usually hug both sides.
We can check to see if the function goes through the line $x=k$, we can simply solve $R(x)=k$.
In this case, we simply need to note that there are no zeros of the functions.

## Horizontal
1. If the degree of the polynomial in the denominator is greater than the degree of the numerator, the HA is $x=0$ because the bottom grows faster than the top.
2. If the degree of the polynomial in the denominator is equal to the degree of the numerator, the HA is $x=$ the ratio of the lead coefficients because the lead terms grow faster than other terms. 
2. If the degree of the polynomial in the denominator is one less than the degree of the numerator, you do not get a HA, but you *do* get a slant asymptote (also called oblique)

**Example:** Consider 
$$R(x)=\frac{3x^2-2x+1}{x-1}$$
We get the slant asymptote $y=3x+1$. This can be shown by long, or in this case synthetic, division.

# Reminders
To find the $y$-intercept, set $x=0$ and solve.
To find the $x$-intercept, set $y=0$ and solve.
In the case of rational functions, to find zeros, we can find the zeros of the numerator and then exclude any values that end up being zeros of the denominator.

**Example:** Consider 
$$R(x)=\frac{x^2-x-6}{x^2-16}$$
Find any VA, HA, $y$-intercepts, and $x$-intercepts.

*Hint:* factor.

*Solution:* 
We have

$$R(x)=\frac{(x-3)(x+2)}{(x-4)(x+4)}$$

The real of the denominator are $\pm 4$, so the domain is all real numbers except those values.
The vertical asymptotes are $x=4$ and $x=-4$ because there is no canceling.
By HA rule #2 above, the HA is x=1.
The $y$-intercept is $y=R(0)=\frac{-6}{16}=\frac 38$.
The $x$-intercepts can the be found by solving $(x-3)(x-+2)=0$.
This gives the solutions $x=3$ and $x=2$, which are the VAs.
