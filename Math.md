**Physics:**

$\mathbf{P}((y, h^{(n)}) \sim \mathrm{R}^n(x, h^{(0)}) \vert y)$

where $\mathrm{R}$ is a recursive dynamics model and a random variable, $h$ is the hidden state (the non-observable universe) at any time point up to some conceivable horizon (in order to make $\mathrm{R}$ defined), composed $n$ times. $y$ is the observable universe.

**Causal reasoning:**

$\mathbf{P}((y, h^{(n)}) \sim \mathrm{R}^n(x, h^{(0)}) \vert y, \mathrm{R})$

$x$ is the cause, $y$ is the effect, under some dynamics system $\mathrm{R}$.

**Axiomatic math:**

$\mathbf{P}((y, h^{(n)}) \sim \mathrm{R}^n(x, h^{(0)}) \vert h^{(n)}, n \in \mathcal{N}, \mathrm{R}, x, h^{(0)})$

where $\mathrm{R}$ is the rules of math. $y$ is a theorem or theorem set, $x$ is an axiom or axiom set. $\mathrm{R}$ is Turing-complete due its rewritable memory state $h$. Ordinarily, $\mathrm{R}$'s rules are deterministic, a side effect being that the probability of a theorem $y$ is also deterministic, $1$ or $0$. 

Non-deterministic math, e.g. an "Occam's razor" "theorem", we will refer to as epistemological math, rooted in belief.

**Belief:**

$\mathbf{P}(B \vert E) = \frac{\mathbf{P}(E \vert B)\mathbf{P}(B)}{\mathbf{P}(E)}$

Physics, causality, and math have utility and correlative predictiveness to our memories and senses, but beyond observing what's in front of us, these established beliefs are symbolic references within the brain, and the referents are memories, observations, and beliefs. As René Descartes derived with "*cogito, ergo sum*": "I doubt, therefore I am," we can further deduce inwardly. If I may: 

"I observe, therefore I am observing, therefore I am. 

I observe many referents to my observation, including memories, feelings, and viscera. There's also belief. I believe X, Y, Z. I justify X, Y, Z by reasons, another element of belief, X', Y', Z'."

Each step is deeper into the psyche.

Physics, causality, and math are beliefs. 

Philosophy includes these meta-beliefs as well as others.

Perhaps, philosophically speaking, philosophy is the random variable set encompassing all random variables:

**Philosophy:**

$\langle B \vert (B \in \Omega) \sim \mathbf{P}(B \in \Omega) \rangle$,

though to define it as such would contradict that definition since a random variable set encompassing all random variables would have to be contained within itself, making the definition self-referentially undefined. This would be analogous to defining a word in a dictionary by some other words plus itself. Perhaps contextually useful to make some inferences about its meaning based on the other words but ultimately meaningless since any reference to itself within the definition would point back to a non-converging turtles-all-the-way-down recursion of itself. Furthermore, something about Gödel's incompleteness theorem.

Random variables may be also expressed as random variables relating other random variables, such as $\mathbf{P}(x > y)$.

For the sake of deduction to derive axioms to theorems, they may also define implications:

**Theorem-derivation steps:**

$\mathbf{P}(x > z \vert x > y, y > z) = 1$

Transitivity of the greater-than inequality for example, using conditionals to specify the valid axioms or theorems $(x > y, y > z)$ that would imply the prior $x > z$.

They may even be cross-referential:

$\mathbf{P}(w > z \vert w > x, \mathbf{P}(x > z \vert x > y, y > z) = 1) = 1$,

Treating each other as random variables.

Could such an ontology form the basis of a data structure to represent $R, h^{(0)}$ in axiomatic math? Using deterministic conditionals with probabilities $1$ as proof steps and a defined set of initial conditionals and beliefs (random variables), it seems so.

Furthermore, it can generalize to a new type of math where proof steps can be epistemological, non-deterministic beliefs applied to other beliefs to quantify a looser proof. This is standardly done in physical sciences with the use of p-values, and we draw a formal unambiguous connection between that to AI and reasoning generally, keeping these notations and formalities that tie together the larger sciences.

# Formally

**Definition 1.** Axiom.

$($ Axiom  $A ) \coloneqq (\exists A)$.

**Definition 2.** Definition.

$($ Definition $A \coloneqq B) \coloneqq (\exists (A \coloneqq B))$. 

**Definition 3.** Equivalence.

$($ Equivalence $A = B) \coloneqq (A \rightarrow_n B, B \rightarrow_m A, n, m \in \mathbb{N})$, where $n, m$ are deductive steps, meaning $n-1, m-1$ statements must be deduced between $A$ and $B$ and $B$ and $A$ respectively. 

Instantaneous equivalence $(A \coloneqq B) \coloneqq (A \rightarrow_1 B, B \rightarrow_1 A)$.

For example, $(A \rightarrow_2 C) \coloneqq (A \rightarrow_1 B \rightarrow_1 C)$ for some mandatory intermediary $B$.

**Definition 4.** Implication.

$($ Implication $A \rightarrow_1 B) \coloneqq (\exists A \rightarrow_1 \exists B)$.

**Definition 5.** Proof.

$($ Deduction/theorem/proof $A \rightarrow B) \coloneqq (A \rightarrow_n B) \coloneqq (\exists A \rightarrow_n \exists B)$ for some $n \in \mathbb{N}$.

**Definition 6.** Hypotheticals.

$($ Sets of anything defined... $(A, B, ...))$ $\coloneqq ((A, B, ...))$

denoted by parentheticals. 

$A$ is a single hypothetical.

**Definition 7.** Sets of existence.

$(\langle X_1, X_2, ... \rangle) \coloneqq (\exists X_1, X_2, ...)$

hypotheticals whose elements exist.

**Definition 8.** Nothing.

The empty existence set $\emptyset \coloneqq \langle \rangle$.

**Definition 9.** Nothing equivalents.

$\emptyset = \emptyset_K \forall K \subseteq \mathbb{N}$.

**Definition 10.** The universe.

$\Omega^{(0)} \coloneqq \emptyset$.

$\Omega^{(n)} \coloneqq (( \emptyset_K \vert K \subseteq \mathbb{N}; \Omega^{(0)} \rightarrow_n \emptyset_K ), \rightarrow_n)$.

$\Omega \coloneqq (\Omega^{(0)}, \Omega^{(n)})$.

$n \in \mathbb{N}$.

**Axiom 1.** Existence exists. $\langle\langle X_1, X_2, ... \rangle\rangle \coloneqq (\exists X_1, X_2, ...)$.

**Axiom 2.** Cause exists. $\exists \rightarrow$.

**Theorem 1.** Nothing exists. $\exists \emptyset$.

**Proof.**

$(\langle\langle\rangle\rangle \coloneqq ())  \rightarrow (\exists \langle\rangle)$. (Axiom 1)

$((\emptyset \coloneqq \langle \rangle), (\exists \langle\rangle)) \rightarrow (\exists \emptyset)$. (Definition 8) $\square$

**Theorem 2.** All nothings exist. $\exists \emptyset_K \vert K \subseteq \mathbb{N}$.

**Proof.**

$((\exists \emptyset), (\emptyset = \emptyset_K \forall K \subseteq \mathbb{N})) \rightarrow (\exists \emptyset_K \vert K \subseteq \mathbb{N})$. (Theorem 1, Definition 9) $\square$

**Theorem 3.** The universe exists. $\exists \Omega$.

**Proof.**

$((\exists \emptyset), (\Omega^{(0)} \coloneqq \emptyset)) \rightarrow (\exists \Omega^{(0)})$. (Theorem 1, Definition 10)

$((\exists \emptyset_K \vert K \subseteq \mathbb{N}), (\exists \rightarrow_n)) \rightarrow \langle\langle \emptyset_K \vert K \subseteq \mathbb{N}; \Omega^{(0)} \rightarrow_n \emptyset_K \rangle, \rightarrow_n \rangle$. (Theorem 2, Axiom 2, Axiom 1)

$\langle\langle \emptyset_K \vert K \subseteq \mathbb{N}; \Omega^{(0)} \rightarrow_n \emptyset_K \rangle, \rightarrow_n \rangle \rightarrow (\exists \Omega^{(n)})$. (Definition 10)

$((\exists \Omega^{(0)}), (\exists \Omega^{(n)})) \rightarrow (\exists \Omega)$. (Definition 10) $\square$

**Theorem 4.** The universe $\Omega$ is at least a non-halting or cyclical Turing machine. 

**Proof.**

Construct a tape of binary zeroes and ones $\emptyset_{0,i}, \emptyset_{1,i}$ where $i$ denotes the position on the tape. 

$\emptyset \rightarrow_1 \emptyset_{\tau,i} \forall i \in \mathbb{N}$.

At each time step modify one bit $\emptyset_{\tau,i} \rightarrow \emptyset_{-\tau + 1,i}$. Now, complete the equivalence cycle of Definition 9 by the following limit:

$\lim_{n\rightarrow\infty} \emptyset_{\tau,i} \rightarrow_n \emptyset$. $\square$

**Theorem 5.** An almost Turing-equivalent universe can arise from nothing, assuming just the properties of deduction: existence of existence and cause.

**Proof.**

By Theorem 4. $\square$
