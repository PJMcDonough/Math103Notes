% Modelling §§2.2-3.3
% Patrick McDonough for Prof. West
% 2022-02-14 -- 2022-02-14

Consider the example of inflation.
Let's consider Phil's function for how much things will cost in a year given 7.5% inflation.
By the definition of percent inflation, we have $p(x)=x+.075x$, which we can rewrite as $p(x)=1.075x$.
The $y$-intercept is $0$ which means that stuff not being free anymore isn't inflation.

# Finding $x$- and $y$-intercepts
For a function $f$, the $y$ intercept is $f(0)$.
In the case of slope-intercept ($mx+b$) form, this is $m$.
The x intercept is the solution to $f(x)=0$.
In the case of slope-intercept form, this means solving $0=mx+b$ for $x$.
This gives $x=-\frac bm$.

A more mnemonic way of looking at this is: to find the $x$-intercept set $y=0$.
Similarly, to find the $y$-intercept set $x=0$.

# Point-slope form
Point-slope form is $y-y_1=m(x-x_1)$.
Lets say we want to find an equation for a line passing through the point $(1,2)$ and parallel to $y=3x+6$.
Since the slope of the given line is $3$, and we know the point, we want to go through, we can substitute giving $y-2=3(x-1)$.
If we want point-slope, we algebra our way to $y=3x-1$.
See [Desmos](https://www.desmos.com/calculator/btzinz9omy).

## Perpendicular lines
Let's say we want a line through the same point and perpendicular to the original formula.
We need to know that two linear functions describe perpendicular lines if and only if their slopes are flipped with opposite sign i.e., $m_1m_2=-1$.
You can convince yourself of this from the definition of perpendicular by drawing a line through the origin and rotate it 90° (which is the measure of the angle in a square).
Now that we know this, we can write the perpendicular line as $y-2=-\frac 13(x-1)$.
If we really wanted to, we could write this in slope-intercept form as $y= -\frac 13x + \frac 53$.

## Example problem
This example is from §2.3.
Suppose VRBO has a plaace avalibe for \$85 per day and a $200 cleaning fee.
How much will it cost (in dollars) to go for $x$ days?

The answer is given by the function $f(x)=85x+200$.
