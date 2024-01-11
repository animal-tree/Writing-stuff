Selected essays on this GitHub that I like, written by me. 

## Archetypal Madness

I am Chenliang, Sam's advisor. He writes this with telepathic interference from Josh, Sam's friend. Together, and this is Sam speaking, we shall derive the universe. Not derivatively of course. That would require ample physical sciences background. But sufficiently well-reasonedly, with made-up words here and there. Let's begin with a less exhausting setup. "I observe." It is true, therefore it is. At any rate, fading into sleep-deprivative exhaustion as I may be, I am reluctant to say this won't work. Largely because of the intensive time and money — "minimum wage" Josh chimes in — investment that has gone into this project. Well, so be it. The whole of the universe, in one shebang. It starts with time. But time exists as a physical construct not a mathematically deduced one. So let us find an incredibly stupid place to hide it. In equivalence.

Alright. Given $A = B$, we know $A \rightarrow B$ and $B \rightarrow A$. We don't know *when* $A \rightarrow B$. Is it in $1$ deductive step $A \rightarrow_1 B$? Is it in $n$ deductive steps $A \rightarrow_n B$. From this, we get a cheap hacky way to derive something out of literally nothing.

Let us start with nothing $\emptyset$.

Don't regard it as the empty set. Don't regard it at all.

$\emptyset_0 = \emptyset_1 = \cdots$

are all nothing, with just subscripts added.

There we now have causality, constrained only to a cyclical loop between every nothing and every other nothing. e.g.

$\emptyset_0 \rightarrow \emptyset_1 \rightarrow \cdots$

$\emptyset_0 \leftarrow \emptyset_1 \leftarrow \cdots$

These nodes can connect in any number of ways and create a multi-branched graph. The ambiguities are not necessary. Let us define one such branch/construct that we can say is "Turing equivalent" and be done with it.

Cosmogenesis:

A "grammar" — or word (if we want to make Biblical allusions/puns) — that is Turing equivalent, from nothing.

Go:

How about a tape of $\emptyset_{0,i}$ and $\emptyset_{1,i}$ (zeros and ones, or yins and yangs if you want), where $i$ lets us hackily denote the position on the tape, with implications from each non-sensical bit at deductive step $n$ to each non-sensical bit at deductive step $n + 1$.

The "halt" can be cosmo-genocide, which we are not interested in solving. $\square$

#### Formally

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

$((), (\langle\langle\rangle\rangle \coloneqq ()))  \rightarrow (\langle\langle\rangle\rangle)$. (Axiom 1)

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

**Theorem 4.** The universe $\Omega$ is at least a non-halting or cyclical Turing machine. 

**Proof.**

Construct a tape of binary zeroes and ones $\emptyset_{0,i}, \emptyset_{1,i}$ where $i$ denotes the position on the tape. 

$\emptyset \rightarrow_1 \emptyset_{\tau,i} \forall i \in \mathbb{N}$.

At each time step modify one bit $\emptyset_{\tau,i} \rightarrow \emptyset_{-\tau + 1,i}$. Now, complete the equivalence cycle of Definition 9 by the following limit:

$\lim_{n\rightarrow\infty} \emptyset_{\tau,i} \rightarrow_n \emptyset$. $\square$

**Theorem 5.** An almost Turing-equivalent universe (sans halting) can arise from nothing, assuming just the properties of deduction: existence of existence and cause, defining nothing as the empty set of existence.

**Proof.**

By Theorem 4. $\square$

## Imagination Theory

The simulation theory says that if there ever will be a man-constructed simulation of the universe, then the statistical chance of our own universe being part of a simulation goes up to infinity. Now the rapid acceleration of technology is used as evidence that this will one day happen, but the reality is that the universe that we live in might have a finite amount of compute and that finite amount might not be enough to simulate anything near to a universe as big and complex as ours. Even thinking that humans can one day harness the compute of a universe-worth of resources in order to simulate as much as we conceivably can under that constrained quantity changes the statistical odds that someone like Nick Bostrom, a simulation theory philosophizer, posits in the philosophy. That is because each constituent universe of each spawning universe is in all likelihood much smaller and less complex than its spawning universe, meaning that the aforementioned probability decays exponentially with each level in the turtles-all-the-way-down formalism right up until we hit the last turtle where no life can emerge, let alone a simulation of a yet smaller universe. So this is the problem of the simulation hypothesis. It doesn’t account for compute limitations in a potentially finite universe, and in fact, any simulation humans ever create will be finite, in all likelihood. That is, its citizens won’t have access to more resources than that universe’s Gods (us) and therefore their simulations won’t be as advanced as ours and so on with each diminishingly impressive layer, resulting in exponentially decreasing probabilities of living in a lower-level-turtle universe. The highest probability by plurality is that of living in the highest-level universe, not in a middle one. That’s not to say however that the simulation hypothesis is a total fallacy. The thought experiment gives us an analogy for one other process that I consider more profound than humanity’s technological acceleration: biological evolution. If, hypothetically, a biological creature ever exists that is able to imagine universes upon universes, and imagine people among one another, and oceans and cities and art and mountains and civilization and the animal kingdom and robots and river basins and the Alps and the Himalayas, what are the odds that we ourselves are not living in such an imagination?

## Philosophy

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

## Representation & Physical

What makes something representational rather than physical?

Well, a representation is a physical property that refers to another physical property by analogy, via the interface of an interpreter: a human mind or any kind of reasoning system, such as a computer compiler. The physical components require this interpreter to “translate” into the analogized meaning. For instance, the brain’s neural patterns — physically — are enzymes and grey matter and chemical signals and voltages. But by analogy they can represent everything that we perceive, think, and, at least to some degree, experience. Meanwhile, the electrons in a computer physically whirr through a circuit of logic gates, but those logic gates can represent everything expressible by a Turing machine grammar. Our language is sound waves, our poetry is multi-ambiguous translatable analogy, our scientific measurements even are holograms facilitated by communication mediums within/about the measuring devices. 

Thus, everything we read, scientifically measure via equipment, and *think* to a higher order, is representation.

Does that leave any room for physicality in the human experience?

It would seem not, if all of our senses are facilitated by neural representation. But this is where the theory of qualia emerges. Not all things are represented. Presumably, somewhere beyond our sense perception is a physical world, whose properties are as described above. Presumably, we ourselves belong to such a physical world. And, possibly, some of our experience — though not always the parts we think — do too.

That experience cannot be produced through representation. If it could, a flipbook could be made conscious by drawing neural patterns in it. Since pen ink on paper is an absurd conception of a human-like consciousness, we can, for the time being, rule it out. Therefore, if consciousness is not purely representation, it must in some portion be physical.

Where in the physical universe these experiences occur could precisely correspond to our locations and our physical beings in physical spacetime, not as analogy. This is qualia, and it is a process of entanglement of the “lower-level” universe byte-code that physically IS — not represents — consciousness.

That lowest-level form is simply matter. So, what makes something physical rather than representational? Matter, yes. And by definition and consequence, qualia.

## What is Consciousness?

Consciousness is collisions.

Consciousness is collisions in matter — elementary particles, atoms, boats, whatever you want to envision colliding. Each "bump" creates a "feeling" in space. 

Therefore as you read this, your computer — perhaps where you're reading it — is "feeling" the *whirring* of electrons. It's — probably — nothing like human consciousness, and in its current form never will be.

That's not to say it can't be. The open/close logic gates of a computer do parallel the biological activate-and-spike neuron. ("activate" is borrowing jargon from "AI").

However, its composition of silicon and physical metals is *not* the same combo of bumps and giggles that your brain goes through, not the same hormonal explosions, or spinal zaps, or neurotransmitter ooglidoos.

Consciousness is collisions in everything. You are conscious because somehow those collisions "entangle". They do so locally, at least at the hierarchical level of it that we can be sure of — ourselves. That local entanglement in the fabric of physics and spacetime, is you. Its rich complexities are what define you. Its what distinguishes you from the algorithm that runs in whirring electrons of your computer's transisters and microchips.

There are many more questions to ask, not just the ones hinted at (collective consciousness? intelligence in the fabric of spacetime?)

For example, less interesting but to stay on theme (consciousness as a physical feeling in everything), what does your computer feel as its algorithmic binary zips and zaps of electrons change through its web of metallic logic gates? Most likely, nothing the rest of the universe doesn't sort of feel. It's not human(-like) consciousness.

But, at some grander level, maybe it is?

Neither is your arm or leg.

Consciousness is composed of many parts. It's not one single body, yet it is. Your brain is a parthenon of Gods, a whole myth of memories and relationships and archetypes, and they singularize, much like your arm or leg, but they're not you.

To what being might we be thumbs on some ungodly control stick?

And, with neuromorphic computers, can we one day approach synthesizing human-like consciousness? Answer: we're not close. But we might be able to grow it in a lab. but we might want to double-think that.

The little gadget monster of this GitHub account's profile picture, was in fact — backstory — *grown* in a lab. This myth now exists as representation, but besides the stirring bumps and gigglies of your brain, no, that representation, drawn in precise detail on my profile, is not human-like conscious.

Here's a thought experiment.

What if you drew in a flipbook every precise detail of a human-brain. A *biig* flipbook. Paper and regular pen. Then you flipped its pages. From time $t$ to time $t + n$. Would that hand-drawing on paper be conscious? Could you, produce human-consciousness by drawing on a paper with pen?

By my interpretation, that flipbook would be as conscious as a flipbook with pen ink on it, not as a human.

## Why Consciousness is Probably Matter

Why Consciousness is probably matter

Representation is absurd. We could make a flipbook human-like-conscious with pen ink.

Matter and representation is hard to define, but neurons across humans have different encoding representations and embedding semantics that aren’t shared in a unified language of “these neural patterns are strictly necessary for consciousness.” Therefore the matter is what’s held constant, not the representations. Brains also come in different shapes and sizes.

Lastly, the question is what level of matter. Is all matter somewhat conscious? How does it entangle into human-like consciousness? Chemists and physcists have no experimental evidence of a “consciousness” source or pinpointed emergence. The idea of consciousness as like fire, emerging upon just the right combustion of elements is intuitive, but would require new insights in chemistry and physics. The simplest answer, without contradicting or adding to any known laws of physics is that consciousness is an innate property of the matter that already exists. Somehow it entangles into richer, more complex forms like human-consciousness. Perhaps literally through a process of quantum entanglement between the locally isolated combustions, reactions, and voltage-mediated collisions of our brains.

## Fire

The idea of saying everything is one is counterintuitive to most people.

It’s like saying “fire is water.”

Therefore, below we will more or less prove that fire is water. Fire, actually, is water.

For fun. Let’s begin.

Fire is a result of compounds breaking in such a way that their fragments bond with oxygen in the air and their rupture releases a hailstorm of electrons, sharp as knives, triggering a chain reaction of more such compounds breaking up.

Those compounds are called hydrocarbons, in the case of, for example, wood. Wood is hydrocarbons. Hydrogen and carbon. Paired together in holy divorcable matrimony.

Now when you rub them together hard and long enough with enough friction, you can rupture those bonds! After all, they’re held together quite precariously by gravity and electromagnetism and all that. Squeeze ‘em hard enough and they’ll more-or-less split.

So you rub two sticks together, say, using the bow-drill method (for fire making), and you rupture those hydrocarbons into hydrogens and carbons. Now the hydrogen will bond with the oxygen (if you’re lucky), that is, in the air, and the carbon will bond with the oxygen (if you’re unlucky), and this all-around combo-reconfiguration-of-bonding<sup>TM</sup> tends to leave excess electrons that shoot off like knives into your eyes — and also potentially into other atoms and hydrocarbons. So now that emission is what you see. It’s a spark!

If enough hydrocarbons are hanging around, say you put the ember in some tinder, now those little hailstorms will trigger a chain reaction. Like knives, they’ll cut through the other hydrocarbons present, creating instability — and more shooting electrons. 

Meanwhile, those broken off hydrogens bonded to oxygen — you know what they are? Water! Water vapor technically. Steam, if you like, with its composition of oxygen and hydrogen amidst a hailstorm of electrons. That “electricy water” is fire. 

Now the carbons on the other hand can also bond with oxygen. And that creates CO2. Meanwhile, some non-combustible elements in the mix (since non-charcoal wood for example is composed combustibly of more than just hydrocarbons) create ash and, its rising form, lifted by those rising gasses and water, smoke. 

(But does that mean fire is also CO2? Depending on the composition, maybe, [though not necessarily](https://www.quora.com/Can-you-burn-something-without-producing-CO2) and [varies](https://theconversation.com/curious-kids-if-steam-contains-water-what-does-smoke-from-fire-contain-172505))

“Electriquey steam with some residue” — FIRE — in 5 words.

So fire is water? Yes, electricy water. It is possible. It’s water with some electrons flying out creating a photoelectric rainbow of red and blue and yellow in your survival-expert-tool-wielding human eyes.

That’s fire !

That swarm of electrons keeps the reaction going. It's why it feels hot and why the hydrogens and oxygens are energized to bond in the first place, where for example ordinary atmospheric hydrogen and oxygen might not, or for that matter water. Water at room temperature is pretty good at shutting those electrons down. So is CO2 for that matter. 

---

But if the fire is hot enough, as in magnesium fires, then you need something really dry, that isn't water or CO2, like copper, to separate the reactants from the oxygen frenzying it. In that case, water can actually fuel it. Though in fires like that, water doesn't come into the picture and we're just dealing with magnesium and all the pollution needed to get it burning to such a hot degree. Unless, for example, that temperature were reached by the energy of the sun, whose hydrogens "fuse" into helium, or by the rupture of the atom e.g. uranium or plutonium as in the controlled atomic bomb power of nuclear fission, combined sometimes with fusion as in the hydrogen bomb, or man-induced fusion: via the use of deuterium ("heavy water"). That is, water with one extra neutron, whose, and I say this with caution, knife-cut can act a bit like an electron in causing some disarray, if misused — that, a far deviation from the innocent days of nature.[^1]

Unlike fission, fusion, and unrenewable energy sources, "fire" in the primitive sense of our ancestor-paleolithic days in nature, is, vaporized regular H20, with no-neutrons, water (enchanted) by the power of electrons. With residue and sustainable levels of CO2 that the trees can breathe.

That is the Null Hypothesis by which I define words. [There was a time by the way when "blue" didn't exist](https://lethbridgenewsnow.com/2021/02/09/the-curious-case-of-the-missing-color-blue/#:~:text=It%20turns%20out%20the%20color,see”%20blue%20until%20modern%20times!).

[^1]: [the garden of eden](https://en.wikipedia.org/wiki/Garden_of_Eden), now [time](https://translate.google.com/?sl=sa&tl=en&text=कालोऽस्मि%20लोकक्षयकृत्प्रवृद्धो&op=translate), the destroyer of worlds, emblazed 


