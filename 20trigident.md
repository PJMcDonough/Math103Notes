% Trigonometric identities
## Pythagorean identities
Recall $\sin^2\theta+\cos^2\theta=1$.
By deviding by 1, $\sin^2\theta$, and $\cos^2\theta$ respectively, we get the four identities we call the Pythagorean identities.

- $\sin^2\theta+\cos^2\theta=1$
- $1+\cot^2\theta=\csc^2\theta$ 
- $\tan^2\theta+1=\sec^2\theta$.

## Even-Odd identities
We have the odd-function trigonometric identities $-\sin\theta=\sin(-\theta)$ and $-\tan\theta=\tan(-\theta)$.
Additionally we have the even-function identity $\cos\theta=\cos(-\theta)$

#### Example
Show that $\tan\theta\cos\theta=\sin\theta$ where $\tan\theta$ is defined.
There are many ways to show this, like any other trig identity.

*Solution* 
$$\begin{align}
\tan\theta&=\frac{\sin\theta}{\cos\theta}\\
\tan\theta\cos\theta&=\frac{\sin\theta}{\cos\theta}\cos\theta\\
\tan\theta\cos\theta&=\sin\theta\\
\end{align}$$

#### Example
Show that $\frac{\sec^2\theta-1}{\sec^2\theta}=\sin^2\theta$ where defined.
One strategy here is to convert everything to sines and cosines. 

*Solution 1:* The final equality follows because of the sine-cosine trigonometric identity.
$$\frac{\sec^2-1}{\sec^2}= \frac{\sec^2}{\sec^2} -\frac{1}{\sec^2} = 1-\cos^2\theta = \sin^2\theta$$

*Solution 2:* First note that since $1+\tan^2=\sec^2$ we have that $\sec^2-1=\tan^2$.
$$\begin{align}
\frac{\sec^2\theta-1}{\sec^2\theta}
&=\frac{\tan^2\theta}{\sec^2\theta}\\
&=\tan^2\theta\cos^2\theta\\
&=\tan^2\theta\cos^2\theta\\
&=\frac{\sin^2\theta}{\cos^2\theta}\cos^2\theta\\
&=\sin^2\theta\\
\end{align}$$

#### Example
The first step of each solution follows by the Pythagorean identities.

*Solution 1:*
$$\begin{align}
&(1-\cos^2x)(1+\cot^2x)\\
&=\sin^2x\csc^2x\\
&=\frac{\sin^2x}{\sin^2x}\\
&=1
\end{align}$$

*Solution 2:*
$$\begin{align}
&(1-\cos^2x)(1+\cot^2x)\\
&=\sin^2x(1+\frac{\cos^2x}{\sin^2x})\\
&=\sin^2x+\sin^2x\frac{\cos^2x}{\sin^2x}\\
&=\sin^2x+\cos^2x\\
&=1
\end{align}$$

#### Example
To solve $\cos^2\theta-\cos^2\theta=0$, let $c=\cos^2\theta$, we resulting in a simple quadratic $c^2-x-2=0$.
So $(c-2)(c+1)=0$.
Because the output of the $\cos$ function can never be $2$, we know $cos\theta=-1$.
So the solutions are, for integer $k$, $\theta=2\pi k+\pi$.

This will likely be on the test

#### Example
We show 
$$\begin{align}
\frac{\cos\theta}{1+\sin\theta}&=\frac{1-\sin\theta}{\cos\theta}
\cos^2\theta&=(1-\sin\theta)(1+\sin\theta)
\cos^2\theta&=1-\sin^2\theta
\sin^2\theta+\cos^2\theta=1
\end{align}$$

## Sum and Difference Identities (§ 7.2)
The proof of these is on page 571 of the PDF version of the proof.
$$\begin{align}
\cos(\alpha+\beta)&=\cos\alpha\cos\beta-\sin\alpha\sin\beta\\
\cos(\alpha-\beta)&=\cos\alpha\cos\beta+\sin\alpha\sin\beta\\
\sin(\alpha+\beta)&=\sin\alpha\cos\beta+\cos\alpha\sin\beta\\
\sin(\alpha-\beta)&=\sin\alpha\cos\beta-\cos\alpha\sin\beta\\
\end{align}$$

#### Example

To calculate $\cos(105º)$, we calculate $\cos(60+45)$ using the unit circle and the above identity.
This gives us $\frac{1}{2}\frac{\sqrt 2}{2} - \frac{\sqrt 3}{2}\frac{\sqrt 2}{2}=\frac 14(\sqrt 2 -\sqrt 6)$.
Similarly we could compute $\cos(150º-45º)$ or $\cos(135º-30º)$.

Similarly, we could compute $\sin(15º)=\sin(45º-30º)$.


## Double Angle Identities
It turns out that $\cos\theta=\sin(\frac\pi 2-\theta)$ because, by the sum identity, $\sin(\frac\pi 2-\theta)=\sin\frac\pi 2\cos\theta-\cos\frac\pi 2\sin\theta$, which cancels and gives us the identity we want.
Similarly $\sin\theta=\cos(\frac\pi 2-\theta)$.

By the sum identity for $\sin$ and some algebra, $\sin 2\theta=\sin(\theta+\theta)=2\sin\theta\cos\theta$.
The sum identity for $\cos$ gives $\cos 2\theta=\cos^2\theta-\sin^2\theta$, and the Pythagorean identity gives the alternate forms $2\cos^2\theta-1$ and $1-2\sin^2\theta$.

## Half Angle Identities
