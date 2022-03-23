% Exponential and logarithmic Function's (Chapter 4)
% Patrick McDonough for Prof. West
% 2022-03-23

## But first some other things
**Example:** Consider the following radical equation $\sqrt{x+1}+1=x$.
Use what you don't like to your advantage, and isolate the things you don't like.
So,
$$\begin{align}
\sqrt{x+1} &= x-1\\
x+1&= (x-1)^2\\
x+1&= x^2-2x+1\\
0  &= x^2-3x\\
0  &= (x)(x-3)\\
\end{align}$$
We the candidate solutions $x=0,3$
It turns out that $\sqrt{0+1}+1\ne 0$ but $\sqrt{3+1}+1=3$.
The *only* solution is $x=3$.

# §4.1 Exponential functions
**Definition:** An exponential function is a function of the form $f(x)=ab^x$ where $b$ is a positive constant called the base and $a$ is a constant called the initial value or coefficient
We also exclude the boring case where $b=1$, and therefore $f(x)=1^x=1$. 
We may also add a trailing constant.
The exponential function is *simple* if and only if $a=1$.

Note that $f(x)=x^2$ is not an exponential function. 
Neither is $f(x)=(-2)^x$, but $f(x)=-2^x=-(2^x)$ is.

Remember that for all $b$, $b^0$ is 1.
So for simple exponentials (i.e. functions of the form $f(x)=b^x$), $f(0)$=1.
Simple exponential functions have a VA of $y=0$.

**Example:** Consider the function $f(x)= 30(2)^x$. 
$$f(3)=30(2)^3=30(8)=240$$
Remember $f(3)\ne 60^3$.
Also $f(0)=30$, and more generally, for any exponential function $f(x)=ab^x$ $f(0)$ is the initial value $a$.

When $b>1$, we say $f$ grows, and when $b<1$ we say it decays. 
Note that growth can mean getting smaller, but if we ignore sign, it makes sense.

**Example:** India's population in 2013 was 1.25 Billion people. The population is growing at a rate of 1.2% per year. 
Find the estimated population in 2031.

*Hint:* You can assume the growth rate remains 1.2%.

We know that the base is $1+$ the growth.
(This is like how you have to multiply the sticker price by $1+$ the tax rate.)
With the given initial value, this gives the estimated population in billions as a function of years since 2013 as $p(t)=1.25(1.012)^t$.
The year 2031 is 18 years after 2013 because $2031-2013$, so its estimated population is $p(30)=1.25(1.012)^18=1.549$ i.e., 1.45 Billion people.
To do exponentiation on your calculator, use the button labeled $x^y$ or `^`.

## Compound interest
The formula for compound interest is
$$A(t)=P\left(1+\frac rn\right)^{nt}$$
Where
 - P is the principle (amount at the beginning)
 - r is the rate as a decimal $.06$ for 6%
 - n is the number of compounding periods per year (or unit of t)
 - t is time (years).

**Example:** Compounded annually, with 12% annual interest, how much will you have after 1 year on a principle of \$1000?
$$\begin{align}
A(1)&=1000\left(1+\frac{.12}{1}\right)^{1(1)}\\
A(1)&=1000\left(1.12\right)^1\\
A(1)&=1000\cdot 1.12\\
A(1)&=1120\\
\end{align}$$


**Example:** Compounded quarterly, with 12% annual interest, how much will you have after 1 year on a principle of \$1000?
$$\begin{align}
A(1)&=1000\left(1+.\frac{.12}{4}\right)^{4(1)}\\
A(1)&=1000\left(1.03\right)^4\\
A(1)&=1000\cdot 1.12551\\
A(1)&=1125.51\\
\end{align}$$


**Example:** Compounded quarterly, with 12% annual interest, how much will you have after 1 year on a principle of \$1000?
$$\begin{align}
A(1)&=1000\left(1+.\frac{.12}{12}\right)^{12(1)}\\
A(1)&=1000\left(1.01\right)^12\\
A(1)&=1000\cdot 1.12683\\
A(1)&=1126.83\\
\end{align}$$

The more frequently things are compounded, the more money interest produces, but as the period goes to zero, we approach something called continuous growth.
This is given by

$$A(t)=Pe^{rt}$$.
The constant $e$ is approximately $2.718281828459$.
This goes on and never repeats.

**Example:** Radon-222 decays at a continuous rate of 17.3% per day.
100mg decays to what in 3 days?

We get $A(3)=100e^{-.173\cdot 3}=100e^{-.519}=59.5115$. So we're left with $59.5115mg$.

**Example:** An exponential function $f(x)=ab^x$ passes through the point (-2,6) and (2,1). Find $a$ and $b$.

By the first point, 
$$\begin{align}
f(-2)&=6\\
f(-2)&=ab^{-2}\\
6&=ab^{-2}\\
6b^2&=a\\
\end{align}$$

Similarly

$$\begin{align}
f(2)&=1\\
f(2)&=ab^2\\
1&=ab^2\\
1&=(6b^2)b^2\\
\frac 16 &= b^4\\
b&= \sqrt[4]{\frac 16}\\
\end{align}$$

We get that $b$ is approximately $.6389$ and we can substitute to find $a$ is approximately $2.4492$.

Transformation techniques work just as well for exponential functions as for the other functions we covered.
Putting a negative sign on the $x$ flips the graph horizontally.
Exponentialls have an interesting property, that the verticall streach is the initial value or equivilenty the $y$-intercept.

**Most Important Lesson From This Class:** Because of the way exponentials work, when you start saving matters *much* more than when you stop saving.
