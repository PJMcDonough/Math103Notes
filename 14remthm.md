% Remainder Theorem
% Patrick McDonough for Prof. West
% 2022-01-03

**Remainder Theorem:** Given a given polynomial $p(x)$ divided by $x-k$, then the remainder is $p(k)$. 

Consider $p(x)= 6x^4-x^3+x^2-7$.
We would like to know if $x-2$ is a factor.
We can use synthetic division to find this out explicitly (which would be my preference) or we can do long division.
In either case, we find that $p(2)=85$ and therefore, $x-2$ is not a factor.
If we do the synthetic division, we find the quotient $6x^3+11x^2+22x+46$ along with the remainder $85$.
It is important to include the zero coefficient when we do the long division.

We already know the special case for $p(x)=0$. It's called the Factor Theorem.

**Factor Theorem:** The number $k$ is a zero of $p(x)$ if and only if $x-k$ is a factor of $p(x)$.

The quadratic formula is relatively simple, but the cubic formula is more complicated, and the quartic formula is very complicated.
There is no formula for higher order polynomial.
The guy who found this out unfortunately died in a duel at age 19.
Because of this, we have to resort to guessing, but we can do this somewhat intelligently.

**Rational Root Theorem** If a polynomial $f(x)$ with integer coefficients has rational roots (i.e. roots of the form $\frac pq$ with $p,q$ integers), then
 $p$ will be a factor of the trailing coefficient, and
 $q$ will be a factor of the leading coefficient. 

We continue with the polynomial $p(x)= x^3-6x^2-x+30$.
The factors of $30$ are $\pm 1$, $\pm 2$, $\pm 3$, $\pm 5$, $\pm 6$, $\pm 10$, $\pm 15$, $\pm 30$ and the factors of $1$ are $\pm 1$.
So we get possible factors of $\frac{\pm 1}{\pm 1}$, $\frac{\pm 2}{\pm 1}$, $\frac{\pm 3}{\pm 1}$, $\frac{\pm 5}{\pm 1}$, $\frac{\pm 6}{\pm 1}$, $\frac{\pm 10}{\pm 1}$, $\frac{\pm 15}{\pm 1}$, \frac{}{\pm 1}$\frac{\pm 30}{\pm 1}$. 
Because of the way the $\pm$s work, we can rewrite this list as $\pm 1$, $\pm 2$, $\pm 3$, $\pm 5$, $\pm 6$, $\pm 10$, $\pm 15$, $\pm 30$.
Trying $3$ gives $p(3)=0$, and therefore, $3$ is a zero.
By the way we did the synthetic division we get $p(x)=(x-3)(x^2-3x-10)$.
The quadratic is much easier to factor, giving $p(x)=(x-3)(x-5)(x+2)$.
This can get quite complicated if either the leading coefficient or trailing constant is highly divisible (e.g. 24 with positve integer factors of 1,2,3,5,6.
On the test, they won't be highly divisible, unlike at Moorpark college.

Fun fact!: Ye olden mathematicians were regarded as philosophers, because people realized how philosophical math is.
St. Thomas Aquinas was were we got our ideas of infinity from.

**Descartes' Rule of Signs:** Given a polynomial written in descending order (the normal order), the number of sign-changes is the number of positive real zeros (or less by a multiple of two).
To find the number of negative real zeros, substitute $p(-x)$ and apply the same rule.

Descartes' Rule of Signs can allow you to cut your work in half sometimes.

Consider $p(x)=x^3+6x^2+11x+6$. 
Note that there are no sign changes and therefore no positive roots, but for $p(-x)=-x^3+6x^2-11x+6$.
By Descartes' rule of signs, there are either three negative roots of $p$.
To find the roots, by the above theorems, we only have to check $-1$, $-2$, $-3$, and $-6$.
By synthetic division we get $p(x)=(x+3)(x^2+3x+2)$.
It turns out that three of the possible four guesses were right.
You may be able to see that we can factor this as $p(x)=(x+3)(x+2)(x+1)$.
Graphing this is doable-enough.

**Fundamental Theorem of Algebra:** Any polynomial of degree $n$ can be factored as $(x-c_1)(x-c_2)\ldots(x-c_n)$ where $c_1,c_2\ldots c_n$ are complex.
Equivalently, counting multiplicity every $n$th degree polynomial has exactly $n$ complex roots.

Consider the polynomial $f(x)=4x^3-3x-1$. We get rational root theorem values of $p=\pm 1$, $q=\pm 1,\pm 2,\pm 4$, and $\frac pq = \pm 1, \pm \frac 12, \pm \frac 14$.
So we can factor this as $f(x)=(x+\frac 12)(4x^2-2x-2)$. We simplify this to $$p(x)=(x+\frac 12)2(2x^2-x-1)=(2x+1)(2x^2-x-1)=(2x+1)^2(x-1).$$

A final example:
$$\begin{align}
x^2+1&=0\\
x^2&=-1\\
x&=\pm\sqrt{-1}\\
x&=\pm i\\
x^2+1&=(x-i)(x+i)\\
\end{align}$$

In a polynomial with real coefficients, whenever you have a non-real zero, its conjugate is also a zero. In other words for real $a,b$, if $a+bi$ is a zero, so is $a-bi$.
The multiplicities are also the same.
