% Linear functions §2.1
% Patrick McDonough for Prof. West
% 2022-02-09 -- 2022-02-14

When we look to see if a function is increasing, we go from left to right. 
[Here](https://www.desmos.com/calculator/xcpdnt45b9), I provide an example of an increasing, decreasing and constant function (black, red and blue respectively).
Make sure to go left to right.
If you say, "oh it goes up and to the left", you'll get the problem wrong, because it goes down and to the right.

Linear functions are functions of the form $y=mx+b$. Where $m$ is slope and
  
See the following [Desmos example](https://www.desmos.com/calculator/ryaggxuc33) to play with $m$ and $b$.
$$m=\frac{\text{Rise (i.e. up)}}{\text{Run (i.e. right)}}=\frac{\Delta x}{\Delta y} = \frac{y_2-y_1}{x_2-x_1}$$
The slope can have interpretable units.
For example, $m$ may be a speed.
If you drive at a constant speed for 6 hours, and go 420 miles, you will find your speed as
$$\frac{\Delta \text{Distance}}{\Delta \text{Time}}=\frac{420\mathrm{mi}}{6\mathrm{h}}=70\mathrm{\frac{mi}{h}}=70\mathrm{mph}$$
If you do it upside down, you will see your answer is wrong because the units will be for pace rather than speed (this is like what runners mean say when they say 10 minute mile pace).

We have a general formula for the slope . $x$ and $y$ are taken to be any ______ on the line, and $x_1$ and $y_1$ are the coordinates of the point we are interested in.
We can algebra this to the final equation below which is known as point-slope form.
$$\begin{align}
m = \frac{y-y_1}{x-x_1}\\
m(x-x_1)=y-y_1\\
y-y_1=m(x-x_1)\\
\end{align}$$

Consider the line defined by the points $(-1,-8)$ and $(4,2)$.
We want a formula for the line in point-slope form.
We can find the slope of the line using the defining formula above, and plug that into the point-slope form.
Note that we can chose either point for this, but to show you how we didn't do it in class, I'll chose to do it this way.
I performed all the substitutions in one step, and wrote $+$ instead of $--$, but the calculation is equivalent to the professor's work.
$$\begin{align}
y+8&=\frac{2+8}{4-1}(x+1)\\
y+8&=2(x+1)\\
y+8&=2x+2\\
y&=2x-6\\
\end{align}$$

The neat thing about slope-intercept form is that the intercept $b$ is the y coordinate of the line when it intersects with the y axis.
We can see this because $0m+b=b$.
This makes graphing easier.

Here's another example: Find an linear equation with slope of $3$ that passes through the point $(6,-1)$.
We can just write $y+1=3(x-6)$.
I just read that off; no math work required.
We *don't* need to convert that to slope-intercept form, but if we were asked to, or we didn't read the problem carefully, we would distribute and solve for $y$ giving $y=3x-19$.

**Sidebar:** Copying things is hard.
Up two this point on this *webpage*, I made two mathematical copying errors that I had to go back and fix.
Mr. West had a student who thought she was just terrible at math, and so didn't really apply herself.
She took a basic algebra class apathetically, and got around 25%.
Next time she worked hard, and went to office hours every week.
Mr. West noticed that her errors were mostly copying errors.
In his mind this was not a good thing, but she realized that her problem wasn't math.
Once she knew what was tripping her up she felt much better and her grade improved.
She got 81% on final he got a bit emotional about it.
With all the work she did, he really wanted her to pass.

More examples are always good. Take a look at this one.
Find a linear equation that goes through points $(5,1)$ and $(8,7)$.
It's a good idea to sketch this, but when I'm typing sketching is hard, so just imagine I did.
Using the formula for slope and point-slope form, we get $y-1=\frac{8-5}{7-1}(x-5)$.
If we wanted to simplify, we could rewrite this as $y-1=2(x-5)$
