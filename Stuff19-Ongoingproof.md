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

$((\exists \emptyset), (\emptyset = \emptyset_K \forall K \subseteq \mathbb{N})) \rightarrow (\exists \emptyset_K \vert K \subseteq \mathbb{N})$. (Theorem 1, Definition 9) $\square$

**Theorem 3.** The universe exists. $\exists \Omega$.

**Proof.**

$((\exists \emptyset), (\Omega^{(0)} \coloneqq \emptyset)) \rightarrow (\exists \Omega^{(0)})$. (Theorem 1, Definition 10)

$((\exists \emptyset_K \vert K \subseteq \mathbb{N}), (\exists \rightarrow_n)) \rightarrow \langle\langle \emptyset_K \vert K \subseteq \mathbb{N}; \Omega^{(0)} \rightarrow_n \emptyset_K \rangle, \rightarrow_n \rangle$. (Theorem 2, Axiom 2, Axiom 1)

$\langle\langle \emptyset_K \vert K \subseteq \mathbb{N}; \Omega^{(0)} \rightarrow_n \emptyset_K \rangle, \rightarrow_n \rangle \rightarrow (\exists \Omega^{(n)})$. (Definition 10)

$((\exists \Omega^{(0)}), (\exists \Omega^{(n)})) \rightarrow (\exists \Omega)$. (Definition 10) $\square$

---

Note: the existence of an "existence set" is debatable. But, it is so assumed in Axiom 1.

We have thereby "defined" nothing. (Definition 8). Without loss of generality, it could be defined as something else. Anything else. Whatever "nothing" is.

But maybe "nothing" isn't? Maybe "nothing" is the undefined.

...then define it as that. Its only use is as an arbitrary subscript-able variable.

We have, however, assumed subscripts (e.g. variables/hypotheticals, Definition 6). There are some recursive definitions here, yes. Technically not prohibited. But also easily falsifiable. Find a proof or deductive logic that doesn't fit into this framework.

(And in such a case it might be easy to amend the current framework).

Argument: maybe, whatever nothing is, has no equivalents.

Response: then axiom 1 can be changed, w.l.o.g., to assume the existence of something denoted by $\emptyset$. That something just exists. Axiomatically forever.

However, though unnecessary, we would lose an explanation for the existence of existence. Axiom 1 currently assumes both.

---

**Theorem 4.** The universe $\Omega$ is at least a non-halting or cyclical Turing machine. 

**Proof.**

Construct a tape of binary zeroes and ones $\emptyset_{0,i}, \emptyset_{1,i}$ where $i$ denotes the position on the tape. 

$\emptyset \rightarrow_1 \emptyset_{\tau,i} \forall i \in \mathbb{N}$.

At each time step modify one bit $\emptyset_{\tau,i} \rightarrow \emptyset_{-\tau + 1,i}$. Now, complete the equivalence cycle of Definition 9 by the following limit:

$\lim_{n\rightarrow\infty} \emptyset_{\tau,i} \rightarrow_n \emptyset$. $\square$

---

Question: how to prove this with implications by the definition of proof?

Easy: Define a Turing machine as a hypothetical and show that this definition is equivalent to that hypothetical.

---

Of course, we are assuming each $\emptyset_I$ has a unique qualia... well, not yet. But that raises the important question: How to get qualitative existence from this array of suspiciously distinguishable equivalents? ...

---

**Theorem 5.** A Turing-equivalent universe can arise from nothing, assuming just the properties of deduction: an existing set of existence and time.

**Proof.**

By Theorem 4. $\square$

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

---

There are many reasons a teleology could emerge. One is evolutionary survival.

### Part 4

One way to describe it as I re-gathered my thoughts from my journals:

Each particle weighs each other particle (or it’s linear projection) by inverse Euclidean distance. That’s it, but the heads represent branching realities of that particle, branching velocities to which that particle’s position is added. They are sampled from, the velocities, as Gaussians, and each get a truncation point for interacting that accumulates, somehow a la beam search. 

This accumulation and truncation can be exactly like beam search, nucleus sampling, or something more “entangled”. 

This entanglement we believe is responsible for higher orders of consciousness, that is, richer and more complex forms of the observation/qualia at the basis of the universe. 

Question: how does beam search work?

It truncates the lowest probability words, branching from the top N, at each time point. 

They can however accumulate over layers/time points? 

They can but that’d be redundant… unless we were preserving over multiple time points and time horizons to give wp duality a memory. 

These richer temporal entanglements might’ve what human consciousness is, where consciousness is, at its basic form, the collision between observers, two particles. 

Consciousness as collisions, each collision has a feeling called “qualia”. Each entangled collision has a richer feeling called consciousness, and eventually, richer human consciousness, paired together with the patterned brain activity of the brain and its corresponding voltages, hormonal explosions, chemical reactions, neurotransmitter exchanges, and electromagnetic field all that generate from its murky depths in your skull. Metaphors un-intended!

But that is consciousness. 

The ambiguities of language, however, are another thing. 

---

Wave-particle duality and entanglement.

Describing it, in terms of $\emptyset$ and $\rightarrow$ and $Q$ and $\Omega$:

$\emptyset_{x, v, \tau, i, k} \rightarrow_1 \emptyset_{x + \frac{v}{c}, v, \tau, i, k}$

if collision:

$\emptyset_{x, v, \tau, i, k} \rightarrow_1 \emptyset_{x + \frac{v'}{c}, v', \tau, i, k+\hat{k}}$,

where $v$ depends on $v, \hat{v}$.

$x, v, c \in \mathbb{N}, \frac{1}{c} \leq v \leq c$.

truncate w.r.t. $i$ top-N $k$.

But no way to get subscripts (qualia) of $\emptyset$. Thus have to use $\mathrm{I}$ an observer / the Identity function to be able to create a custom equivalence graph for singular and colliding (double) existences.

Can we prove that in order to do this we need $\emptyset$ to be a function

$\rightarrow$ an existence function, not non-existence.

Furthermore, $x$ needs to be circular coordinates (e.g. defined by a unit vector or just implied as such).

Collision: $\mathrm{I}(\mathrm{I_{\mathit{x, v, \tau, i, k}}}) \coloneqq \mathrm{I}(\mathrm{I_{\mathit{x', v', \tau', i', k'}}})$.

$\mathrm{I}$ is both observer and qualia. But while each observer is equivalent, each qualia is distinct.

# From the ground up

Go:

---

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

**Axiom 1.** Existence exists. $\langle X_1, X_2, ... \rangle \coloneqq \langle\langle X_1, X_2, ... \rangle\rangle$.

**Axiom 2.** Cause exists. $\exists \rightarrow$.

**Theorem 1.** Nothing exists. $\exists \emptyset$.

**Proof.**

$(()) \rightarrow (\langle\rangle)$. (Definition 7)

$(\langle\rangle)  \rightarrow (\langle\langle\rangle\rangle)$. (Axiom 1)

$(\langle\langle\rangle\rangle)  \rightarrow (\exists \langle\rangle)$. (Definition 7)

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

**Theorem 4.** The universe $\Omega$ is at least a non-halting Turing machine. 

**Proof.**

Construct a tape of binary zeroes and ones $\emptyset_{0,i, t}, \emptyset_{1,i, t}$ where $i$ denotes the position on the tape and $t$ denotes the time point.

$\emptyset \rightarrow_1 \emptyset_{\tau,i,0} \forall i \in \mathbb{N}, \tau \in (0, 1)$.

This is the initial state, defined by $\tau$.

At each time step modify one bit 

$\emptyset_{\tau,i,t} \rightarrow_1 \emptyset_{-\tau + 1,i,t+1}$

or "stay":

$\emptyset_{\tau,j,t} \rightarrow_1 \emptyset_{\tau,j,t+1}$.

Now, complete the equivalence cycle of Definition 9 by the following limit:

$\lim_{n\rightarrow\infty} \emptyset_{\tau,i,n} \rightarrow_1 \emptyset$. 

The infinitum allows us to leave the potential cyclicality of the universe a mystery. $\square$

**Theorem 5.** A universe capable of simulating a Turing machine can arise from nothing, assuming just the properties of deduction: existence of existence and cause, defining nothing as the empty set of existence.

**Proof.**

By Theorem 4. $\square$

---

However, a Turing-equivalent grammar assumes someone defining the "word" of the grammar. Why would it be "this" universe instead of some other Turing-equivalent universe?

The universe as representation however is not the universe as matter. Representation, while convincing, has no qualia. It makes no sense why/how these nothings and their somehow-distinguishable equivalents, as they chain together through the inner-worlds of deduction, actually bring rise to sensation and reality. We have a theoretical model, capable of representing the universe by the known laws of physics. But not an insight as to why the universe *matters* beyond just numerical nothings.

That is why qualia is essential. Not just to human consciousness, but to the basis of physics. "qualia" — whatever it is — says "this is real."

The less qualia in an experience, the "greyer" it becomes, until, eventually, it disappears from existence. qualia is in a way an existence metric. Something that gives something meaning/matter beyond its more-arbitrary representative form.

This is an experience in human consciousness. Arguably not in cosmic space and time. But why "matter" would exist, in the sense that differentiates from just the existent universe defined in our proof, is what qualia defines. qualia defines existence beyond representation, existence in actuality.

Further entangling, from its base level of primordial consciousness to richer forms through physics of entanglement that produce human consciousness and the consciousness of other biological lifeforms.

In the subsequent re-derivations, we'll construct a universe made of matter, not binary 1s and 0s.

Distinguishing the two, as perhaps you're reading this on a computer, is the job of qualia. Do each of those 1s and 0s have a qualia? In your computer, maybe! But they don't add up to the kind they're representing. The universe in front of your screen is not the universe around you.

---

(1) I will be in your spot.

(2) You will be in my spot.

(3) We will be in — same spot.

$A \vert B \vert C \rightarrow$ collision.

But we need an observer function, something that distinguishes nothings and their subscripts (e.g. position).

However, for some reason, $\emptyset$ needs to be the observer function? Using $\emptyset$ defeats the power of the implication graph, I suppose?

As in,

$\emptyset \rightarrow \emptyset_X \rightarrow \mathrm{I}(\emptyset_X) \rightarrow \emptyset_X \rightarrow \emptyset$

gives us only one observation.

We can then transition to other observations by arbitrary choice of $\emptyset_{X'}$.

So how to pre-define this is unclear. We have a cyclical loop. However, we can introduce probability as our solution,

where since $\emptyset_X \rightarrow \emptyset_{X'}$ between observers is probabilistic, the graph, eventually, as long as it extends into the infinitum, converges every node back to every other node.

But in the meantime, the implication graph can be pretty defined. With transitions from $\emptyset_{x,v} \rightarrow \emptyset_{x+v,v}$ for example. $c$ is used to give each increment a waiting duration, but we'll get to that later.

Why use an observer at all? Why not just transition between sets of $\emptyset$?

Well, observer with subscripts wouldlet us output anything we want, meaning an observation of multiple subscripts can output an observer with a subset of those subscripts, but I suppose $\emptyset$ can do that too?

Perhaps $Q$ can just pick which $\emptyset$ to truncate. i.e. each pair has a probibilistic implication, or multiple implications.

What if two observers somehow observed each other? And then their own subscripts changed accordingly, probabilistically and with branching implications that could somehow, e.g. by $Q$, be truncated per-observer.

---

The previous formulation gets usas far as a non-halting Turing machine, but this one more intuitively models the physics of the universe able to directly — without solely binary 1s and 0s on a Turing machine tape — represent the universe. That is, without a tape of just individually changing binary bits — a representation that would be ugly and hard to relate to our actual real world. The below formulation "collides" particles with other particles and directly expresses forces of interaction, velocity, and wave-particle duality. As well as observation, qualia, and entanglement that can express how rich experiences of human consciousness can form through the intricate complexities emergeable from this model.

What if we represent space with nothings $\emptyset_{x,y,z}$.

Now we point to each nothing with an observer $\mathrm{I}_{v, \tau, k, , i}$ let's say.

We can then change this implication graph how. Well, we can cycle back to the observers from their corresponding point in space but how ! Each deductive step needs to update the implication graph. One point in space only has an outgoing arrow to it corresponding observer situated in it via an ingoing arrow.

At each deductive step, this whole graph updates, how, by Qualia I guess. Then the cycle is completed by making each outgoing arrow probabilistic, potentially back to $\emptyset$. Er, the observer in this case can be represented as well by the $\emptyset$. An arrow needs to be able to delete and update the next arrow. Then the outgoing arrow can simultaneously point to a new observer and sets its outgoing spatial arrow. It can also delete the previous observer outgoing arrow, thereby translating the observer across space.

---

Existence can be defined as a recursive function w.l.o.g., specifically the Identity function.

$\mathrm{I} \circ \cdots \circ \mathrm{I}(\emptyset) = \emptyset$.

Where each "observation" by the Identity function (the "observer") signifies existence. Furthermore, by defining it as such we can more intuitively justify the "realness" of reality/matter over representation. This is what qualia is. Infinite self-observation by a self-observing observer, thus making its many self-observation equivalents distinguishably unique by this mysterious property, in the existence of definition, of qualia. Giving tangible concept to Axiom 1.

More formally, we will define the existence set as an observer's observation:

$\mathrm{I}(A, B, ...) \coloneqq \langle A, B, ... \rangle$

whose output, $A, B, ...$ are able to distinguish equivalents, that is, qualia.

This can be shown deductively possible by the following constraint on the Identity function, not losing generality:

Suppose $\emptyset_i = \emptyset_j$.

$\mathrm{I}(\emptyset_i) \coloneqq \emptyset_i$.

$\mathrm{I}(\emptyset_i) :\neq \emptyset_j$.

For example, the following cyclic implication graph would satisfy the definition of equivalence, as supposed, while still distinguishing unqiuely:

$\mathrm{I}(\emptyset_i) \coloneqq \emptyset_i \coloneqq  \emptyset_j \coloneqq \mathrm{I}(\emptyset_j)$,

where $\coloneqq$ denotes instantaneous equivalence. (Definition 3).

In fact, the empty set, non-existence, "nothing" (Definition 8), can be re-defined as $\mathrm{I}$. Leaving us with nothing but a self-observing observer, who existence is self-distinguishing (qualia).

**What is existence?**

**Answer:** Distinguishable definition.

**Answer:** qualia/observation.

**What causes existence?**

**Answer:** "Nothing", the base thing at the eternal reality of the universe, is a function, not a set. $\emptyset \coloneqq \mathrm{I}$.

**Answer:** Observers/observer.

**What is cause?**

**Answer:** A teleological purpose. $\rightarrow_n = \mathrm{Q}(\Omega^{(n)})$. Or better:

$\rightarrow_{n+1} = \max\limits_{\rightarrow_{n+1}} q(\Omega^{(t \geq n)})$.

**Answer:** Qualia (uppercase). Next up.

There are many reasons a teleological purpose could emerge. One is evolutionary survival. Another is the presence of pain qualia amid the everything/anything that is emergent from the random application of $\mathrm{I}$, or for that matter, desire. Objective reality with an objective.

---
