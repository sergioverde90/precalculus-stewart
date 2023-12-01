### 61. DISCOVER ■ PROVE: Finding the Terminal Point for $\dfrac{\pi}{6}$

Suppose the terminal point determied by $t = \dfrac{\pi}{6}$ is $P(x,y)$, the point $Qx$ and $R$ are as shown in the figure. Why are the distances $PQ$ and $PR$ the same? Use this fact, together with the Distance formula to show that the coordinates of $P$ satisfy the equation $2y = \sqrt{x^2 + (y-1)^2}$. Simplify this
equation using the fact that $x^2 + y^2 = 1$. Solve the simplified equation to find $P(x,y)$. 

#### a) Why are the distances $PQ$ and $PR$ the same?
The distances are the same becase they form the same angle, so PR and PQ form a congruent triangle. Congruent triangles are explained in the Appendix A: Geometry review.

We have $P(x,y)$ and $R(0,1)$ so, using the distance formula, we have:

$$
\begin{equation}
\begin{aligned}
& Distance(PR) = \sqrt{(x-0)^2 + (y-1)^2} \\ 
& = \sqrt{x^2 + (y-1)^2}
\end{aligned}
\end{equation}
$$

Same for $Q(x, -y)$:

$$
\begin{equation}
\begin{aligned}
& Distance(PQ) = \sqrt{(x-x)^2 + (y-(-y))^2} \\ 
&  = \sqrt{0^2 + (2y)^2} \\
& = \sqrt{(2y)^2} \\ 
& = 2y
\end{aligned}
\end{equation}
$$ 

This is where the equation comes from. Now, in the section b), the equation is solved to find a the $y$ that satisfies the equation.

#### b) show that the coordinates of $P$ satisfy the equation $2y = \sqrt{x^2 + (y-1)^2}$. Solve the simplified equation to find $P(x,y)$. 

$$
\begin{equation}
\begin{aligned}
& 2y = \sqrt{x^2 + (y-1)^2} \\
& 4y^2 = x^2 + y^2 +2y -1  \\
& 4y^2 = 1 -2y -1 \\
& 4y^2 = 2-2y \\
& 4y^2 + 2y -2 = 0 \\
& 2y^2 + y -1 = 0 \\
\end{aligned}
\end{equation}
$$

Solving the quadratic equation we have $y=\dfrac{1}{2}$ or $y=-1$. Take the positive solution because $y$ is in the $I$ Quadrant. Now we know the $y$ value in $P(x, \dfrac{1}{2})$, so we can calculate $x$ using the unit circle formula:

$$
\begin{equation}
\begin{align*}
x^2 + y^2 = 1 \\
x^2 + (\dfrac{1}{2})^2 = 1 \\
x^2 = 1 - \dfrac{1}{4} \\
x^2 = \dfrac{3}{4} \\
x = \dfrac{\sqrt{3}}{2}
\end{align*}
\end{equation}
$$

So the terminal point for $\dfrac{\pi}{6}$ is $P(\dfrac{\sqrt{3}}{2}, \dfrac{1}{2})$.