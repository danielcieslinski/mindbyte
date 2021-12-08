# Mindbyte (metaknowledge)

[![hackmd-github-sync-badge](https://hackmd.io/ZTe9RLc5SEqnLHxKk8ygWA/badge)](https://hackmd.io/ZTe9RLc5SEqnLHxKk8ygWA)

###### tags: `research` `math` `AI` `knowledge` `metalearning`

## Purpose
Creation of unified and fully adaptabile and reusible knowledge system, allowing for advanced and fully interptible numerical abstraction. 

## Meta-taxonomy for knowledge related machine learning problems

I propose two universal equations, which have their modelling abilities dependent only on the constraints induced by the context, within which presented. 

My motivation was to reate unified mathematical description of knowledge related problems.
Specification of problems that is,
-  Self explainable.
-  Invariant under transformations, which concern used `knowledge representation`.
-  Capable of modelling transitions between those representations. \*
-  Growing in size, more or less, proporionaly, to the complexity of the problem, that it describes

\* _This is heavily related to another concept, which I'm currently researching and will provide the follow-up in near future._*

#### Quantitive model

$$\tag1\dot{\Omega} = X + B + C $$

#### Dynamic model

$$\tag2 \Omega(T+[t_{0}, t_{1},..., t_{max}]) = \Omega(t) * F(K) + \lambda\downarrow I$$

### Modelling possibilites
Let $B$, $C$ and $\Omega$, represent sets, then `+` is summation operator, such that in context of equation $\Omega$ = $B+C$ where B and C are set, `+` denotes sumset, function.
I allow $X$ to be variable of any type(in computational sense), however it must preserve all properties of `random variable`, understood with common statistical sense.
Second equation can be rewriten as UDE, such that $\Omega(t) = \dot{\Omega} ; \forall t \in T$

Therefore any system is fully expressible as the linear combination of given equations, where each is the combination of those two.

 
> My Motivation behind introducing those equations, is to create usable tool, that could be used for categorical clustering of computational problems, that somehow concern the topic of `knowledge`.
> For now I'll save mathematical redundancy, that would require construction of _(what I consider)_ "a proper proof"
> required to show, they are capable of generating the taxonomy, by writing some nonsense about their symbolic capacity.

### Notation
#### Quantitive model

<!-- #todo Clearer notation definitions. \
#todo Finish the proof of modelling sufficiency -->

$\dot{\Omega}$: Complete set of information.

$X$ : Random variable, supporting totality of $\Omega$, when combined with $B$ and $C$ under the summation operation.

$B, C$ : Any mathematical varieties, of properties satysfying constrains induced by the context and definition of $X$. 
Their presence in problem description is optional. Should be rather measurable and comparable by common norm. 

> It falls pretty far from living standard, of formal definition and this is very annoying, that mathematics even though, so polluted,

#### Dynamic 

$\Omega(T)$: Complete set of information, given context, with time. Where time is monotonic linear function, which directs the growth of entropy(size of $\Omega$)

$\Omega(T+[t_{0}, t_{1},..., t_{max}])$ : $τ = t_{0}, t_{1},..., t_{max}$, represent $\Omega$ in particular timestamps, $T + τ$ is non-surjective, for absolute(independent) time function T.

$F$: A function set, where $\Omega(T) * F(K)$, denote complete transition function, for all, knowledge dependent transforms of $\Omega(T) \rightarrow \Omega(T+1)$

$\lambda\downarrow I$: Denotes action triggered with _perfectly decidable_ information set $I$ and allows for baysian inference, of $\Omega(T+t_{n})$ and F(K), given with
set triggered by $\lambda$

_perfectly decidable_: Information known, at the time of a trigger, is definite information set -> enumarable. (we can exactly tell what information it contains)

---

## Research ideas

### Topic 1: Meta-knowledge problem
__This could concern multiple papers__ \
Unsupervised construction of determinic algorithm for _human usable_ knowledge distilation and its' representations. Given:

1.  Target representation type system.
    - Vector space embedding
    - Knowledge graph embdedding. Existing entity-relation space separation
    - Knowledge sets.
    - Fact-Rules set separable, inferencial boolean logic system
2.  Grammar definition/grammar composition rules, for effective human use, with the focus on typecasting/polymorphism, between mentioned type systems.
3.  Particular context, set of assertions, information on the size of domain.
4.  Environment induced rules and observability
5.  Feedback capabilities, with adequate information on observable state-action-reactivity

With _human usable_ I mean a preposition, stronger, than commonly used term _explainable AI_, or _interpretable models_, by _stronger_ I hope for the for distillation,
of lexical system, which would be easily understandable and could be used, by humans to represent all kinds of relations and theorems, to bring in meaningful insights.

### Topic 2: How can possession of a given fact, given some knowledge boundries, be verified?

In terms of games with computational context, possible way of veryfying the posession of fact k, which has distant consequences ~ highly important
to the outcome of the game, (near boundary values, of the target function) can be infered, by playing a move which, given some parameter set,
would cause move of this fact into the `active zone`, what should result in long time spent on computing all the outcomes lying within a particular distance from the boundary.

> The idea of anti-engine move in chess

:::info
What is lower bound, for a situation in which it would be optimal, for the metaheuristic, to involve a forgetful functor, which would, anonimise possession of this fact.

Assuming, that a `model`, returns time boundaries, which , only time boundries of determinstic search algorithm. 

- How much such `forgetful update` would affect accuracy depending on model topology?



:::

<!-- #todo rewrite to proper notation  -->

### Game example

Let G = (α.K,β.K, $τ$=[1,...,n], T) represent a game, with two players, $\alpha$, $\beta$, discreet variable τ where mod 2 = 0,1 indicates a turn of a player

Using introduced notation, let $\lambda\downarrow I$, be such action of $\alpha$, which for a particular game state $\Omega$ and knowledge dependent
**f-set** F(K), has $\Omega(t_{k+1})$ = $\Omega(t_{k})$ \* F(K) + $\lambda$, state such that for

$\lambda = \Omega(t_{k+1}) - \Omega(t_{k}) * F(K)$

<!-- #todo proper lambda compute, calculate corresponding  -->

<!--
### Meta-learning with observer

Let $O_n$, be ontology, P is defined, on T

Let's consider a formal structure represented, with graph denoted as $G$.
Let $M_{G}$ be the meta structure, which contains all graphs $G$, it doesn't matter f it's a super-graph, or a super set. 

Let, $G$, have ontological properties.
P Observer

 -->

### TODO
- Basic comparison 
- Aggregation of existing research, 
- [Rough Sets](https://en.wikipedia.org/wiki/Rough_set)


