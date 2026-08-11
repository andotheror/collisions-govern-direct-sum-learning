# Collisions Govern Direct-Sum Learning

## Abstract

Direct-sum learning asks how the cost of predicting $r$ outputs at once compares with learning one output. Even for finite classes and zero-one loss on the complete output vector, the answer was unknown. We prove a complete dichotomy. Call a class collision-free if every input assigns distinct labels to all distinct concepts. Every power of a collision-free class reduces exactly to mode estimation, regardless of $r$. Its agnostic and uniform-convergence curves are $\Theta(n^{-1/2})$, one realizable example identifies the full target, adversarial online regret is $\Theta(\sqrt T)$, and its Natarajan, graph, DS, and Littlestone dimensions all equal one. If one collision exists, two concepts agree at one input and differ at another. These two points embed $r$ independently addressable bits in the $r$th power. For every fixed finite class this forces agnostic and uniform rates $\Theta(\min\\\\{1,\sqrt{r/n}\\\\})$, realizable rate $\Theta(\min\\\\{1,r/n\\\\})$, online regret $\Theta(\min\\\\{T,\sqrt{rT}\\\\})$, and realizable mistake complexity $\Theta(r)$. We also show that the Natarajan dimension of every colliding power lies within a factor three of $r$ times the base dimension. The dichotomy subsumes the two examples in a recent rate separation and resolves the finite-class forms of several direct-sum questions. It also disproves a claimed additivity formula for multiclass Littlestone dimension. Powers of the two constant binary functions have dimension one, not $r$.

## Contributions

First, we identify the collision criterion and prove the simultaneous statistical and online dichotomy in Table~. Second, we give explicit bounds in the base-class size, with lower bounds valid for improper learners. Third, if $d=\mathrm{Ndim}(\mathcal C)$ and $\mathcal C$ has a collision, we prove

$$\frac{rd}{3}\leq \mathrm{Ndim}(\mathcal C^r)\leq rd.$$

This closes the degeneration of the prior lower bound when $d\leq2$. Fourth, for heterogeneous products we show that collision-free factors disappear from the batch rates and exactly from Natarajan and DS dimensions. Fifth, we disprove and replace it for finite powers by a one-versus-linear Littlestone dichotomy. All proofs are self-contained in the supplement apart from standard concentration, Assouad, and online optimization facts.

## Keywords

direct-sum learning, multiclass learnability, Natarajan dimension, Littlestone dimension, uniform convergence, online regret, product classes

## Files

- `main.pdf`, `supplement.pdf`
- `main.tex`, `supplement.tex`
- `references.bib`
- `aistats2027.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `supplement.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs
