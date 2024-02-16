# Disproving experimental evidence

The velocity addition formula derivable from the Lorentz transformation, used as corroboration for the theory in subsequent experiments (e.g. Fizeau), derives a contradictory term for

$\frac{\partial x}{\partial t}$

to the constancy of light postulate Einstein uses to derive the Lorentz transformation.

$x = ct \rightarrow \frac{x}{t} = c$.

Then $\frac{\partial x}{\partial t} = c$ assuming uniform motion.

However, this contradicts the velocity addition formula:

$\frac{\partial x}{\partial t} = \frac{\frac{\partial x'}{\partial t'} + v}{1 + \frac{v}{c^2}\frac{\partial x'}{\partial t'}}$

for pretty much all experimentally tested velocities $W = \frac{\partial x}{\partial t} \neq c$.

# Deriving the velocity addition formula

## Rigorously

Assume the Lorentz transformation. We have:

$\partial x = \frac{\partial x' + v \partial t'}{\sqrt{1 - \frac{v^2}{c^2}}}$

$\partial t = \frac{\partial t' + \frac{v \partial x'}{c^2}}{\sqrt{1 - \frac{v^2}{c^2}}}$

$\frac{\partial x}{\partial t} = \frac{\frac{\partial x' + v \partial t'}{\sqrt{1 - \frac{v^2}{c^2}}}}{\frac{\partial t' + \frac{v \partial x'}{c^2}}{\sqrt{1 - \frac{v^2}{c^2}}}} = \frac{\partial x' + v \partial t'}{\partial t' + \frac{v \partial x'}{c^2}} = \frac{\frac{1}{\partial t'}(\partial x' + v \partial t')}{\frac{1}{\partial t'}(\partial t' + \frac{v \partial x'}{c^2})} = \frac{\frac{\partial x'}{\partial t'} + v}{1 + \frac{v}{c^2}\frac{\partial x'}{\partial t'}}$

## Most rigorously

In case the above doesn't satisfy one's preferance of rigor, here is a derivation from absolute scratch.

### Definitions.

**(1) Speed of light constant *in vacuo*, reference frame, and spacetime.**

Let $c \coloneqq 299,792,458$ be the speed of light constant.

Reference frame $K^{(i)}$ (for any $i \in \mathbb{N}$) has time points $t^{(i)}  \in \mathbb{R}$ and corresponding spatial coordinates $x_{t^{(i)}}^{(i)} \in \mathbb{R}$.

$v^{(i, j)} \in \mathbb{R}$ is the velocity of $K^{(j)}$ measured by an observer on $K^{(i)}$.

**(2) Lorentz transformation.**

$\mathcal{X}(X, T, V) \coloneqq \frac{X - VT}{\sqrt{1 - \frac{V^2}{c^2}}}$

$\mathcal{T}(X, T, V) \coloneqq \frac{T - \frac{XV}{c^2}}{\sqrt{1 - \frac{V^2}{c^2}}}$

**(3) Velocity-addition formula.** 

$\mathcal{V}(V, W) \coloneqq \frac{W + V}{1 + \frac{V}{c^2}W}$.

**(4) Derivative.**

$\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} \coloneqq \lim\limits_{h^{(i)} \to 0} \frac{x_{t^{(i)} + h^{(i)}}^{(i)} - x_{t^{(i)}}^{(i)}}{h^{(i)}}$

**(5) Infinitesimal changes of time.** 

<!-- $h^{(i)}, h^{(j)}$ will denote infinitesimal time increments.  -->

$\Delta^j x_{t^{(i)}}^{(i)} \coloneqq \lim\limits_{h^{(j)} \to 0} x_{t^{(i)} + h^{(i)}}^{(i)} - x_{t^{(i)}}^{(i)}$

$\Delta^j t^{(i)} \coloneqq \lim\limits_{h^{(j)} \to 0} h^{(i)}$

### Assumptions

**(1) Lorentz transformation.**

The Lorentz transformation describes reference frame transformations in physical spacetime.

$x_{t^{(j)}}^{(j)} \coloneqq \mathcal{X}(x_{t^{(i)}}^{(i)}, t^{(i)}, v^{(i, j)})$

$t^{(j)} \coloneqq \mathcal{T}(x_{t^{(i)}}^{(i)}, t^{(i)}, v^{(i, j)})$

**(2) Mutual velocity perspective.**

$v^{(i, j)} \coloneqq -v^{(j, i)}$

This is assumed generally as well as in Einstein's second postulate ("the principle of relativity").

<!--
**(3) Einstein's first postulate: The speed of light *in vacuo* across all reference frames is constant.**

$x_{t^{(i)}}^{(i)} = c t^{(i)}$

**(4)** $\frac{\partial x}{\partial t} \neq c$.

As assumed in most experimentally tested setups, e.g., Fizeau.
-->

### Corollaries

**(1) Infinitesimal changes of time as partial derivative.** 

$\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} \coloneqq \frac{\Delta^i x_{t^{(i)}}^{(i)}}{\Delta^i t^{(i)}}$.

**Proof.**

$$
\begin{align}
  \frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} &= \lim\limits_{h^{(i)} \to 0} \frac{x_{t^{(i)} + h^{(i)}}^{(i)} - x_{t^{(i)}}^{(i)}}{h^{(i)}} \quad\quad \text{(Definition 4)} \\
  &= \frac{\lim\limits_{h^{(i)} \to 0} x_{t^{(i)} + h^{(i)}}^{(i)} - x_{t^{(i)}}^{(i)}}{\lim\limits_{h^{(i)} \to 0} h^{(i)}} \\
  &= \frac{\Delta^i x_{t^{(i)}}^{(i)}}{\Delta^i t^{(i)}} \quad\quad \text{(Definition 5)}
\end{align}
$$

**(2) Lorentz transformation of infinitesimal changes of time across reference frames.**

$\Delta^i x_{t^{(i)}}^{(i)} \coloneqq \mathcal{X}(\Delta^i x_{t^{(j)}}^{(j)}, \Delta^i t^{(j)}, -v^{(i, j)})$

$\Delta^i t^{(i)} \coloneqq \mathcal{T}(\Delta^i x_{t^{(j)}}^{(j)}, \Delta^i t^{(j)}, -v^{(i, j)})$

<!--
$\Delta x_{t^{(i)}}^{(i)} = \frac{\Delta x_{t^{(j)}}^{(j)} + v^{(i, j)} \Delta t^{(j)}}{\sqrt{1 - \frac{{v^{(i, j)}}^2}{c^2}}}$

$\Delta t^{(i)} = \frac{\Delta t^{(j)} + \frac{v^{(i, j)} \Delta x_{t^{(j)}}^{(j)}}{c^2}}{\sqrt{1 - \frac{{v^{(i, j)}}^2}{c^2}}}$
-->

**Proof.**

<!--
$\Delta x = \lim\limits_{h \to 0} x_{t + h} - x_{t} = \frac{x_{t' + h'}' + v (t' + h')}{\sqrt{1 - \frac{v^2}{c^2}}} - \frac{x_{t'}' + v t'}{\sqrt{1 - \frac{v^2}{c^2}}} = \frac{x_{t' + h'}' - x_{t'}' + v (t' + h') - v t'}{\sqrt{1 - \frac{v^2}{c^2}}} = \frac{x_{t' + h'}' - x_{t'}' + vh'}{\sqrt{1 - \frac{v^2}{c^2}}} = \frac{\Delta x' + v \Delta t'}{\sqrt{1 - \frac{v^2}{c^2}}}$
-->

### Theorems

**(1) Velocity-addition formula.** 

$\frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} \coloneqq \mathcal{V}(v^{(i, j)}, \frac{\partial x_{t^{(j)}}^{(j)}}{\partial t^{(j)}})$.

**Proof.**

$$
\begin{align}
  \frac{\partial x_{t^{(i)}}^{(i)}}{\partial t^{(i)}} &= \frac{\Delta^i x_{t^{(i)}}^{(i)}}{\Delta^i t^{(i)}} \quad\quad \text{(Corollary 1)}\\
  &=
\end{align}
$$

<!-- 
$\frac{\partial x}{\partial t} = \frac{\Delta x}{\Delta t} = \frac{\frac{\Delta x' + v \Delta t'}{\sqrt{1 - \frac{v^2}{c^2}}}}{\frac{\Delta t' + \frac{v \Delta x'}{c^2}}{\sqrt{1 - \frac{v^2}{c^2}}}} = \frac{\Delta x' + v \Delta t'}{\Delta t' + \frac{v \Delta x'}{c^2}} = \frac{\frac{1}{\Delta t'}(\Delta x' + v \Delta t')}{\frac{1}{\Delta t'}(\Delta t' + \frac{v \Delta x'}{c^2})} = \frac{\frac{\Delta x'}{\Delta t'} + v}{1 + \frac{v}{c^2}\frac{\Delta x'}{\Delta t'}} = \frac{\frac{\partial x'}{\partial t'} + v}{1 + \frac{v}{c^2}\frac{\partial x'}{\partial t'}}$ 
-->
