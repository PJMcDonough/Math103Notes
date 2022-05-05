% Law of Sines and Law of Cosines (§§ 8.1--8.2)

# Law of Sines

Consider a triangle with Angles $A$, $B$, and $C$.
We call the angles opposite a given side the lowercase version of that letter.
In other words, the opposite angles are, respectively, $a$, $b$, and $c$.

Recall that the area of a triangle is the base times the hight divided by 2.
You can prove this by bisecting an arbitrary parallelogram.

In this case, we will take $c$ to be the base.
The height can be found by drawing a line through point $C$ perpendicular to $c$.
We can then se that the height $h=cb\sin A$.
This gives the area $\frac 12 cb\sin A$.
The same argument with different variable names gives area as $\frac 12 ca\sin B=\frac 12 ba\sin C$.

Dividing each of the expressions for the areas by $\frac 12 abc$ gives the law of sines:

$$\frac{\sin A}{a}=\frac{\sin B}{b}=\frac{\sin C}{c}$$

### Example
Consider a triangle with $a=10$, $A=50º$, and $C=50º$. Solve the triangle (i.e., find all unknowns).

**Solution** $B=180º-50º-30º=100º$. 
By the law of sines, and some algebra 
$$c=\frac{\sin C}{\sin A}a=\frac{\sin 30º}{\sin 50º}10$$ 
$$b=\frac{\sin B}{\sin A}a=\frac{\sin 100º}{\sin 50º}10$$

This comes out to about 6.53 and 12.86 respectively.

### Example
Consider a triangle with $C=85º$, $c=12$, and $b=9$. Solve the triangle (i.e., find all unknowns).

**Solution:** Left as an exercise for the reader.

### Example
Consider a triangle with $A=35º$, $a=6$, and $b=8$. Solve the triangle (i.e., find all unknowns).

**Solution:**
$$\sin B = \frac{b}{a} \sin A= \frac 86\sin 35º$
Taking the $B=\arcsin\sin B$ is then aproximately $49.89$, but we also need to consider the posibility $B = 180º-\arcsin\sin B$, giving the solution of aproximately $130.11$.
Finding the remaining angles of both sets of solutions is left as an exercise for the reader.

## Note

If you have to take an $\arcsin$, then you need to consider all possible values, but note that some values will be inconstant with things we know about triangles, usually leaving just one or two solutions.

# Law of Cosines 
The law of cosines is

$$ a^2 = b^2 +c^2 - 2bc\cos A $$

There are a total of 6 forms of this which you can get by substitution, but up to commutativity of addition and multiplication, there are only 3.

Note that the Pythagorean theorem is a special case of this.

### Example
Consider a triangle with $a=20$, $b=18$, and $b=25$. Solve the triangle (i.e., find all unknowns).

**Solution** Solving the law of cosines gives

$$ A = \arcsin\frac {b^2+c^2-a^2}{2bc}$$

We can do the same thing with each of the other angles.
After that, we can add up all three angles and make sure we get 180º.


