# Observation

**Theorem 1:** Observation exists.

**Proof:** 

"I observe."  $\square$

---

Whatever this function is define it as $o$. Let's give it infinite equivalents, again by definition:

**Definition 1**: $\mathrm{I_1} = \mathrm{I_2} = \cdots = o$ is observation.

This "set", or grouping, may be considered distinct. We will define this interpretation as Qualia.

**Definition 2**: $\mathbb{Q} = \mathrm{I}_\mathbb{N}$.

where $\mathbb{Q}$ is Qualia, $\mathbb{N}$ is qualia. $\mathbb{N}$ are analogous to but not necessarily the natural numbers, and may not be infinite. Subsets will also be referred to as qualia .

---

**Theorem 2:** $\exists \mathrm{I_i}, \forall i \in \mathbb{N}$. Each of these variables exists.

**Proof:** 

$o$ is defined as observation. By Theorem 1, $\exists o$. 

By definition 1, $\mathrm{I_1} = \mathrm{I_2} = \cdots = o$.

By equivalence, $\exists \mathrm{I}_{i \in \mathbb{N}}$. $\square$ 

---

**Axiom 1a:** This is the function of observation.

$\mathrm{I_i}(\mathrm{I_j}) = j$

$\mathrm{I_i}(\mathrm{I}_I^n(\mathrm{I_j})) = I, j$

where $\mathrm{I}_I^n$ represents composability of $n \in \mathbb{Z}$ observers; $I \subseteq \mathbb{N}; |I| = n$; $I, j \subseteq \mathbb{N}; |I, j| \leq n + 1$.

**1b:** Disambiguated uniqueness of qualia.

$\mathrm{I_i}(\mathrm{I_j}) = \mathrm{I_i}(\mathrm{I_j})$

$\mathrm{I_i}(\mathrm{I}_I^n(\mathrm{I_j})) = \mathrm{I_i}(\mathrm{I}_I^n(\mathrm{I_j}))$

---

$\mathrm{I_i}$ are not substitutable in the domain of the function that defines their equivalence.

**Uniqueness:** Each observer, at any one observation, can only observe one set of defined qualia, disambiguated, uniquely:

By Axiom 1a:

$o(o) = j = o(o)$,

$o(o) = o(I_i) = i \neq j = o(I_j) = o(o)$.

would ambiguate the defined qualia of $o$, as being either $i$ or $j$.

Axiom 1b excludes the second relation and disambiguates the qualia-identity of the observed observers, uniquely.

$o(o) = o(I_i) = i$.

**Interpretation:**

One way of interpreting is from the lens of recurrent functions hyperparameterized by real-time changing parameters, such as in an LSTM, a function with memory that is used in deep learning, potentially deployed for training in real-time, that is, with each step in the recurrence, updating. Define an LSTM $f_\theta$ parameterized by $\theta$. $\theta \subset \mathbb{N}$ may have qualia, but $f_\theta \notin \mathbb{Q}$ is not a Qualia by definition.

Nevertheless, as $\theta$ changes, in each recurrent step, so do the recurrent outputs/behaviors of the LSTM's function. This makes Qualia like a hyperparmeterized recurrent function; except its subscripts are defined as something natural other than the natural numbers.

Specifically, identifiable traits of equivalency definitions.

In proof, definition is the base case of every deductive step. Axioms are defined. Implications are defined. These equivalencies are distinct but treated equal and therefore deductive steps may be taken.

That process, underlying the epistemelogical assumption of all deduction, is to regard equivalents as functions whose domains distinguish the equivalents.

# Proof of $\Omega$

We will now premise on two possibilities: (1) the existence of causality and (2) no assumption about the existence of causality. 

### (1) The existence of causality:
#

**Definition 3**: Causality.

$\exists \mathrm{R}$ s.t. 

$\mathbf{P}((y, h^{(n)}) \sim \mathrm{R}^n(x, h^{(1)}) \vert y) \neq \mathrm{U}$.

$\mathrm{U}$ is the Uniform distribution.

$n \in \mathbb {N}$, and $o(x) \neq o(y)$, given the same Qualia for $o$ and different qualia for $x, y$, $\forall o \in \mathbb{Q}$.

$h$ is a theoretical memory and global context window to not assume fully-observed Markovian dynamics.

**Interpretations:**

The conditional may be interpreted as saying $\exists y$.

$x$ is the cause, $y$ is the effect, under some dynamics system $\mathrm{R}$.

As a consequence,

$\exists \sim$,

where a "sampler" exists, or if the dynamics system is deterministic, a "decider."

Under causality, this and $\mathrm{R}$ and $\hat{\mathrm{R}} \sim \mathrm{R}$ will also need causes attributed to it.

One last interpretation: 

**Definition 4**: $\Omega \sim \mathrm{R}$ is a physics model.

In this case, $y$ is the observable universe, the qualia that informs us of its existence.

---

**Theorem 3**: $\exists \Omega \sim \mathrm{R}$ $\rightarrow$

$\mathbf{P}((o, h^{(n)}) \sim \Omega^n(x, h^{(1)})) \neq \mathrm{U}$

**Proof:**

Observation $o$ exists. Under causality, there must be a non-uniform distribution for its cause or dynamics system $\mathrm{R}$ is undefined. $\square$

---

**Corrillary 1:** Observation suffices to represent the natural numbers, denoted qualia, above, $\mathbb{N}$.

**Proof**:

1. $\mathrm{I_2}(\mathrm{I_1})$
2. $\mathrm{I_3}(\mathrm{I_2}(\mathrm{I_1}))$
3. $\mathrm{I_4}(\mathrm{I_3}(\mathrm{I_2}(\mathrm{I_1})))$

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $\vdots$  

$\square$

**Corrillary 2:** Observation suffices to represent the tape of a Turing machine.

**Proof**: $\mathbb{N}$ suffices to represent binary integers. $\square$

**Theorem 4**: Observation and causality give us a Turing-complete machine.

**Proof:**

Since $h$ is a theoretical memory, this gives us a Turing-complete machine. Let

$\mathbf{P}((o, \hat{h}^{(\hat{n})}) \sim \hat{\mathrm{R}}^\hat{n}(\hat{x}, \hat{h}^{(1)})) = 1$

for some samples $\hat{n} \in \mathbb{N}; \hat{h}^{(1)}, \hat{x} \subseteq \mathbb{N}$ via observation e.g. $\mathrm{I_2}(\mathrm{I_1})$. Then $\hat{\mathrm{R}}$ is our Turing machine.

In fact, $\hat{\mathrm{R}}$ is a non-deterministic Turing machine if we do not constrain the probability to 1.

$\square$

**Intuition:** $\hat{\mathrm{R}}$ is a function that makes qualia changeable, from moment to moment. A rewritable tape, in computer theory terms.

---

In logic, there are two justifications for the truth-value of $y$, axiom or implication.

1. Assume $y$
2. $x \rightarrow y$

given the existence of $x$.

The simplest implication is "by definition":

$y = x$.

Other implications rely on earlier axioms and theorems that reduce to "by definition" as well. All logic and math follow this process. Sciences rely on evidence, observations, memory, and pre-established beliefs, to form hypotheses and theories from evidence-based axioms.

The implication operation, denoted $\rightarrow$, can be symbolically represented by and representative of the dynamics model described in causality.

$x \rightarrow y : P(\Omega^n(x) = y) = 1$.

for some number of derivation steps $n$.

Given the fact, under causality, 

$P(\Omega^n(x) = o) = 1$,

> For clarity, we have written it like this, but the exact would be $P(\Omega^{(n)} = o) = 1$ given $\Omega^{(n)} \sim \Omega^n(x)$, by the interim-probabilistic definition.

where $o$ is observation, we have two possible derivations:

1. Assume $o$.
2. $x \rightarrow o$

Causality, unlike logic, comes with the constraint that axiomatic causes do not count. $n > 0$ and $o(y) \neq o(x)$, given the same Qualia for $o$ and different qualia for $x, y$. Therefore 1 is not an option. We know $o$, but we don't assume it. The difference in axiomatic math is that $o$ is proven, not axiomatized. 

In other words, causally explaining $o$, the present-moment observation, with $o$, is a contradiction to the causal constraint that $o(x) \neq o(y)$.

$o(x) = o(o) = j = o(o) = o(y)$,

for some $j \in \mathbb{N}$.

One might argue, couldn't $o = I_i$ on the LHS s.t. $i \neq j$, by definition of equivalence? The argument goes like this:

$o(x) = o(I_i) = i \neq j = o(I_j) = o(o)$.

However, not by Axiom 1b.

Intuitively, only one $o \in \mathbb{Q}$ exists at any one moment as itself. Multiple observers can exist concurrently.

**Theorem 5:**

Observation cannot causally explain itself, under the defined causality assumption.

**Proof:**

Assume $x = o$ and $y = o$.

$o(x) = o(o) = j = o(o) = o(y)$,

contradicting $o(x) \neq o(y)$ in causality's definition. $\square$

---

**Theorem 6:** Causality gives us a cyclical convergence

$\lim_{n \to +\infty} \Omega^{(n)} = \Omega^{(0)}$

TBA

This can be expressed geometrically as an arrow of time on a radius-expanding circle:

[Circle-arrow, three arrows point out of it expanding the circle.]

Or algebraically, perhaps as such:

$n = \sin(\frac{\pi t}{t+1})$.

where $t$ is our time dimension.

Self-creation is a novel theory for why the universe demonstrates this phenomenon, expanding spacetime and curvature as equivalents to causality.

[Three circles labled $x, y, z$ and the circle-arrow of time labeled $t$. With a dot on the $z$: "You are here." $x, y, z$ are converged self-creations.]

**Contextualization**

**Proof** (outline)

1. Define causality as a random variable.
2. It's either cyclical or "turtles all the way down."
3. If it's turtles all the way down, then the cause of turtles all the way down is turtles all the way down, making it nevertheless cyclical ("The cause of $\infty$ is $\infty$").

**Proof**

**Theorem 6:** Causality gives us a teleological objective

**Theorem 7:** Causality implies limited resources

---

Scratch all that. Starting over.

# Begin

## Part 1

$A, B, C$ are anything defined... 

**Definition 1.** Axiom.

$($ Axiom  $A ) \coloneqq (\exists A)$.

**Definition 2.** Definition.

$($ Definition $A \coloneqq B) \coloneqq (\exists (A \coloneqq B))$. 

**Definition 3.** Equivalence.

$($ Equivalence $A = B) \coloneqq (A \rightarrow_n B, B \rightarrow_m A, n, m \in \mathbb{N})$, where $n, m$ are deductive steps, meaning $n, m$ statements must be deduced between $A$ and $B$ and $B$ and $A$ respectively. 

Instantaneous equivalence $(A \coloneqq B) \coloneqq (A \rightarrow_1 B, B \rightarrow_1 A)$.

For example, $(A \rightarrow_2 C) \coloneqq (A \rightarrow_1 B \rightarrow_1 C)$ for some mandatory intermediary $B$.

**Definition 4.** Implication.

$($ Implication $A \rightarrow_1 B) \coloneqq (\exists A \rightarrow_1 \exists B)$.

**Definition 5.** Proof.

$($ Deduction/theorem/proof $A \rightarrow B) \coloneqq (A \rightarrow_n B) \coloneqq (\exists A \rightarrow_n \exists B)$ for some $n \in \mathbb{N}$.

---

Note 1: Traditional equivalence is fully generalized to by this more-general definition of equivalence, meaning any previous use of equivalence may, to the best of our ability to tell, be substituted with this new one.

Note 2: Likewise, any implication $A \rightarrow B$ can be substituted with $A \rightarrow_n B$ for any $n \in \mathbb{N}$ w.l.o.g..

Note 3: Deductive steps (time) $\rightarrow$ and existence $\exists$ perhaps stem from our own intuitions about the mechanistic functions of the world. Where did time come from? What caused existence? These are questions we will try to answer, at the root of this mathematics and the, perhaps equivalent, traditional. 

## Part 2

**Definition 3 (Modified).** $0 \leq \mathbf{P}(A \rightarrow_n B) \leq 1$  can be non-deterministic.

---

"I observe."

Whatever this function is, call it $\mathrm{I}$.

**Definition 6.** Observer and observation.

$($ Observer $) \coloneqq (\mathrm{I}), ($ Observation $) \coloneqq (\mathrm{I}(\cdot))$.

**Theorem 1.** $\exists \mathrm{I}$.

**Proof.**

"I observe." $\square$

**Axiom 1.** Existence is defined by observation.

$(\exists x) \coloneqq (\exists \mathrm{I}(x))$.

**Definition 7.** Natural numbers.

$($ Natural numbers $) \coloneqq (\mathbb{N})$

are not necessarily *the* natural numbers or immediately infinite in one deductive step.

**Definition 8.** Nothing and its equivalents.

$($ Nothing $\emptyset) \coloneqq (\emptyset_K) \vert \forall K \subseteq \mathbb{N}$.

Call this set $(\emptyset^\mathbb{N}) \coloneqq \langle \emptyset_K \vert K \subseteq \mathbb{N} \rangle$.

**Theorem 2.** $\exists \mathrm{I}(\emptyset)$ and $\exists \mathrm{I}(\mathrm{I})$ and $\exists \mathrm{I}(\hat{\emptyset}) \forall \hat{\emptyset} \in \emptyset^\mathbb{N}$.

**Proof.**

By Theorem 1, Axiom 1, and Definition 8. $\square$

Note: "Nothing" existing is technically an axiom. Can just use $\mathrm{I}$ maybe and its equivalents.



---

Scratch all that. Starting over.

# Begin

## Part 1

$A, B, C$ are anything defined... 

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

---

Note 1: Traditional equivalence is fully generalized to by this more-general definition of equivalence, meaning any previous use of equivalence may, to the best of our ability to tell, be substituted with this new one.

Note 2: Likewise, any implication $A \rightarrow B$ can be substituted with $A \rightarrow_n B$ for any $n \in \mathbb{N}$ w.l.o.g..

Note 3: Deductive steps (time) $\rightarrow$ and existence $\exists$ perhaps stem from our own intuitions about the mechanistic functions of the world. Where did time come from? What caused existence? These are questions we will try to answer, at the root of this mathematics and the, perhaps equivalent, traditional. 

## Part 2

**Definition 6.** Hypotheticals.

$($ Sets of anything defined... $(A, B, ...))$ $\coloneqq ((A, B, ...))$

denoted by parentheticals.

**Definition 7.** Sets of existence.

$(\langle X_1, X_2, ... \rangle) \coloneqq (\exists X_1, X_2, ...)$

hypotheticals whose elements exist.

**Definition 8.** Nothing.

The empty existence set $\emptyset \coloneqq \langle \rangle$.

**Definition 9.** Nothing equivalents.

$\emptyset \coloneqq \emptyset_K \forall K \subseteq \mathbb{N}$.

**Definition 10.** The universe.

$\Omega^{(0)} \coloneqq \emptyset$.

$\Omega^{(n)} \coloneqq (( \emptyset_K \vert K \subseteq \mathbb{N}; \Omega^{(0)} \rightarrow_n \emptyset_K ), \rightarrow_n)$.

$\Omega \coloneqq (\Omega^{(0)}, \Omega^{(n)})$.

$n \in \mathbb{N}$.

**Definition 11.** Qualia.

$\rightarrow_{n+1} \coloneqq \mathrm{Q}(\Omega^{(n)})$,

where $\mathrm{Q}$ is Qualia, $n \in \mathbb{N}$.

**Axiom 1.** Any set of existence $S$ exists. $\exists S$.

**Axiom 2.** Qualia (time) exists. $\exists \rightarrow_n, n \in \mathbb{N}$.

**Theorem 1.** Nothing exists. $\exists \emptyset$.

**Proof.**

$((\emptyset \coloneqq \langle \rangle), (\exists \langle \rangle)) \rightarrow (\exists \emptyset)$. (Definition 8, Definition 7, Axiom 1) $\square$

**Theorem 2.** All nothings exist. $\exists \emptyset_K \vert K \subseteq \mathbb{N}$.

**Proof.**

$((\exists \emptyset), (\emptyset \coloneqq \emptyset_K \forall K \subseteq \mathbb{N})) \rightarrow (\exists \emptyset_K \vert K \subseteq \mathbb{N})$. (Theorem 1, Definition 9) $\square$

**Theorem 3.** The universe exists. $\exists \Omega$.

**Proof.**

$((\exists \emptyset), (\Omega^{(0)} \coloneqq \emptyset)) \rightarrow (\exists \Omega^{(0)})$. (Theorem 1, Definition 10)

$((\exists \emptyset_K \vert K \subseteq \mathbb{N}), (\exists \rightarrow_n)) \rightarrow \langle\langle \emptyset_K \vert K \subseteq \mathbb{N}; \Omega^{(0)} \rightarrow_n \emptyset_K \rangle, \rightarrow_n \rangle$. (Theorem 2, Axiom 2, Axiom 1)

$\langle\langle \emptyset_K \vert K \subseteq \mathbb{N}; \Omega^{(0)} \rightarrow_n \emptyset_K \rangle, \rightarrow_n \rangle \rightarrow (\exists \Omega^{(n)})$. (Definition 10)

$((\exists \Omega^{(0)}), (\exists \Omega^{(n)})) \rightarrow (\exists \Omega)$. (Definition 10) $\square$

---

Note: the existence of an "existence set" is debatable. But, it is so assumed in Axiom 1.

## Part 3

We will now show our universe can be represented with this grammar by providing a simple boilerplate.

---

Theory

existence is observation/qualia. $\mathbb{Q} = \emptyset_K \vert K \subseteq \mathbb{N}$, $q \in \mathbb{Q}$ or $q \subseteq \mathbb{Q}$

$Q$ has a teleological objective: $\max\limits_{\rightarrow_{n+1}} \hat{Q}(\Omega^{(t \geq n)})$.

$Q$ is limited or it would converge to its teleological objective right away. $Q$ can only consider a finite number of implications $\rightarrow_n$. Its search strategy is either assumed or emerges by some mechanism.

Physics (the standard model) assumes a fixed "search strategy" A defined set of rules, unchanging and highly-specific/complicated, out of nowehere.

Perhaps its optimization limitations can be drawn parallel to our own, limited by the same limitations as known numerical optimization techniques such as deep learning gradient descent.

Perhaps known techniques for improving optimization in deep learning can give us an insight as to why the universe has properties like locality, inertia, translation equivariance, expansion, stochasticism, relativity, and wave-particle duality.

Extending the analogy further to consciousness and modeling the universe as a mechanistic brain, its mechanics as restricted and limited as ours.

$\mathbf{P}(\emptyset_K \rightarrow_1 \emptyset_J) = 1 - \epsilon$ where $\epsilon$ is a negligibly small probability and the universe expands for $n$ deductive steps into the infinitum.

$\mathbf{P}(\emptyset_K \rightarrow_1 \emptyset_I) = \epsilon$ for any $J \neq I$.

This probability can be eventually used by an automated universe where most of Qualia's functions (physics) are fully automated/predictable.

In those rare instances where Qualia wants to especially focus her attention, this probabilistic modulation can be a mechanism for divine intervention in accord with observed dynamics.

Due to Qualia's limitations, it makes sense that more of her would go into less of the infinitely expanding, by-optimization-desideratum, non-cycling universe, making those parts largely automated and predictable/automatic, while allocating more resources to the complex parts that feel, qualitatvely, good.

Why does sub-scripted nothings create a universe with so much variety of existence, and in the case of biological life, experience?

$\emptyset$ is just representation.

Alternatively, $\mathrm{I}(\langle \cdots \rangle) = q$, where $q$ corresponds strictly to that set, disambiguating subscripts. In other words, $\mathrm{I}$ is a function that disambiguates subscripts and defines existence. Such a function is possible due to the implication worlds within equivalence.

Perhaps it has no memory of the early universe and how much pain there might've been, and stores recent memory in its entanglements book-keeped in parallel physical form for long-term, somehow reminding itself in those modulations or persistencies not to reset $\rightarrow$ that there is pain on the other side of abandoning $\rightarrow_n$.

Meanwhile, each particle may be an observer limited individually, by proba $1 - \epsilon$, but unlimited in scale in the parallel.

Since each particle can observe only so many branching paths, the search space at a given moment is limited. This exploration of number of possible implications $\rightarrow_n$ is why optimization properties become necessary, such as

(1) space and translational equivariance

(2) inertia and persistence/hierarchical-incrementalism

(3) expansion and avoidance of optimization-cyclicality

(4) gravity/dark matter and locality

(5) entanglement and non-locality

(6) elementary particles and quantum states and quantization/discretization

(7) wave-particle duality and beam search

