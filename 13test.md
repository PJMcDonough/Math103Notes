% Upcoming Test
% Patrick McDonough for Prof. West
% 2022-02-28

There will be a test on Wednesday March 9, and a practice test the preceding Monday (March 7).
You can bring a 3"x5" index card with notes to the Test.
You may also bring a **five-function** calculator.
The calculator should not be able to perform any math other than addition subtraction multiplication division and roots.

# Intermediate Value Theorem
This is normally covered in calculus, but we provide a reasonable summary of it here.
Let $f$ be a polynomial, and consider two numbers $a$ and $b$.
If $f(a)$ and $f(b)$ have opposite signs, then there is some value $c$ strictly between $a$ and $b$ where $f(c)=0$.

We can also apply this theorem to certain other functions that are not polynomials.
As an aside, we call this type of function continuous on $[a,b]$.

If you plot $f(x)$ against $x$ and note the points $\big(a,f(a)\big)$ and $\big(a,f(a)\big)$, this should make intuitive sense.

Consider the polynomial $f(x)=x^3-5x^2+3x+6$.
By rote computation we can determine that $f(3)=-3$ and $f(4)=+2$.
By the Intermediate Value Theorem, we can conclude that there is a zero between $3$ and $4$.

Continuing with the above example, we can check the sign of $f(3.5)=-1.875$.
Because it's negative, we can see there is a root in the interval $(3.5,4.0)$.
After this, we can also check $3.75$ to determine if it is in the interval $(3.5,3.75)$ or $(3.75,4)$

# Division
Consider the question "Does 12 go into 75 evenly" or equivalently "Is 12 a factor of 75".
At first when they taught you division you were likely taught to say "It goes in 6 times with a remainder of 3" written "$6R3$".
When dividing 17 by 3, we get the result $17R0$, so 51 is a multiple of 3.
It's a useful fact that a number is divisible by 3 if and only if the sum of its digits is.
When we do divide $A$ by $B$, we call $B$ the divisor, and $A$ the dividend.
The result is called the quotient, and the bit left over is the remainder.

We can do polynomial long division the same way we do ordinary long division.
There is a neat theorem that, given a polynomial $p(x)$, $p(k)=0$ if and only if $x-k$ is a factor of $p(x)$.
More generally, if we divide $p(x)$ by $x-k$, the remainder is always $p(k)$.
This is called the remainder theorem.

## Synthetic Division
See your own notes, or the text book for this section. It's hard to type up.

## Example
Say you want to find the zeros of $f(x)=x^3-6x^2-x+30$.
If you somehow know or guess that $x+2$ is a factor, you can use synthetic division to see that $f(x)=(x+2)(x^2-8x+15)$.
You can then factor and see the zeros.
