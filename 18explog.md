% Exponential and logarithmic Function's (Chapter 4)
% Patrick McDonough for Prof. West
% 2022-03-23 -- 2022-03-23

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

**Most Important Lesson From This Class:** Because of the way exponentials work, when you start saving matters *much* more than when you stop saving.

## $e^x$
Recall the compound intrest formula, and take $P,t=1$.
Then we have $A=(1+\frac 1n)^n$.
For $n=1$, we have $A=(1+\frac 11)^1=2$.
For $n=2$, we have $A=(1+\frac 12)^2=2.25$.
Larger $n$ results in a larger number.
If you imagine graphing this, there is a vertical asymptote at $e$.
We say that this approaches $e$.

The constant $e$ is very important in lots of different parts of math.

There is a famous theorem that $e^{i\pi}+1=0$ which is rather profound.

## Graphing

Transformation techniques work just as well for exponential functions as for the other functions we covered.
Putting a negative sign on the $x$ flips the graph horizontally.
Exponentials have an interesting property, that the vertical stretch is the initial value or equivalently the $y$-intercept.

Consider $f(x)=ab^{x+c}+d$. 
The constant $a$ stretches, vertically, and if negative flips vertically, $b$ controls the rate of growth ($b>1$) or decay ($b<1$), $c$ shifts to the left, and $d$ shifts up.
See Mr. West's Desmos graph tool. 

**Example** (6 in book): Give an exponential with base $e$ stretched vertically by a factor of 2, flipped across the $y$-axis and shifted up 3.
This gives the solution $f(x)=2e^{-x}+3$ when we substitute into the previous formula and recalled how to flip across the $y$-axis.

You should be able to prove to yourself that $b^{-x} = \left(\frac 1b\right)^x$

# Logarithmic Functions (§4.3)

Note that all exponential functions are one-to-one.
In other words, they pass the horizontal line test.
All one-to-one functions have inverse "undoing" functions.

Recall that to find an inverse $f^{-1}(x)$ of $f(x)$.

1. Change $f(x)$ to $y$.
2. Swap $x$ and $y$.
3. Solve for $y$.
4. Change $y$ to $f^{-1}(x)$

Let's do this with exponential functions.
Let $f(x)=2^x$.

1. $y=2^x$
2. $x=2^y$
3. The best we could do with our level of knowledge is just to say $y=$ The exponent to which you raise the base $2$ in order to get $x$. We just described the inverse function of the exponential function. We call this function $log_2(x)$. More generally, we can talk bout $log_b(x)$.
4. $f^{-1}(x)=\log_2(x)$

**Example:** What's $\log_2(8)$. In other words, by applying the definition given in step 3, what is the exponent to which you raise the base $2$ in order to get $8$. 
We can see that it is $3$ because $2^3=8$.

Note that more generally $y=\log_b(x)$ if and only if $b^y=x$.
This is the "mother of all $\log$ identities".

Logs are inverse functions for exponentials.
When we find inverses, we swap the $x$s and $y$s.
The domain of an exponential is the range of the corresponding logarithm and vice versa.
The domain of an exponential is all real numbers i.e., $(-\infty,\infty)$, and the range is all positive numbers i.e., $(0,\infty)$.
The domain of a log is $(0,\infty)$, and the range is $(-\infty,\infty)$.

**Example:** convert to exponential

1. $\log_6(\sqrt 6)=\frac 12$. So, $\sqrt 6 = 6^{\frac 12}$.
2. $log_3(9)=2$. So, $3^2=9$.


**Example:** convert to $\log$ equation

1. $5^3=125$. So, $log_5(125)=3$.
2. $10^{-4}=\frac 1{10000}$. So, $\log_{10}(\frac 1{10000}=-4$ which makes sense because $\log_{10}(10000)=4$

In this class, as well as in the financial and engineering fields, when we write $\log$ without a base, we mean $\log_{10}$.
Confusingly in other subjects like analysis of algorithms, $\log$ means $\log_2$.
You will also see $\log_e$ written $\ln$.
Also confusingly, in other classes you may also see *this* written $\log$.

**Example:** There was an earthquake in Northridge in 1993.
It was 500 times more powerful than a 4.0 earthquake. 
Earthquakes are measured in a base-10 exponential scale.
Use this fact $10^x=500$ where $x$ is the difference in magnitude.
We then know that $x=\log(500)$.
This is approximately $2.7$.
Therefore, it was approximately a $6.7$ magnitude earthquake.

## Graphing
Since they are inverses, a logarithmic function is an exponential reflected across $y=x$.
Note that, even with the restriction on domain, $f(x)=-\log(x)$ reflects over the $y$-axis.

#Logs
## Domain and Range (§4.4)
The domain of exponential functions is all real numbers. The range is $(0,\infty), the positive numbers.

The domain of $log_b(x)$ is $(0,\infty)$, the positive numbers.

We have to do algebra to find the domain of $\log_2(6-3x)$.
We solve 

$$\begin{align}
6-3x&>0
-3x&>6
x&<2
\end{align}$$

Remember to flip the $>$ on the last step when we devide by a negative number becuase
$$\begin{align}
-3x>6
0>3x-6
6>3x
2>x
x<2
\end{align}$$

This proof of the flipping thing is, in my view remarkably beautiful.

We can use set-builder notation to write the domain as $\{x\vert x<2\}$
Note that negative $x$-values are OK here because it's the argument of the log that we care about..

## Graphing (§4.4)
Remember that you can use the origami method and reflect a function about $y=x$ to get its inverse by folding.
In Desmos, and math more generally, we can do this by swapping $x$ and $y$.
Also in Desmos, in the functions menu, below the calculus, there is a function for log to an arbitrary base.
This can also be typed as `log_2`.
The underscore character `_` is typed like a dash `-` (to the right of 0), but you have to hold shift.

All the shifting operations work as usual.
The professor provides some demonstrations of this.

In reality, we when we want to build something we don't usually need perfect answers.
Three decimal places is usually enough, and the inputs are frequently less precise than that.
This makes solving things by graphing make sense.

Say we want to solve $4\ln(x)+1=-2\ln(x-1)$.
We might as well solve this by graphing because the algebraic solution is incredibly complicated. 
Graph the LHS and the RHS. 
The $x$-value of their intersection is the solution.
When two roads cross, we call that an intersection.
The same is true of two curves.

## Properties of logarithms (§4.5)
There are an unlimited number of log identities, but remembering these is usually enough to make your life continent.
Most of the rest can be derived from these relatively easily.
When I say "iff", that means "if and only if" or equivalently that the two statement are equivalent.

The mother of all log identities is the definition of $log_b$: $y=log_b(x)$ iff $b^y=x$.

The identity $\log_b(MN)=\log_b(M)+log_b(N)$ is useful. We prove it here. 
Let $P=\log_b(M)$. Let $Q=\log_b(N)$.
So, by MOALI $b^P=M$ and $b^Q=N$.
By substitution, and then further algebra, then more substitution,
$$\log_b(MN)=\log_b(b^Pb^Q)=\log_b(b^{P+Q})=P+Q=\log_b(M)+\log_b(N)$$
For example $\log_2(4\cdot 8)=\log_2(4)+\log_2(8)$
Not having to the multiplication makes simplifying this to $5$ easier, especially because most people don't know $2^5=32$.


Another nice identity is $\log_b(M^P)=P\log_b(M)$.
This is probably the second most important log identity.
This is not surprising given that by the preceding rule, $\log_b(M^2)=\log_b(M\cdot M)=\log_b(M)+ \log_b(M)=2\log_b(M)$.

Finally, we have the identity given by the following proof using the previously mentioned log identities and some algebra.
$$\log_b\left(\frac MN\right)=\log_b(MN^{-1})=\log_b(M)+\log_b(N^{-1})=\log_b(M)-\log_b(N)$$

The change of base formula is $\log_b(M)=\frac{\log_a(M)}{\log_a(b)}$.
The constant $a$ is the base we want to convert to, and $b$ is the base we have to convert from.
Using slightly different notation and taking $a=e$ and $a=10$ gives the formulas $\log_b(M)=\frac{\ln(M)}{\ln(b)}$ and $\log_b(M)=\frac{log(M)}{log(b)}$ 

We also have the one-to-one property that $b^s=b^t$ iff $s=t$.

## Expanding and Condensing Logs
**Example:** Expand 
$$\ln\left(\frac{x^4y}{7}\right)$$

*Solution:* By our final identity we get that this is $\ln(x^4y)-ln(7)$.
We can further simplify this by the first and second identities to $\ln(x^4)+ln(y)-y=4\ln(x)+ln(y)-y$

**Example:** Condense $log_3(5)+log_3(8)-log_3(2)$

*Solution:* By similar reasoning, and some arithmetic simplification we get $\log_3(20)$

**Example:** Condense to a single logarithm $log_2(x^2)+\frac 12 \log_2(x-1)-3\log_2(x+3)^2$

*Solution:* 
$$\begin{align}
&\log_2(x^2)+\frac 12 \log_2(x-1)-3\log_2(x+3)^2\\
&=\log_2(x^2)+\log_2(x-1)^{\frac 12} -\log_2((x+3)^2)^3\\
&=\log_2(x^2)+\log_2sqrt{x-1} -\log_2((x+3)^6)\\
&=\log_2(x^2sqrt{x-1}) -\log_2((x+3)^6)\\
&=\log_2\left(\frac{x^2sqrt{x-1}} {(x+3)^6}\right)\\
\end{align$$

# Exponential and logarithmic equations (§4.6)
We should plug our answers back in to check that we didn't make any mistakes, but I omit that here.

**Example:** Remember that when we divide we subtract exponents because we can cancel.
$$\begin{align}
3^{4x-7}&=\frac{3^{2x}}3\\
3^{4x-7}&=\frac{3^{2x}}{3^1}\\
3^{4x-7}&=3^{2x}3^{-1}\\
3^{4x-7}&=3^{2x-1}\\
4x-7&=2x-1\\
4x&=2x+6\\
2x&=6\\
x&=3
\end{align}$$

**Example:**
$$\begin{align}
32&=4^{x-2}\\
2^5&=\left(2^2\right)^{x-2}\\
2^5&=2^{2(x-2)}\\
5&=2(x-2)\\
5&=2x-4\\
9&=2x\\
\frac 92&=x
\end{align}$$

**Example:** Now we need logarithms. Recall $\log_bM^P=P\log_bM$. The professor used $\log_{10}$. We use $\ln$ here.
$$\begin{align}
3^{x+2}&=4^x\\
\ln 3^{x+2}&=\ln 4^x\\
(x+2)\ln(3)&= x \ln(4)\\
x\ln(3) +2\ln(3) &= x \ln(4)\\
x\ln(3) -x\ln(4) &= -2 \ln(3)\\
x(\ln(3)-\ln(4)) &= -2 \ln(3)\\
x &= \frac{-2 \ln(3)}{\ln(3)-\ln(4)}\\
x &= \frac{2 \ln(3)}{\ln(4)-\ln(3)}\\
\end{align}$$

**Example:** This kind of thing shows up in biology. We can do this simply by using the log identity $\log_bb^x=x$ with $b=e$.
$$\begin{align}
100&=20e^{2t}\\
5&=e^{2t}\\
\ln(5)&=2t\\
t&=\frac 12 \ln(5)\\
\end{align}$$
*Hint*: don't use $\log_{10}. It takes longer and gives a less simplified answer.
$$\begin{align}
100&=20e^{2t}\\
5&=e^{2t}\\
\log(5)&=2t\log(e)\\
t&=\frac 12 \frac{\log(5)}{\log(e)}\\
\end{align}$$
We can see that these answers are equivalent using the change of base formula, or by convincing yourself with your calculator.

**Example:** Something like this will probably be on the test.
$$\begin{align}
\log_b(2)&\cong .301\\
\log_b(3)&\cong .477\\
\log_b(5)&\cong .699\\
\end{align}$$
What's $\log_b(\frac 9{10})$?
*Solution:* $\log_b(\frac 9{10})= \log_b(9)-\log_b(10)= 2\log_b(3)-(\log_b(2)+\log_b(5))\cong -.046$

**Example:** Something like this will be on the test.

$$\begin{align}
\log(x)+log(x+3)&=1\\
\log\left(x(x+3)\right)&=1\\
x(x+3)&=10\\
x^2+3x-10&=0\\
(x+5)(x-2)&=0\\
x&=-5,2
\end{align}$$
But we have to reject $x=-5$ because $\log(-5)$ is undefined leaving the only solution as $x=2$.

