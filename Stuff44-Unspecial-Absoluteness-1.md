# The Unspecial Absoluteness of Cellphone Communication

All 3 men start at the same position when Man 1 sends the text. Man 2 is driving.

Man 3 <⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯ $D$ ⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯ Cell tower</br>
⎯⎯⎯⎯ $B$ ⎯⎯⎯> Man 2 <⎯⎯⎯⎯⎯ $C$ ⎯⎯⎯⎯⎯⎯ </br>
Man 1 &nbsp;⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯ $A$ ⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯>

The cellphone signal travels at the speed of light $V(A) = V(C) = V(D) = c$.

Man 2 is driving at velocity $V(B) = v$.

Let $x = X(A) + X(D)$ and $x' = X(A) + X(C)$.

Let $t = T(A) + T(D)$ and $t' = T(A) + T(C)$.

Given $x, t$, the goal is to find $x', t'$. 

We obtain from this, using only the absolute times, distances, and speeds of this absolute physically-possible reference frame, the Special Relativity equations of Einstein and Lorentz.

### Proof

Let us derive in the analog fashion to Einstein.

First, to obtain his 2nd postulate equations without assuming constancy of light *in vacuo*:

$x = X(A) + X(D) = V(A)T(A) + V(D)T(D) = cT(A) + cT(D) = c(T(A) + T(D)) = ct$

and

$x = X(A) + X(C) = V(A)T(A) + V(C)T(C) = cT(A) + cT(C) = c(T(A) + T(C)) = ct'$.

We thus have $x = ct$ and $x' = ct'$.

This can then be rewritten

$x - ct = 0$ </br>
$x' - ct' = 0$

Necessitating that

$x - ct = \lambda(x' - ct')$

for any constant $\lambda$.

In this absolute physical space, we may reasonably assume isotropy, that is, "the laws of physics to Man 1's left are the same as the laws of physics to Man 1's right." Therefore, if we flip the diagram at the start of this on its vertical-mirror axis, so that the cell tower is to the left of the men and Man 2 is driving to the left, 

Cell tower ⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯ $\hat{D}$ ⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯> Man 3</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⎯⎯⎯⎯⎯ $\hat{C}$ ⎯⎯⎯⎯⎯⎯> Man 2 <⎯⎯⎯⎯ $\hat{B}$ ⎯⎯⎯ </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯ $\hat{A}$ ⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯ &nbsp; Man 1

we get the same result but in the additive:

$x + ct = \mu(x' + ct')$,

where $\mu$ is any constant.

Adding these last 2 equations and allowing

$a = \frac{\lambda + \mu}{2}$

$b = \frac{\lambda - \mu}{2}$,

we get

$x' = ax - bct$

$ct' = act - bx$.

(To be continued)

---

Never mind, this is impossible. The axiom $x' = x - vt'$ suffices to disprove Einstein relativity.

### Disproving

Given this diagram (and as assumed in many works actually), we see that $x' = x - vt'$.

$x' = x - vt' = ct'$
$\rightarrow t' = \frac{x}{c + v}$
$\rightarrow x' = \frac{cx}{c + v}$

However, if by the Einstein result, $x' = \frac{x - vt}{\sqrt{1 - \frac{v^2}{c^2}}}$, we get

$\frac{cx}{c + v} = \frac{x - vt}{\sqrt{1 - \frac{v^2}{c^2}}}$.

Squaring both sides, we get:

$\frac{c^2x^2}{c^2 + 2cv + v^2} = \frac{x^2 - 2xvt + v^2t^2}{1 - \frac{v^2}{c^2}}$

Multiplying both sides by the RHS denominator:

$\frac{c^2x^2 - v^2x^2}{c^2 + 2cv + v^2} = x^2 - 2xvt + v^2t^2$

$\rightarrow \frac{x^2(c+v)(c-v)}{(v+c)(v+c)} = x^2 - 2xvt + v^2t^2$

$\rightarrow x^2(c-v) = (x-vt)^2(c+v)

$\rightarrow 2x^2 - 2xt(v+c) + (v^2t^2+vt^2c) = 0

Solving for x, via quadratic equation:

$x = \frac{2t(v+c) \pm \sqrt{(2t(v+c))^2 - (8v^2t^2-8vt^2c)}}{4}$

However, since this value must also equal $ct$ owing to $x = ct$ a core assumption of special relativity, we have

$\frac{2t(v+c) \pm \sqrt{(2t(v+c))^2 - (8v^2t^2-8vt^2c)}}{4} = ct$.

Solving for $v$ ( as can be verified by a Wolfram Alpha calculator for example), we get

$v = c$.

Therefore, the axiom $x' = x - vt'$ suffices to disprove Einstein relativity for any $v \neq c$.
