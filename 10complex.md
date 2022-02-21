% Complex Numbers §3.1
% Patrick McDonough for Prof. West
% 2022-02-14 -- 2022-02-21

# Backstory
The exact order of events here is not completely accurate, but it is instructive.
In the beginning, we just had counting numbers: 1, 2, 3, 4, 5.
Then they invented 0 and thought, hey this is just as much of a number as those other numbers.
Then people invented things like debt and decided to describe things with negative numbers.
Then the Egyptians decided they needed to describe how much bread each person gets if you divide two loaves of bread among three people.
Then irrational numbers.
A cult called the Pythagorean lead by Pythagoras believed that all numbers were rational, but then someone proved that $\sqrt 2$ is irrational.
They drowned him.

# Imaginary  numbers
So people invented the number $i=\sqrt 1$ which made math easier, and like many of the inventions before it, still follows the rules of math.
The number $i$ is sometimes called the imaginary unit.
You may find it interesting to hear that the reason imaginary numbers were created to find *real* solutions to equations of the for $ax^3+bx^2+cx+d=0$
In some ways, imaginary numbers are more real than real numbers because physics simply requires it.
Complex numbers "all" numbers.
They can be written with real $a$ and $b$ in the form $a+bi$.
Consider for example $7=7+0i$ and $i=0+1i$.

# Operations
Consider the following examples of operations 
$$\sqrt{-16}=\sqrt{-1}\sqrt{16}=i4=4i$$.
Adding two complex numbers works just like combining like terms. In fact, it is combining like terms. 
$$(2+3i)+(5-7i)= (2+5)+(3-7)i =7-4i$$.
The same can be said of subtracting. 
$$
\begin{align}
(3+2i)-(2-i)&=(3-2)+(2+1)i\\
&=1+3i
\end{align}$$
Multiplication is done by FOILing just like if you are multiplying $(1+x)$+$(1-x)$ except that we know $i^2=-1$.
$$
\begin{align}
(2+5i)(3-2i)&=2(3)+2(-2i)+5i(3)+5i(-2i)\\
&=6-4i+15i-10i^2\\
&=6-4i+15i+10\\
&=16+11i\\
\end{align}
$$

We can show by FOILing that for any two constants $a$ and $b$, $(a+bi)(a-bi)=a^2+b^2$.
Any two numbers of the form $a+bi$, and  $a-bi$ are called complex conjugates. 
Note that the only difference is the sign in the middle.
To find the conjugate of a complex number written as $a+bi$, rewrite it as $a-bi$, or vice versa.
This comes from a difference of squares, which results in the fact that the product of a complex number and its conjugate is real.
The coefficients $a$ and $b$ may well be zero, so real numbers are there own conjugates and $\frac 23 i$ and $-\frac 23i$ are conjugates.
When one of the coefficient's is $0$, we often don't write that term.

Division is more complicated, but not terribly so. To divide $2+5i$ by $4-i$, we proceed as follows.
$$
\begin{align}
\frac{2+5i}{4-i}&= \frac{2+5i}{4-i}\cdot \frac{4+i}{4+i}
&=\frac{(2+5i)(4+i)}{(4-i)(4+i)}
&=\frac{8+2i+20i-5}{4^2-i^2}
&=\frac{3+22i}{17}
&=\frac 3{17}+\frac{22}{17}i
\end{align}
$$

Recall that any nonzero real number raised to the 0th power is 1.
This actually holds for all complex numbers.
Similarly recall that any real number to the 1st power is that number.
This also holds for all complex number.
Similarly just like for real numbers, for any complex $x,y,z$, $x^yx^z=x^{y+z}$ and $(x^y)^z=x^{yz}$.

See the following table, and note that it repeats. The left and right columns are equal.

|i^0| 1|
|i^1| i|
|i^2| -1|
|i^3| -i|
|i^4| 1|
|i^5| i|
|i^6| -1|
|i^7| -i|

Because of the above we know $i^{2001}=(i^4)^{500}i=1^4i=i$.
You can also do this by saying 4 goes into 2001  500 times with a remainder of 1.
Only the remainder matters here, and we simply raise $i$ to that power.
