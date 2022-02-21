% Quadratics §3.2
% Patrick McDonough for Prof. West
% 2022-02-21

The general form of a quadratic function is $f(x)=ax^2+bx+c$.
This is not to say that something is not a quadratic if it's written a little differently, but we can rearrange any quadratic into that form.

Recall the quadratic formula. Remember to divide the entire numerator by the denominator, not just part of it.

$$x = \frac{-b\pm \sqrt{b^2-4ac}}{2a}$$

We frequently use this formula when there is not a nice way to factor.
You could just always use it, but factoring is frequently easier.

There is another, poorly named, form called standard form.
A better name for it is vertex form.
We write this as $f(x)=a(x-h)^2+k$.

If $a$, is positive the parabola is smile shaped, and if $a$ is negative, the parabola is frown-shaped.
The vertex (i.e. flat bit) of the parabola is at $(h,k)$.
We can also find the vertex from general form.
The $x$-value is given by $\frac{-b}{2a}$.
The other coordinate can then be found by evaluating the function at the given $x$-value.
In other words, it's the point $(\frac{-b}{2a},f\left(\frac{-b}{2a}\right))$.
For example, the vertex of the graph of $f(x)=x^2+4x-5$ is $(-2,-9)$.
We can do graphing based on this.
Remember that parabolas are symmetrical.

To find the $x$-intercepts of the graph of $x^2+4x-5$, we solve $x^2+4x-5=0$ by factoring into $(x+5)(x-1)$.
This tells us that the solutions are $x=1,5$.
We could also use the quadrati formula if we really wanted to. 
This gives $$x=\frac{-4\pm\sqrt{4^2-4(1)(-5)}}{2(1)}=\frac{-4\pm{16+20}}{2}=\frac{-4\pm\sqrt{36}}{2}=\frac{-4\pm 6}{2}= -2 \pm 3 = 1,-5$$

Similarly we can find the vertex using a technique called completing the square.
$$\begin{align}
f(x)&=x^2+4x-5\\
f(x)&=(x^2+4x)-5\\
f(x)&=(x^2+4x+4)-5-4\\
f(x)&=(x+2)^2-9\\
\end{align}$$
Now it's in vertex form.
Also note that completing the square only really works when the lead coefficient is 1, but we can fix this by factoring.

Instead of doing that, we could have used the formulas for the vertex given above.
Here's another example.
To find the vertex of the graph of the functions $f(x)=2x^2+4x-4$, we can use the formulas to see that the x coordinate is $\frac{-4}{2(2)}=-1$.
Then we can plug in to see that the $y$-value of the vertex is $2$.
Vertex form is $f(x)=2(x+1)^2+2$.
We can find $x$-intercepts by setting the vertex form to $0$, and adding 6 to both sides giving $6=2(x+1)$.
We can the look at the square roots giving $\pm\sqrt 3=x+1$.
solving gives $x=-1\pm\sqrt 3$.
