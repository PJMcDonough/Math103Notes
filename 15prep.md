% Exam Prep
% Patrick McDonough for Prof. West
% 2022-01-07

**FTA (Fundamental Theorem of Algebra):** The degree of the polynomial is the number of complex factors where repeated factor are counted the number of times they repeat.

**Example:** Find a quadratic with the factors x=2 and x=-3. This is $p(x)=(x-2)(x-(-3))$. We don't have to simplify this to $p(x)=x^+x-6$.

**Example:** This is one the professor stumbled on in during a review of teaching. Find the quadratic with the real coefficients and a leading coefficient of $1$ that has the root $2+3i$.
This must also have the root $2-3i$. The answer is then $p(x)=(x-(2+3i))(x-(2-3i))$. Unfortunately this is hard to simplify, but we can do completing the square backwards.

$$\begin{align}
x&=2\pm 3i\\
(x-2)^2&=(\pm 3 i)^2\\
x^2-4x+4&=-9\\
x^2-4x+13&=0\\
\end{align}$$

This then gives that the polynomial is $p(x)=x^2-4x+13$, which is really neat!

**Example:** This problem should be significantly easier than anything on the test.
Consider $p(x)=3x^5+7x^4+61x^3+151x^2-350x-600$.
The suggestion is to graph using a graphing calculator to find some zeros.
An additional hit is given: "$5i$ is a zero".
By the additional hint, we also know $-5i$ is a zero, so $(x-5i)(x+5i)=(x^2+25)$ is a factor.
From graphing, we get the zeros $-3,-1,2$.
Synthetically dividing the given by $x-3$ gives $3x^4-3x^3+67x^2-50x-200$.
Synthetically dividing that by $x+2$ gives $3x^3+4x^2+75x+100$.
Long dividing that by $x^2+25$ gives $3x+4$.
Therefore, $p(x)=(x-3)(x+2)(3x+4)(x^2+25)$, and we're done.

