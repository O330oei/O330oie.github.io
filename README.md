<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.11.1/dist/katex.min.css" integrity="sha384-zB1R0rpPzHqg7Kpt0Aljp8JPLqbXI3bhnPWROx27a9N0Ll6ZP/+DiW/UqRcLbRjq" crossorigin="anonymous">
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.11.1/dist/katex.min.js" integrity="sha384-y23I5Q6l+B6vatafAwxRu/0oK/79VlbSz7Q9aiSZUvyWYIYsd+qj+o24G5ZU2zJz" crossorigin="anonymous"></script>
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.11.1/dist/contrib/auto-render.min.js" integrity="sha384-kWPLUVMOks5AQFrykwIup5lo0m3iMkkHrD0uJ4H5cjeGihAutqP0yW0J6dpFiVkI" crossorigin="anonymous"></script>
<script>
document.addEventListener("DOMContentLoaded", function() {
  console.log("invoked katex...");
  renderMathInElement(document.body, { delimiters : [
  {left: "$$", right: "$$", display: true},
  {left: "!!", right: "!!", display: true},
  {left: "$", right: "$", display: false},
  {left: "\\[", right: "\\]", display: true},
  {left: "%[", right: "%]", display: true},
  ] });
  console.log("finished running katex");
});
</script>



<!-- comment out mathjax
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [ ['$','$'], ["\\(","\\)"] ],
      processEscapes: true
    }
  });
</script>
<script
  type="text/javascript"
  charset="utf-8"
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
> </script>
<script
  type="text/javascript"
  charset="utf-8"
  src="https://vincenttam.github.io/javascripts/MathJaxLocal.js"
> </script>

-->


- [My github](http://github.com/bollu)
- [My math.se profile](https://math.stackexchange.com/users/261373/siddharth-bhat)
- [My resume](resume/main.pdf)
- [My reading list](todo.md)
- email ID: rot13(`fvqqh.qehvq@tznvy.pbz`)

#### Table of contents:

- [Why I like algebra over analysis](#why-i-like-algebra-over-analysis)
- [`using` for cleaner function type typedefs](#using-for-cleaner-function-type-typedefs)
- [A walkway of lanterns (WIP)](#a-walkway-of-laterns)
- [Natural transformations](#natural-transformations)
- [The hilarious commentary by dinosaure in OCaml git](#the-hilarious-commentary-by-dinosaure-in-ocaml-git)
- [How to link against MLIR with CMake](#how-to-link-against-mlir-with-cmake)
- [Energy as triangulaizing state space (WIP)](#energy-as-triangulaizing-state-space)
- [The cutest way to write semidirect products](#the-cutest-way-to-write-semidirect-products)
- [My Favourite APLisms](#my-favourite-aplisms)
- [Proof of chinese remainder theorem on rings (WIP)](#proof-of-chinese-remainder-theorem-on-rings)
- [monic and epic arrows](#monic-and-epic-arrows)
- [The geometry of Lagrange multipliers](#the-geometry-of-lagrange-multipliers)
- [Efficient tree transformations on GPUs (WIP)](#efficient-tree-transformations-on-gpus)
- [Things I wish I knew when I was learning APL](#things-i-wish-i-knew-when-i-was-learning-apl)
- [Every ideal that is maximal wrt. being disjoint from a multiplicative subset is prime](#every-ideal-that-is-maximal-wrt-being-disjoint-from-a-multiplicative-subset-is-prime)
- [Getting started with APL](#getting-started-with-apl)
- [SpaceChem was the best compiler I ever used](#spacechem-was-the-best-compiler-i-ever-used)
- [Mnemonic for Kruskal and Prim](#mnemonic-for-kruskal-and-prim)
- [Legendre transform](#legendre-transform)
- [Cartesian Trees](#cartesian-trees)
- [DFS numbers as a monotone map](#dfs-numbers-as-a-monotone-map)
- [Self attention? not really](#self-attention-not-really)
- [Coarse structures](#coarse-structures)
- [Matroids for greedy algorithms (WIP)](#matroids-for-greedy-algorithms)
- [Grokking Zariski (WIP)](#grokking-zariski)
- [My preferred version of quicksort](#my-preferred-version-of-quicksort)
- [Geometric proof of Cauchy Schwarz inequality](#geometric-proof-of-cauchy-schwarz-inequality)
- [Dataflow analysis using Grobner basis](#dataflow-analysis-using-grobner-basis)
- [Fenwick trees and orbits](#fenwick-trees-and-orbits)
- [Dirichlet inversion (WIP)](#dirichlet-inversion)
- [Incunabulum for the 21st century: Making the J interpreter compile in 2020](#incunabulum-for-the-21st-century-making-the-j-interpreter-compile-in-2020)
- [An example of a sequence whose successive terms get closer together but isn't Cauchy (does not converge)](#an-example-of-a-sequence-whose-successive-terms-get-closer-together-but-isnt-cauchy-does-not-converge)
- [Krylov subspace method](#krylov-subspace-method)
- [Good reference to the Rete pattern matching algorithm](#good-reference-to-the-rete-pattern-matching-algorithm)
- [Leapfrog Integration](#leapfrog-integration)
- [Comparison of forward and reverse mode automatic differentiation](#comparison-of-forward-and-reverse-mode-ad)
- [An invitation to homology and cohomology: Part 1 --- Homology](#an-invitation-to-homology-and-cohomology-part-1--homology)
- [An invitation to homology and cohomology: Part 2 --- Cohomology](#an-invitation-to-homology-and-cohomology-part-2--cohomology)
- [Stuff I learnt in 2019](#stuff-i-learnt-in-2019)
- [A motivation for p-adic analysis](#a-motivation-for-p-adic-analysis)
- [Line of investigation to build physical intuition for semidirect products](#line-of-investigation-to-build-physical-intuition-for-semidirect-products)
- [Topology is really about computation --- part 2](#topology-is-really-about-computation--part-2)
- [Topology is really about computation --- part 1](#topology-is-really-about-computation--part-1)
- [PSLQ algorithm: finding integer relations between reals](#pslq-algorithm-finding-integer-relations-between-reals)
- [Geometric characterization of normal subgroups](#geometric-characterization-of-normal-subgroups)
- [Radical ideals, nilpotents, and reduced rings](#radical-ideals-nilpotents-and-reduced-rings)
- [My disenchantment with abstract interpretation](#my-disenchantment-with-abstract-interpretation)
- [Computing equivalent gate sets using grobner bases](#computing-equivalent-gate-sets-using-grobner-bases)
- [The janus programming language --- Time reversible computation](#the-janus-programming-language--time-reversible-computation)
- [`A = B` --- A book about proofs of combinatorial closed forms (TODO link)](#a--b--a-book-about-proofs-of-combinatorial-closed-forms)
- [Generating `k` bitsets of a given length `n`](#generating-k-bitsets-of-a-given-length-n)
- [Bondi k-calculus](#bondi-k-calculus)
- [Vivado toolchain craziness ](#vivado-toolchain-craziness)
- [What the hell _is_ a Grobner basis? Ideals as rewrite systems](#what-the-hell-is-a-grobner-basis-ideals-as-rewrite-systems)
- [Lie bracket versus torsion](#lie-bracket-versus-torsion)
- [Spatial partitioning data structures in molecular dynamics](#spatial-partitioning-data-structures-in-molecular-dynamics)
- [Vector: Arthur Whitney and text editors](#vector-arthur-whitney-and-text-editors)
- [Discrete random distributions with conditioning in 20 lines of haskell](#discrete-random-distributions-with-conditioning-in-20-lines-of-haskell)
- [Everything you know about word2vec is wrong](#everything-you-know-about-word2vec-is-wrong)
- [Small Haskell MCMC implementation ](#small-haskell-mcmc-implementation)
- [Debugging debug info in GHC ](#debugging-debug-info-in-ghc)
- [GHC LLVM code generator: Switch to unreachable](#ghc-llvm-code-generator-switch-to-unreachable)
- [Concurrency in Haskell](#concurrency-in-haskell)
- [Handy list of differential geometry definitions](#handy-list-of-differential-geometry-definitions)
- [Lazy programs have space leaks, Strict programs have time leaks](#lazy-programs-have-space-leaks-strict-programs-have-time-leaks)
- [Presburger arithmetic can represent the Collatz Conjecture](#presburger-arithmetic-can-represent-the-collatz-conjecture)
- [Using compactness to argue about covers](#using-compactness-to-argue-about-covers)
- [Stephen wolfram's live stream](#stephen-wolframs-live-stream)
- [Japanese Financial Counting system](#japanese-financial-counting-system)
- [`Cleave` as a word has some of the most irregular inflections](#cleave-as-a-word-has-some-of-the-most-irregular-inflections)
- [McCune's single axiom for group theory](#mccunes-single-axiom-for-group-theory)
- [Arthur Whitney: dense code](#arthur-whitney-dense-code)
- [How does one work with arrays in a linear language?](#how-does-one-work-with-arrays-in-a-linear-language)
- [Linear optimisation is the same as linear feasibility checking](#linear-optimisation-is-the-same-as-linear-feasibility-checking)
- [Quantum computation without complex numbers](#quantum-computation-without-complex-numbers)
- [Linguistic fun fact: Comparative Illusion ](#linguistic-fun-fact-comparative-illusion)
- [Stuff I learnt in 2018](content/blog/stuff-i-learnt-this-year-2018.md)
- [Stuff I learnt in 2017](content/blog/papers-I-read-and-loved-in-2017.md)
- [Reading the `structs` library](content/blog/reading-kmett-structs.md)
- [Reading the `machines` library (WIP)](content/blog/machines/reading-kmett-machines.md)
- [Explaining laziness (WIP)](content/blog/laziness-for-c-programmers.md)
- [Explaining STG(WIP)](stg-explained.md)
- [Simplexhc: proc points suck / making GHC an order of magnitude faster](content/blog/ghc-micro-optimisations-or-why-proc-points-suck.md)
- [Simplexhc: dec 2017](this-month-in-simplexhc-dec-2017.md)
- [Simplexhc: oct 29 2017](this-week-in-simpexhc-oct-29-2017.md)
- [Simplexhc: july 2017](this-week-in-simplexhc-07-2017.md)
- [Simplexhc: july 6th 2017](this-week-in-simplexhc-2017-07-06.md)
- [Simplexhc: announcement](content/blog/announcing-simplexhc.md)
- [GSoC 2015 proposal](content/blog/gsoc-vispy.md)
- [GSoC 2015 week 1](content/blog/gsoc-vispy-week-1-and-2.md)
- [GSoC 2015 week 3 and 4](content/blog/gsoc-vispy-week-3-and-4.md)
- [GSoC 2015 week 5](content/blog/gsoc-vispy-week-5.md)
- [GSoC 2015 week 6](content/blog/gsoc-vispy-week-6.md)
- [GSoC 2015 week 7](content/blog/gsoc-vispy-week-7.md)
- [GSoC 2015 final report](content/blog/gsoc-vispy-report-6.md)
- [Distributed Systems](#distributed-systems)
- [Link Dump](#link-dump)



# [Why I like algebra over analysis](#why-i-like-algebra-over-analysis)

Midnight discussions with my room-mate
[Arjun P](https://researchweb.iiit.ac.in/~arjun.p/).

This tries to explore what it is about algebra that I find appealing.

I think the fundamental difference to me comes down to flavour ---
analysis and combinatorial objects feel very "algorithm", while Algebra feels
"data structure".

To expand on the analogy, a proof technique is like an algorithm, while an
algebraic object is like a data structure. The existence of an algebraic object
allows us to "meditate" on the proof technique as a separate object that does
not move through time. This allows us to "get to know" the algebraic object,
independent of how it's used. So, at least for me, I have a richness of 
feeling when it comes to algebra that just doesn't shine through with analysis.
The one exception maybe reading something like "by compactness", which has
been hammered into me by exercises from Munkres :)

Meditating on a proof technique is much harder, since the proof technique
is necessarily intertwined with the problem, unlike a data structure which
to some degree has an independent existence. 


This reminds me of the quote: "“Art is how we decorate space;
Music is how we decorate time.”. I'm not sure how to draw out the
tenuous connection I feel, but it's there.

Arjun comes from a background of combinatorics, and my understanding of his
perspective is that each proof is a technique unto itself. Or, perhaps
instantiating the technique for each proof is difficult enough that abstracting
it out is not useful enough in the first place. 

A good example of a proof technique that got studied on its own right in
combinatorics is the probabilistic method. A more reasonable example is that of
the Pigeonhole principle, which still requires insight to instantiate in
practise.

Not that this does not occur in algebra either, but there is something in
algebra about how just meditating on the definitions. For example,
Whitney trick that got pulled out of the proof of the Whitney embedding
theorem.

To draw an analogy for the haskellers, it's the same joy of being able to write
down the type of a haskell function and know exactly what it does, enough that
a program can automatically derive the function (djinn). The fact that we know
the object well enough that just writing the type down allows us to infer the
_program_, makes it beautiful. There's something very elegant about the
_minimality_ that algebra demands. Indeed, this calls back to another quote:
"perfection is achieved not when there is nothing more to add, but when there
is nothing left to take away".

I'm really glad that this 2 AM discussion allowed me to finally pin down
why I like algebra.

# [`using` for cleaner function type typedefs](#using-for-cleaner-function-type-typedefs)

I've always struggled with remembering the syntax for function type typedefs:

```cpp
typedef RETTY (*FNTYNAME)(ARGTY1, ARGTY2, ..., ARGTYn);
```

we can now use `using` for a far more pleasant syntax:

```cpp
using FNTYNAME = RETTY(ARGTY1, ARGTY2, ..., ARGTYn);
```

which is also intuitive. You write down the "type"
on the right hand side, and give it a name on the left.

This is not strictly the same, since the `typedef` 
`typedefs` `FNTYNAME` to a _function pointer type_, while
the C++ version typedefs the _function type_. I prefer
the latter at any rate, since I dislike the fact
that the usual typedef tends to hide the fact that a
function pointer is some pointer-like-thing.


# [A walkway of lanterns](#a-walkway-of-lanterns)

### Semidirect products

- $(\alpha \equiv \{ a, b, \dots\}, +, 0)$
- $(\omega \equiv \{ X, Y, \dots\}, \times, 1)$
- $\cdot ~: ~\omega \rightarrow Automorphisms(\alpha)$
 
--- 
- [How to twist pointers without breaking them](https://www.cse.iitk.ac.in/users/ppk/research/publication/Conference/2016-09-22-How-to-twist-pointers.pdf)

- rotations: $\mathbb Z 5$
- reflection: $\mathbb Z 2$

- $D_5 = \mathbb Z5 \rtimes \mathbb Z2$
--- 

\begin{align*}
\begin{bmatrix}
1 & 0 \\
a & X
\end{bmatrix}
\begin{bmatrix}
1 & 0 \\
b & Y
\end{bmatrix}
=  \begin{bmatrix}
1 & 0 \\
a + X \cdot b & XY
\end{bmatrix}
\end{align*}

- $(Y \mapsto b) \xrightarrow{act} (X \mapsto a)$

- $XY \mapsto a + X \cdot b$


### A walkway of lanterns

- Imagine $\mathbb Z$ as a long walkway. you start at 0. You are but a poor lamp lighter.
- Where are the lamps? At each $i \in \mathbb Z$, you have a lamp that is either on, or off. So you have $\mathbb Z2$.

- $L \equiv \mathbb Z \rightarrow \mathbb Z2$ is our space of lanterns. You can act on this space by either moving using $\mathbb Z$, or toggling a lamp using $\mathbb Z2$. $\mathbb Z2^{\mathbb Z} \rtimes \mathbb Z$

- $g = (lights:\langle-1, 0, 1\rangle,  loc:10)$
- $move_3: (lights: \langle \rangle, loc: 3)$
- $move_3 \cdot g =  (lights:\langle-1, 0, 1\rangle,  loc:13)$
- $togglex = (lights:\langle 0, 2 \rangle, loc: 0)$
- $togglex \cdot g = (lights: \langle -1, 0, 1, 13, 15 \rangle, loc:13)$
- $toggley = (lights: \langle -13, -12 \rangle, loc:0)$
- $toggley\cdot g= (lights:\langle -1 \rangle, loc:13)$

### Wreath products


### This is automata theoretic? :O
- cascade finite automata.

### Krohn-rhodes, AKA how to model Freudian psychoanalysis using Lagrangians over semigroups.




# [Natural transformations](#natural-transformations)

![natural-transformations](static/natural-transformation.png)

I don't find people who draw "all three parts" of the natural transformation:
the catories $C$, $FC$, and $GC$, and then show the relationship between
them, so I made this for my own reference.


# [The hilarious commentary by dinosaure in OCaml git](#the-hilarious-commentary-by-dinosaure-in-ocaml-git)

the [Ocaml-git](https://github.com/mirage/ocaml-git/) project is a
re-implementation of `git` in `OCaml`. It's well-written, and I was
walking through the codebase, when I found absolutely amazing, hilarious,
and deep comments from `dinosaure`. I really enjoyed reading through the
codebase, and the existence of these comments made it more humane to read.
I don't know who `dinosaure` is, but I'm really glad they wrote the comments
they did, it really made my day.

##### The one that takes a stab at Haskell for fun

```
(* XXX(dinosaure): ...we can fix this detail but
I'm lazy like haskell. TODO! *)
```
 
##### The academic one that broken-links to a paper

```
(* XXX(dinosaure): see this paper
https://github.com/ocamllabs/papers/blob/master/irmin/2014.08.matthieu/rapport.pdf *)
```

##### The one about the frustrations of bug-hunting

```
(* XXX(dinosaure): [~chunked:false] is mandatory, I don't want to explain
why (I lost one day to find this bug) but believe me. *)
```

##### The one about a potential heisenbug 

```
(* XXX(dinosaure): if, one day, we find a bug about the serialization of the
IDX file, may be it's about this function (stable/unstable sort). *)
``` 

##### The requisite comment in french for an OCaml project

```
(* XXX(dinosaure): bon ici, c'est une note compliqué, j'ai mis 2 jours
à fixer le bug. Donc je l'explique en français, c'est plus simple.
En gros, [Helper.MakeDecoder] utilise ce buffer comme buffer interne
pour gérer les alterations. Ce qui ce passe, c'est que dans la
fonction [refill], il s'agit de compléter à partir d'un [input]
(typiquement [zl]) le buffer interne. C'est finalement un
__mauvais__ jeu entre un [Cstruct.t] et un [Bigarray].
Il s'agit de connaître la véritable taille du [Bigarray] et de
rajouter avec [blit] le contenu de l'[input] si la taille du
[Bigarray] (et pas du [Cstruct]) est suffisante.
Avant, cette modification, [zl], [de] et [io] partagaient le même
[Bigarray] découpé (avec [Cstruct]) en 3. Donc, dans le
[MakeDecoder], [refill] considérait (pour des gros fichiers faisant
plus de 0x8000 bytes) que après [de], nous avions encore de la
place - et dans ce cas, nous avions [io].
Ainsi, on [blit]ait [zl] dans [de+sizeof(de) == io], et finalement,
on se retrouvait à essayer de décompresser ce que nous avions
décompressé. (YOLO).
Donc, on considère maintenant [de] comme un [Cstruct.t] et un
[Bigarray] physiquement différent pour éviter ce problème.
Cependant, il faudrait continuer à introspecter car j'ai
l'intuition que pour un fichier plus gros que [2 * 0x8000], on
devrait avoir un problème. Donc TODO. *)
```

###### The deep one

```
(* XXX(dinosaure): at the end, we don't care if we lost something. *)
```

# [How to link against MLIR with CMake](#how-to-link-against-mlir-with-cmake)

Since `MLIR` hasn't setup the nice tooling that LLVM has around `CMake`
as far as I can tell, one needs to actually _know_ `CMake` to link against
`MLIR`. However, as is well known, `CMake` incantations are handed down
by preists who spend the better part of their lives studying the tome
that is the CMake manual. I, an unlucky soul had to go on this adventure,
and I hope to spare you the trouble.

I wished to link against a static library build of MLIR. The secret
lies in the `find_library` call:

```
#If the variable has been set by -DMLIR_INCLUDE_PATH, then keep it. 
#Otherwise fallback to the environment variable $MLIR_INCLUDE_PATH.
#if neither, then *shrug*.
IF(NOT MLIR_INCLUDE_PATH)
    set (MLIR_INCLUDE_PATH $ENV{MLIR_INCLUDE_PATH})
endif()

#Resolve for:
#- a library target called `MLIRAnalysis`
#- asking to link against `libMLIAnalysis.a`
#- using the variable MLIR_INCLUDE_PATH which as we saw before
#  is either an environment variable or a cmake option
target_include_directories(languagemodels PRIVATE ${MLIR_INCLUDE_PATH})
```

I cribbed the actual things to link against from the path 
[`mlir/examples/Toy/Ch2/CMakeLists.txt`](https://github.com/llvm/llvm-project/blob/master/mlir/examples/toy/Ch2/CMakeLists.txt)
which helpfully lists MLIR things it needs to link against.

The full `CMakeLists` is here:

```
cmake_minimum_required(VERSION 3.5)
project(languagemodels)

set(CMAKE_CXX_STANDARD 14)

# I don't want to use find_package since I want proper control over where my LLVM comes from.
# find_package(LLVM REQUIRED)

add_executable(languagemodels
        rnn.cpp codegenc.h lang.h codegenmlir.h)

# Attempt to take these as command line arguments. IF that fails,
# lookup environment.
IF(NOT MLIR_INCLUDE_PATH)
    set (MLIR_INCLUDE_PATH $ENV{MLIR_INCLUDE_PATH})
endif()

IF(NOT MLIR_LIBRARY_PATH)
    set (MLIR_LIBRARY_PATH $ENV{MLIR_LIBRARY_PATH})
endif()

target_include_directories(languagemodels PRIVATE ${MLIR_INCLUDE_PATH})
find_library(MLIRAnalysis MLIRAnalysis ${MLIR_LIBRARY_PATH})
find_library(MLIRIR MLIRIR ${MLIR_LIBRARY_PATH})
find_library(MLIRParser MLIRParser ${MLIR_LIBRARY_PATH})
find_library(MLIRSideEffects MLIRSideEffects ${MLIR_LIBRARY_PATH})
find_library(MLIRTransforms MLIRTransforms ${MLIR_LIBRARY_PATH})
find_library(LLVMCore LLVMCore ${MLIR_LIBRARY_PATH})
find_library(LLVMSupport LLVMSupport ${MLIR_LIBRARY_PATH})

# debugging to check if it's been set properly
message(MLIR_INCLUDE_PATH ${MLIR_INCLUDE_PATH})
message(MLIR_LIBRARY_PATH ${MLIR_LIBRARY_PATH})
message(MLIRAnalysis ${MLIRAnalysis})

target_link_libraries(languagemodels
        ${MLIRAnalysis}
        ${MLIRIR}
        ${MLIRParser}
        ${MLIRSideEffects}
        ${MLIRTransforms}
        ${LLVMCore}
        ${LLVMSupport})
```



# [Energy as triangulaizing state space](#energy-as-triangulaizing-state-space)
This comes from
[The wild book](https://en.wikipedia.org/wiki/John_Rhodes_(mathematician)#Books_and_Monographs)
which I anticipate I'll be posting more of in the coming weeks.

#### Experiments

Let an experiment be a tuple of the phase space $X$, action space $A$,
and an action of the actions onto the phase space
$\curverightarrow: A \times X \rightarrow X$. We will write
$x' = a \curverightarrow x$ to denote the new state of the system
$x$. So the experiment $E$ is the data
$E \equiv (X, A, \curverightarrow : A \times X \rightarrow X)$.

#### Coordinate systems.

The existence of the action $\curverightarrow$ allows us to
write the evolution of the system recursively:

$x_{t+1} = a \rightarrow x_t$.

However, to understand the final state $x_{t+1}$, we need to essentially
"run the recursion", which does not permit us to _understand the
experiment_. 

What we really need is the ability to "unroll" the loop. To quote:

> Informally, understanding an experiment $E$ means 
> introducing coordinates into phase space of $E$ which are in triangular form
> under the action of the inputs of $E$.

#### Conservation laws as triangular form

We identify certain interesting invariants of a system by two criteria:

1. The parameter $Q(t)$ determines some obviously important aspects of
   the system. That is, there is a deterministic function $M(Q(t))$ which
   maps $Q(t)$ to "measure" some internal state of the system.

2. If the values of such a  parameter $Q$ is known at time $t_0$ (denoted $Q(t_0)$)
    and it is also known what inputs are presented to the
    system from time $t$ to time $t + \epsilon$
    (denoted $I[t_0, t_0 + \epsilon]$), then the new value of $Q$ is a
    deterministic function of $Q(t_0)$ and $I[t_0, t_0+ \epsilon]$.


Such parameters allow us to understand a system, since they are deterministic
parameters of the evolution of the system, while also provding a way to 
measure some internal state of the system using $M$.

For example, consider a system $x$ with an energy function $e(x)$. If we
perform an action $a$ on the system $x$, then we can predict the action
$e(x' = a \curvearrowright x)$ given just $e(x)$ and $a$ --- here,
$(x' = a \curverightarrow x)$ is the action of the system $a$ on $x$.

> In general, conservation principles give a first coordinate
> of a triangularization. In the main a large part of physics can be viewed as
> discovering and introducing functions $e$ of the states $q$ of the
> system such that under action $a$, $e(a \curverightarrow q)$ depends 
> only on $e(q)$ and $a$, and **not** on $q$.


#### Theory: semidirect and wreath products

- For semidirect products, I refer you to 
    [the cutest way to write semidirect products](#the-cutest-way-to-write-semidirect-products)
    [Line of investigation to build physical intuition for semidirect products](#line-of-investigation-to-build-physical-intuition-for-semidirect-products).

A wreath product

#### Symmetries as triangular form

> We first heuristically indicate the construction involved in going from the
> group of symmetries to the triangularization, and then precisely write it out
> in all pedantic detail.

Let an experiment be $ E \equiv (X, A, \curverightarrow) $. Then we define $\Pi$
is a _symmetry_ of $E$ iff:

1. $\Pi: X \rightarrow X$ is a permutation of $X$.

2. $\Pi$ commutes with the action of each $a$: 
       $ \Pi(a \curverightarrow x) = a \curverightarrow \Pi(x) $.

We say that the theory $E$ is _transitive_ (in the action sense) if for
all $x_1, x_2 \in X, x_1 \neq x_2$, there exists $a_1, a_2, \dots a_n$ 
such that $ x_2 = a_n \curverightarrow \dots (a_1 \curverightarrow x_1) $.

Facts of the symmetries of a system:

1. We know that the symmetries of a theory $E$ form a group.

2. If $E$ is transitive, then each symmetry $\Pi$ is a regular permutation
   --- If there exists an $x$ such that $\Pi(x_f) = x_f$ (a fixed point), then
   this implies that $\Pi(x) = x$ for _all_ $x$.

3. Let the action split $X$ into disjoint orbits $O_1, O_2, \dots O_k$ from whom
   we choose representatives $x_1 \in O_1, x_2 \in O_2, \dots x_k \in O_k$.
   Then, if $E$ is transitive, there is _exactly one_ action that sends a
   particular $x_i$ to a particular $x_j$. So, on fixing _one component_
   of an action, we fix _all components_.

To show that this gives rise to a triangulation, we first construct
a semigroup of the actions of the experiment:
$S(E) \equiv \{ a_1 \dots a_n : n \geq 1 \text{~and~} a_i \in A \}$.

Now, let $G = Sym(E)$, the full symmetry group of $E$. One can apparently
express the symmetry group in terms of:

!! (X, S) \leq (G, G)  \wr (\{ O_1, O_2, \dots O_k\}, T) !!

# [The cutest way to write semidirect products](#the-cutest-way-to-write-semidirect-products)

Given two monoids $(M, +, 0_M)$ and $(N, \times, 1_N)$, and a 
homomorphism $\phi: N \rightarrow End(M)$, where $End(M)$
is the endomorphism group of $M$. We will notate $\phi(n)(m)$ as $n \cdot m \in M$.

Now the semidirect product $M \ltimes_\phi N$ is the set $M \times N$ equipped
with the multiplication rule:
- $(m, n) (m', n') = (m + n \cdot m', nn')$

This can also be written down as:

!!
\begin{bmatrix}
1 & 0 \\
m & n \end{bmatrix}
\begin{bmatrix} 1 & 0
\\ m' & n'
\end{bmatrix} = 
\begin{bmatrix} 1 & 0 \\
m + n \cdot m' & n \times n' \end{bmatrix}
!!

This way of writing down semidirect products as matrices makes many things
immediately clear:

- The semidirect product is some kind of "shear" transform, since that's 
  what a shear transformation looks like, matrix-wise.

- The resulting monoid $M \ltimes_{\phi} N$ has identity $(0_M, 1_N)$, 
  since for the matrix to be identity, we need the 2nd row to be $(0, 1)$.

- The inverse operation if $(M, N)$ were groups would have to be such that

!!
\begin{bmatrix} 1 & 0 \\ m + n \cdot m' & n \times n' \end{bmatrix} = 
\begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}
!!

Hence:
- $nn' = 1$ implies that $n' = 1/n$.
- $m + n m' = 0$ implies that $m' = -m/n$.

which is indeed the right expression for the inverse.



# [My Favourite APLisms](#my-favourite-aplisms)

#### identity matrix
```
n←3 ⋄ id ← n n ⍴(1,n⍴0) ⋄ id
```

This relies heavily on `⍴` replicating its arguments.


#### histogram
``` 
xs←(1 1 3 3 3 6) ⋄ n←(⌈/xs)⍴0 ⋄ n[xs]+←1 ⋄ n
```

The use of `n[x] +←1` will stably write `+1` as many times as there are repeated
indexes in `xs`.

# [Proof of chinese remainder theorem on rings](#proof-of-chinese-remainder-theorem-on-rings)

#### General operations on ideals
We have at our hands a commutative ring $R$, and we wish to study the ideal
structure on the ring. In particular, we can combine ideals in the following
ways:

1. $I + J \equiv \{ i + j : \forall i \in I, j \in J \}$
2. $I \cap J \equiv \{ x : \forall x \in I \land x \in J \}$
3. $IJ \equiv \{ ij : \forall i \in I \land j \in J \}$ (**wrong!**)

Is the third one really right? How do we prove that:
$\forall i_1, i_2 \in I, j_1, j_2 \in J, \exists i_3 \in I, j_3 \in J$ such that
$i_1 j_2 + i_2 j_2 = i_3 j_3$? 

Indeed, we can't do so in general! For
a quick counter-example, consider the ring $\mathbb Z[X, Y]$ and the ideals
$I \equiv \langle X \rangle$, $J \equiv \langle Y \rangle$. Now, note
that $XY  + X^2Y^2$ cannot be written as the product of a power of $X$
and a power of $Y$. 

So, the _correct definition_ is to in fact _generate an ideal_ from all
elements of the form $ij$. So #3 should be:

3.  $IJ \equiv \{ \sum_k i_k j_k : \forall i_k \in I \land j_k \in J \}$ (**right!**)


#### Specializing ideal operations to $\mathbb Z$

Let $I \equiv \langle 12 \rangle, J \equiv \langle 20 \rangle$.

- $I + J \equiv \{ 12k + 20l : k, l \in \mathbb Z\} = \langle gcd(12, 20) \rangle = \langle 4 \rangle
- $IJ \equiv \langle\{ (12 k)(20 l) : k, l \in \mathbb Z \}\rangle = $
- $I \cap J \equiv ??$

Great. Now, one can conjecture the relation:
- $(I + J)(I \cap J) = IJ$

by the following chain of inference:
- $(I + J)(I \cap J) = I(I \cap J) + J(I \cap J) \subseteq IJ + JI = IJ$.

#### References

- [I learnt the material from this course on commutative algebra from IIT bombay](https://www.youtube.com/watch?v=YxyxP894MLk).


# [monic and epic arrows](#monic-and-epic-arrows)

This is trivial, I'm surprised it took me _this long_ to internalize this fact.

When we convert a poset $(X, \leq)$ into a category, we stipulate that
$x \rightarrow y \iff x \leq y$.

If we now consider the category $Set$ of sets and functions between sets,
and arrow $A \xrightarrow{f} B$ is a function from $A$ to $B$. If $f$ is 
monic, then we know that $|A| = |Im(f)| \leq |B|$. That is, a monic arrow
behaves a lot like a poset arrow!

Similarly, an epic arrow behaves a lot like the arrow in the inverse poset.
I wonder if quite a lot of category theoretic diagrams are clarified by thinking
of monic and epic directly in terms of controlling sizes.

# [The geometry of Lagrange multipliers](#the-geometry-of-lagrange-multipliers)
If we want to minise a function $f(x)$ subject to the constraints $g(x) = c$,
one uses the method of lagrange multipliers. The idea is to consider a new
function $L(x, \lambda) = f(x) + \lambda (c - g(x))$. Now, if one has a local maxima
$(x^\star, y^\star)$, then the conditions:

1. $\frac{\partial L}{\partial x} = 0$: $f'(x^\star) - \lambda g'(x^\star) = 0$.
2. $\frac{\partial L}{\partial \lambda} = 0$: $g(x^\star) = c$.

Equation (2) is sensible: we want our optima to satisfy the constraint that
we had originally imposed. What is Equation (1) trying to say?

Let us say that we are at an $(x_0)$ which
is a feasible point ($g(x_0) = c$).

We are interested in wiggling 
$(x_0) \xrightarrow{wiggle} (x_0 + \epsilon) \equiv x_1$.
such that:

-  $x_1$ is still feasible: $g(x_1) = c$
- $x_1$ is an improvement: $f(x_1) > f(x_0)$.

- We need $f$ to increase in the direction of $\epsilon$. So, 
  __we need $\epsilon$ to have positive component along $f'(x)$__. That is,
  $f'(x) \cdot \epsilon > 0$.

- We need $g(x_1) = c$. But notice that $g(x_0) = c$. So, we need $g(x)$
  to __remain constant along $\epsilon$__. That means that $\epsilon$ should
  be __perpendicular to the gradient of $g$__: $g'(x) \cdot \epsilon = 0$.


Now, if $f'(x_0) \lvert \lvert g'(x_0)$ (parallel to),
then we have $f'(x_0) \lbot levelset(g(x_0))$ (perpendicular to).

- We want to move along $f'(x_0)$ to improve $f(x_0)$.
- We want to move _perpendicular_ $g'(x_0)$ to keep $g(x_0) = c$.

Clearly if $f'(x_0) || g'(x_0)$ these two conditions contradict each other, and so
we are at a local maxmia.

On the other hand, if it is not true that $f'(x_0) || g'(x_0)$, then there will
be _some_ component of $f'$ to be had by moving along $levelset(g(x_0))$.


# [Efficient tree transformations on GPUs](#efficient-tree-transformations-on-gpus)

All material lifted straight from [Aaron Hsu's PhD thesis](TODO). I'll be converting
APL notation to C++-like notation.
[Source code link to my implementation is here](TODO)


#### Tree repsentation as multi-dimensional ragged nested arrays

We're interested in this tree:
```
      ∘
┌──┬──┴────┐
a  b       c
│ ┌┴┐  ┌───┼───┐
p q r  s   t   u
  │    │   |  
  │   ┌┴┐ ┌┴┐
  v   w x y z
```

I'll be writing APL commands in front of a `$` to mimic bash, and I'll
write some arrays as multi-line. To run them, collapse them into a single
line. The `ast` object is represented in memory as:
```
$ ast ← ('∘'
           ('a' ('p'))
           ('b' 
             ('q' ('v'))
             ('r'))
           ('c' 
             ('s' ('w' 'x'))
             ('t' ('y' 'z'))
             ('u')))
$ ]disp ast
┌→┬──┬────────┬───────────────────┐
│∘│ap│┌→┬──┬─┐│┌→┬──────┬──────┬─┐│
│ │  ││b│qv│r│││c│┌→┬──┐│┌→┬──┐│u││
│ │  │└─┴─→┴─┘││ ││s│wx│││t│yz││ ││
│ │  │        ││ │└─┴─→┘│└─┴─→┘│ ││
│ │  │        │└─┴─────→┴─────→┴─┘│
└─┴─→┴───────→┴──────────────────→┘
```

Here's how read the array representation. Look at the top level of the tree.
we have a root node with three children:

```
      ∘
┌──┬──┴────┐
a  b       c

┌→┬──┬────────┬─────────────┐
│∘│  │        │             │
│ │ a│   b    │     c       │
│ │  │        │             │
└─┴─→┴───────→┴────────────→┘
```

With the first `∘` being the root node, and the three adjacent cells
being the children.

Next, we look at how `x` is represented. This is predictably recursive. Let's
see the subtree under `x`:

```
      ∘
┌──┬──┴────┐
a  b       c
│ 
p 

┌→┬──┬────────┬─────────────┐
│∘│ap│        │             │
│ │  │  b     │   c         │
│ │  │        │             │
└─┴─→┴───────→┴────────────→┘

```

Similarly for `y`:

```
      ∘
┌──┬──┴────┐
a  b       c
│ ┌┴┐ 
p q r  

┌→┬──┬────────┬─────────────┐
│∘│ap│┌→┬──┬─┐│             │
│ │  ││b│q │r││   c         │
│ │  │└─┴─→┴─┘│             │
└─┴─→┴───────→┴────────────→┘
```

And so on, leading to the final representation:

```
      ∘
┌──┬──┴────┐
a  b       c
│ ┌┴┐  ┌───┼───┐
p q r  s   t   u
  │    │   |  
  │   ┌┴┐ ┌┴┐
  v   w x y z
┌→┬──┬────────┬───────────────────┐
│∘│ap│┌→┬──┬─┐│┌→┬──────┬──────┬─┐│
│ │  ││b│qv│r│││c│┌→┬──┐│┌→┬──┐│u││
│ │  │└─┴─→┴─┘││ ││s│wx│││t│yz││ ││
│ │  │        ││ │└─┴─→┘│└─┴─→┘│ ││
│ │  │        │└─┴─────→┴─────→┴─┘│
└─┴─→┴───────→┴──────────────────→┘
```


Note that for this representation to work, we need to be able to:

- nest arrays inside arrays.
- have subarrays of different sizes (ragged arrays)
- of different _nesting depths_ --- so it's really not even an array?

I don't understand the memory layout of this, to be honest. I feel like to
represent this in memory would still rely on pointer-chasing, since we need
to box all the arrays. This is possibly optimised by APL to not be too bad.

#### The depth vector representation

```
      ∘             0
┌──┬──┴────┐
a  b       c        1
│ ┌┴┐  ┌───┼───┐
p q r  s   t   u    2
  │    │   |  
  │   ┌┴┐ ┌┴┐
  v   w x y z       3
```

If we visit this tree and record depths in pre-order `(node left right)`, we
arrive at the list:

```
(∘:0 
  (a:1 (p:2)) (b:1 (q:2 (v:3)) (r:2))
  (c:1 (s:2 (w:3 x:3)) (t:2 (y:3 z:3)) (u:2)))
```

formatted as:

```
(∘:0
  (a:1 
    (p:2))
  (b:1 
    (q:2 (v:3))
    (r:2)
  )
  (c:1 (s:2 (w:3 x:3))
       (t:2 (y:3 z:3))
       (u:2))
)
```

This linearlized is the list:

```
    (∘ a p b q v r c s w x t y z u)
d ← (0 1 2 1 2 3 2 1 2 3 3 2 3 3 2)

      ∘             0
┌──┬──┴────┐
a  b       c        1
│ ┌┴┐  ┌───┼───┐
p q r  s   t   u    2
  │    │   |  
  │   ┌┴┐ ┌┴┐
  v   w x y z       3
```


To convert the `ast` object into a depth vector representation, we can
use the following call:

```
$ ast ← ('∘' ('a' ('p')) ('b' ('q' ('v')) ('r')) ('c' ('s' ('w' 'x')) ('t' ('y' 'z')) ('u')))
$ d ← ∊0{(⊢,(⍺+1)∇⊣)/⌽⍺,1↓⍵}ast
0 1 2 1 2 3 2 1 2 3 3 2 3 3 2
```

Let's break this down:

TODO

#### Inverted tables

We represent data associated with our nodes as follows:

```
$ data ← ⍪ ¨d(15⍴'T')(↑15⍴⊂'n.')
$ ]disp data
┌→┬─┬──┐
│0│T│n.│
│1│T│n.│
│2│T│n.│
│1│T│n.│
│2│T│n.│
│3│T│n.│
│2│T│n.│
│1│T│n.│
│2│T│n.│
│3│T│n.│
│4│T│n.│
│2│T│n.│
│3│T│n.│
│4│T│n.│
│2↓T↓n.↓
└→┴→┴─→┘
```

This is the same thing as a 
[structure of arrays (SOA) representation](https://en.wikipedia.org/wiki/AoS_and_SoA#Structure_of_Arrays),
where each array of information (eg, the depth at `data[1]`, the `T`
information at `data[2]`) are each _arrays_ which can be accessed well on SIMD
instructions.

#### AST representation

TODO

#### Path matrices

We want information of how to go up and down the tree in ideally constant time.
We store this information in what is known as a _path matrix_.

For our recurring example, the path matrix is:

```
∘ a p b q v r c s w x t y z u | preorder traversal
──────────────────────────────────────────────────
∘ ∘ ∘ ∘ ∘ ∘ ∘ ∘ ∘ ∘ ∘ ∘ ∘ ∘ ∘ | depth=0
- a a b b b b c c c c c c c c | depth=1 
- - p - q q r - s s s t t t u | depth=2
- - - - - v - - - w x - y z - | depth=3

      ∘             0
┌──┬──┴────┐
a  b       c        1
│ ┌┴┐  ┌───┼───┐
p q r  s   t   u    2
  │    │   |  
  │   ┌┴┐ ┌┴┐
  v   w x y z       3
```

To efficiently compute this, we first replace every value in
our tree with its preorder traversal visit time. This changes
the tree to:

```
              ∘:0                               0
┌──────────┬──┴─────────────────┐
a:1        b:3                 c:7              1
│      ┌───┴───┐     ┌──────────┼───────┐
p:2    q:4     r:6   s:8        t:11    u:14    2
       │             │          │
       │          ┌──┴──┐     ┌─┴───┐
       v:5        w:9   x:10  y:12  z:13        3
```

The values we store in the tree are the integers. The old labels
are represented for clarity.

The path matrix for this tree is:

```
0  1  2  3  4  5  6  7  8  9 10 11 12 13 14  | preorder traversal
────────────────────────────────────────────────────────────
0  0  0  0  0  0  0  0  0  0  0  0  0  0  0  | depth=0
-  1  1  3  3  3  3  7  7  7  7  7  7  7  7  | depth=1
-  -  2  -  4  4  6  -  8  8  8 11 11 11 14  | depth=2
-  -  -  -  -  5  -  -  -  9 10  - 12 13  -  | depth=3

              ∘:0                               0
┌──────────┬──┴─────────────────┐
a:1        b:3                 c:7              1
│      ┌───┴───┐     ┌──────────┼───────┐
p:2    q:4     r:6   s:8        t:11    u:14    2
       │             │          │
       │          ┌──┴──┐     ┌─┴───┐
       v:5        w:9   x:10  y:12  z:13        3
```

#### Rendering the depth information in 2D

We use the incantation:

```
$ d ← (0 1 2 1 2 3 2 1 2 3 3 2 3 3 2)
$ ((⍳≢d)@(d,¨⍳≢d)) ((⌈/d) (≢d))⍴'-'
0 - - - - - - - - -  -  -  -  -  -
- 1 - 3 - - - 7 - -  -  -  -  -  -
- - 2 - 4 - 6 - 8 -  - 11  -  - 14
- - - - - 5 - - - 9  -  - 12  -  -
- - - - - - - - - - 10  -  - 13  -
```

Let's break this down (the symbol ` ` means a lamp, for commenting/illumination)


```
$ ⍳ 3 ⍝ iota: make a list of n elements:.
1 2 3
```

```
$ d
0 1 2 1 2 3 2 1 2 3 4 2 3 4 2

$ ≢d ⍝ tally: ≢`. count no. of elements in d: 
15
```

```
⍳≢d  ⍝ list of elements of len (no. of elements in d).
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15
```

```
$ ]disp (1 2 3),(4 5 6) ⍝ ,:concatenate
┌→────┬─────┐
│1 2 3│4 5 6│
└~───→┴~───→┘
```

```
]disp (1 2 3) ,¨ (4 5 6)
┌→──┬───┬───┐
│1 4│2 5│3 6│
└~─→┴~─→┴~─→┘
```

The use of `¨` needs some explanation. `¨` is a higher order function which
takes a function and makes it a mapped version of the original function.
So, `,¨` is a function which attemps to map the concatenation operator.
Now, given two arrays `(1 2 3)`
and `(4 5 6)`, `(1 2 3) ,¨ 4 5 6` attemps to run `,` on each pair 
`1 and 4`, `2 and 5`, `3 and 6`. This gives us tuples `((1 4) (2 5) (3 6))`.
So, for our purposes, `zip ← ,¨`.

```
]disp (d,¨⍳≢d) ⍝ zip d with [1..len d].
┌→──┬───┬───┬───┬───┬───┬───┬───┬───┬───┬────┬────┬────┬────┬────┐
│0 0│1 1│2 2│1 3│2 4│3 5│2 6│1 7│2 8│3 9│4 10│2 11│3 12│4 13│2 14│
└~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~──→┴~──→┴~──→┴~──→┴~──→┘
```

```
$ ((⌈/d) (≢d))⍴'-' ⍝ array of dim (max val in d) x (no. of elem in d)
---------------
---------------
---------------
---------------
```

- `⌈` is the maximum operator and `/` is the fold operator, so 
  `⌈/d` finds the maximum in `d`. Recall that `(≢d)` find the no. of
   elements in `d`. `⍴` reshapes an array to the desired size. We pass it
   a `1x1` array containing only `-`, which gets reshaped into a
   `(⌈/d) x (≢d)` sizes array of `-` symbols.


TODO: explain @ and its use

#### Creating the path matrix

```
$ ⎕IO ← 0 ⍝ (inform APL that we wish to use 0-indexing.) 
$ d ← (0 1 2 1 2 3 2 1 2 3 3 2 3 3 2)
$ PM ← ⌈\((⍳≢d)@(d,¨⍳≢d))(((⌈/d+1)(≢d))⍴0)

0 0 0 0 0 0 0 0 0 0  0  0  0  0  0
0 1 1 3 3 3 3 7 7 7  7  7  7  7  7
0 0 2 2 4 4 6 6 8 8  8 11 11 11 14
0 0 0 0 0 5 5 5 5 9 10 10 12 13 13

      0               0
┌──┬──┴───────┐
1  3          7       1
│ ┌┴┐  ┌──────┼───┐
2 4 6  8     11   14  2
  │    │      |
  │   ┌┴─┐   ┌┴──┐
  5   9  10  12  13   3
```

The incantation can be broken down into:


- `(((⌈/d+1)(≢d))⍴0)` is used to create a `max(d+1)x|d|` dimension array of zeros.
   Here, the rows define depths, and the columns correspond to tree nodes
   which for us are their preorder indexes.

```
$ grid←(⌈/d+1) (≢d) ⍴ 0
$ grid
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
```

- `((d ,¨ ⍳≢d))` creates an array of pairs `(depth, preindex)`. We will use
  this to fill index `(d, pi)` with the value `pi`. 

```
$ writeixs ← (d,¨⍳≢d)
$ ]disp writeixs
┌→──┬───┬───┬───┬───┬───┬───┬───┬───┬───┬────┬────┬────┬────┬────┐
│0 0│1 1│2 2│1 3│2 4│3 5│2 6│1 7│2 8│3 9│3 10│2 11│3 12│3 13│2 14│
└~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~──→┴~──→┴~──→┴~──→┴~──→┘
```

- `ixgrid ← ((⍳≢d)@writeixs) grid` rewrites at index `writeixs[i]` the value (`(i≢d)[i]`).
  
```
$ ixgrid ← ((⍳≢d)@writeixs) grid
$ ixgrid
0 0 0 0 0 0 0 0 0 0  0  0  0  0  0
0 1 0 3 0 0 0 7 0 0  0  0  0  0  0
0 0 2 0 4 0 6 0 8 0  0 11  0  0 14
0 0 0 0 0 5 0 0 0 9 10  0 12 13  0
```

- Finally, `⌈` is the maximum operator, and `\` is the [prefix scan]() operator,
  so `⌈\ixgrid` creates a prefix scan of the above grid to give us our
  final path matrix:

```
$ PM ← ⌈\ixgrid
$ PM
0 0 0 0 0 0 0 0 0 0  0  0  0  0  0
0 1 1 3 3 3 3 7 7 7  7  7  7  7  7
0 0 2 2 4 4 6 6 8 8  8 11 11 11 14
0 0 0 0 0 5 5 5 5 9 10 10 12 13 13
```

#### Using the path matrix:  distance of a node from every other node.

Note that the maximum distance between two nodes is to climb
all the way to the top node, and then climb down:

```
dmax ← depth(a) + depth(b)
```

If we know the lowest common ancestor of two nodes,
then the distance of one node to another is:

```
dcorrect ← dist(a, lca(a, b)) + dist(b, lca(a, b))
```

So, we can compute the depth as:

```
dcorrect ← dist(a, lca(a, b)) + dist(lca(a, b), b)
 = dist(a, lca(a, b)) + depth(lca(a, b)) + 
   dist(b, lca(a, b)) + depth(lca(a, b)) +
   -2 * depth(lca(a, b))
 = depth(a) +
   depth(b) +
   -2 * depth (lca(a, b))
```

[TODO: picture]
[TODO: finish writing this]


#### Parent vector representation

A parent vector is a vector of length `n` where `Parent[i]` denotes an 
index into `Parent`. Hence, the following condition will return 1
if V is a parent vector.

For example, for our given example, here is the parent vector:

```
d ← (0  1  2  1  2  3  2  1  2  3  3  2  3  3  2) │ depths
    (∘  a  p  b  q  v  r  c  s  w  x  t  y  z  u) │ values
p ← (∘  ∘  a  ∘  b  q  b  ∘  c  s  s  c  t  t  c) │ parents
    (0  1  2  3  4  5  6  7  8  9 10 11 12 13 14) | indexes     
P ← (0  0  1  0  3  4  3  0  7  8  8  7 11 11  7) │ parent indices



              ∘:0                               0
┌──────────┬──┴─────────────────┐
a:1        b:3                 c:7              1
│      ┌───┴───┐     ┌──────────┼───────┐
p:2    q:4     r:6   s:8        t:11    u:14    2
       │             │          │
       │          ┌──┴──┐     ┌─┴───┐
       v:5        w:9   x:10  y:12  z:13        3
```


The condition a parent vector must satisfy is:

```
∧/V ∊(⍳≢V) ⍝ [All elements of V belong in the list [1..len(V)] ]
```

- `V ∊ (⍳≢V)` will be a list of whether each element in v belongs (`∊`) to the list
  `(⍳≢V) = [1..len(V)]`

- Recall that `/` is for reduction, and `∧/` is a boolean `AND` reduction.
  Hence, we compute whether each element of the vector `V` is in the range `[1..len(V)]`.

- We add the constraint that root notes that don't have a parent simply
  point to themselves. This allows us to free ourselves from requiring
  some kind of `nullptr` check.
  

The root node (parent of all elements) can be found using the fixpoint operator (`⍨`):

```
I←{(⊂⍵)⌷⍺} ⍝ index into the left hand side param using right hand side param
I⍣≡⍨p ⍝ compute the fixpoint of the I operator using ⍨ and apply it to p
```



#### Converting from depth vector to parent vector, Take 1

As usual, let's consider our example:

```
d ← (0  1  2  1  2  3  2  1  2  3  3  2  3  3  2) │ depths
    (∘  a  p  b  q  v  r  c  s  w  x  t  y  z  u) │ values
p ← (∘  ∘  a  ∘  b  q  b  ∘  c  s  s  c  t  t  c) │ parents
    (0  1  2  3  4  5  6  7  8  9 10 11 12 13 14) | indexes     
P ← (0  0  1  0  3  4  3  0  7  8  8  7 11 11  7) │ parent indices



              ∘:0                               0
┌──────────┬──┴─────────────────┐
a:1        b:3                 c:7              1
│      ┌───┴───┐     ┌──────────┼───────┐
p:2    q:4     r:6   s:8        t:11    u:14    2
       │             │          │
       │          ┌──┴──┐     ┌─┴───┐
       v:5        w:9   x:10  y:12  z:13        3
```

Note that the depth vector already encodes parent-child information.
- The parent of node `i` is a node `j` such that `d[j] = d[i] - 1` and
  `j` is the closest index to the left of `i` such that this happens.

For example, to compute the parent of `t:11`, notice that it's at depth `2`.
So we should find all the nodes from `d[0..11]` which have depths equal to
`2`, and then pick the rightmost one. This translates to the expression:

```
$ d ← (0  1  2  1  2  3  2  1  2  3  3  2  3  3  2)
$ t ← 11   ⍝ target node
$ ixs ← ⍳t   ⍝ array indexes upto this node
  0 1 2 3 4 5 6 7 8 9 10
$ d[ixs]   ⍝ depths of nodes to the left of the given node t
  0 1 2 1 2 3 2 1 2 3 3
$ d[ixs]  = d[t]-1  ⍝ boolean vector of nodes whose depth is that of t's parent
  0 1 0 1 0 0 0 1 0 0 0
$ eqds ← ⍸ (d[ixs] = d[t]-1)  ⍝ array indexes of nodes whose depth is that of t's parent
  1 3 7
$ ⌽ eqds ⍝ reverse of array indexes to extract `7`
  7 3 1
$ ⊃ ⌽ eqds ⍝ first of the reverse of the array indexes to extract `7`
  7
$ (⌽⍸(d[⍳t] = d[t]-1))[0]  ⍝ APL style one-liner of the above
```

While this is intuitive, this does not scale: It does not permit us to find
the parent of all the nodes _at once_ --- ie, it is not parallelisable
over choices of `t`.

#### Converting from depth vector to parent vector, Take 2 (Or scan idiom)

Imagine we have a list of `0`s and `1`s, and we want to find the _index_ of
the rightmost `1` value. For example, given:

```
       0 1 2 3 4 5 6 7 8 9 10 11 12
$ a ← (0 0 1 0 0 0 1 0 1 0  0  0  0)
```

we want the answer to be `f a = 8`. We saw an implementation in terms of
`f←{(⌽⍸⍵)[0]}` in Take 1.
(recall that `⍵` is the symbol for the right-hand-side argument of a function).

We're going to perform the same operation slightly differently. Let's consider
the series of transformations:

```
$ ⌽a  ⍝ reverse of a
  0 0 0 0 1 0 1 0 0 0 1 0 0
$ ∨\ ⌽a ⍝ prefix scan(\) using the OR(∨) operator. Turn all 
        ⍝ entries after the first 1 into a 1
  0 0 0 0 1 1 1 1 1 1 1 1 1
$ +/ (∨\ ⌽a)  ⍝ sum over the previous list, counting number of 1s
  9
$ ¯1 +  (+/ (∨\ ⌽a))  ⍝ subtract 1 from the previous number
  8    
```

Why the hell does this work? Well, here's the proof:

- On running `⌽a`, we reverse the `a`. The last 1 of `a` at index $i$
  becomes the first $1$ of `⌽a` at index $i' \equiv n-i$. 
- On running  `∨\ ⌽a`, numbers including and after the first 1  
  become `1`. That is, all indexes $j \geq i'$ have 1 in them.
- On running `+/ (∨\ ⌽a)`, we sum up all 1s. This will give us $n-i'+1$ 1s.
  That is, $n-i'+1 = n-(n-i)+1 =i+1$.
- We subtract a $1$ to correctly find the $i$ from $i+1$.

This technique will work for __every row of a matrix__. This is paramount,
since we can now repeat this for the depth vector we were previously
interested in for each row, and thereby compute the parent index!


#### Converting from depth vector to parent vector, Take 3 (full matrix)

We want to extend the previous method we hit upon to compute the parents
of all nodes in parallel. To perform this, we need to run the moral
equivalent of the following:

```
$ ⎕IO ← 0 ⍝ 0 indexing 
$ d ← (0  1  2  1  2  3  2  1  2  3  3  2  3  3  2) ⍝ depth vector
$ t ← 11 ⍝ node we are interested in
$ a←d[⍳t]=d[t]-1  ⍝ boolean vector of nodes whose depth is that of t's parent
  0 1 0 1 0 0 0 1 0 0 0
$ ¯1 +  (+/ (∨\ ⌽a)) ⍝ index of last 0 of boolean vector
7 
```

for _every single choice of t_. To perform this, we can build a 2D matrix
of `d[⍳t]=d[t]-1` where `t` ranges over `[0..len(d)-1]` (ie, it ranges
over all the nodes in the graph).

We begin by using:

```
$ ⎕IO ← 0 ⋄ d ← (0  1  2  1  2  3  2  1  2  3  3  2  3  3  2) ⍝ depths
$ ]display ltdepth ← d ∘.> d ⍝ find `d[i] > d[j]` for all i, j.
┌→────────────────────────────┐
↓0 0 0 0 0 0 0 0 0 0 0 0 0 0 0│
│1 0 0 0 0 0 0 0 0 0 0 0 0 0 0│
│1 1 0 1 0 0 0 1 0 0 0 0 0 0 0│
│1 0 0 0 0 0 0 0 0 0 0 0 0 0 0│
│1 1 0 1 0 0 0 1 0 0 0 0 0 0 0│
│1 1 1 1 1 0 1 1 1 0 0 1 0 0 1│
│1 1 0 1 0 0 0 1 0 0 0 0 0 0 0│
│1 0 0 0 0 0 0 0 0 0 0 0 0 0 0│
│1 1 0 1 0 0 0 1 0 0 0 0 0 0 0│
│1 1 1 1 1 0 1 1 1 0 0 1 0 0 1│
│1 1 1 1 1 0 1 1 1 0 0 1 0 0 1│
│1 1 0 1 0 0 0 1 0 0 0 0 0 0 0│
│1 1 1 1 1 0 1 1 1 0 0 1 0 0 1│
│1 1 1 1 1 0 1 1 1 0 0 1 0 0 1│
│1 1 0 1 0 0 0 1 0 0 0 0 0 0 0│
└~────────────────────────────┘
```

- Note that `gt[i][j] = 1` iff `d[j] < d[i]`. So, for a given row (`i = fixed`), the `1s`
  nodes that are at lower depth (ie, potential parents).
  
- If we mask this to only have those indeces where `j <= i`, then the
  last one in each row will be such that `d[last 1] = d[i] - 1`. Why? Because
  the node that is closest to us with a depth less than us _must_ be our parent,
  in the preorder traversal.
```
$ ⎕IO ← 0 ⋄ d ← (0  1  2  1  2  3  2  1  2  3  3  2  3  3  2) ⍝ depths
$ ]display left ←  (⍳3) ∘.> (⍳3) ⍝ find `i > j` for all i, j.
┌→────┐
↓0 0 0│
│1 0 0│
│1 1 0│
└~────┘
```

Combining the three techniques, we can arrive at:

```
$ ⎕IO ← 0 ⋄ d ← (0  1  2  1  2  3  2  1  2  3  3  2  3  3  2) ⍝ depths
$ ltdepth ← d ∘.> d ⍝ find `d[i] > d[j]` for all i, j.
$ preds ←  (⍳≢d) ∘.> (⍳≢d) ⍝ predecessors: find `i > j` for all i, j.
$ pred_higher ←  ltdepth ∧ left   ⍝ predecessors tht are higher in the tree
$  parents_take_3 ← ¯1 +  +/∨\⌽pred_higher  ⍝ previous idiom for finding last 1.
¯1 0 1 0 3 4 3 0 7 8 8 7 11 11 7
```

For comparison, the actual value is:

```
    (0   1  2  3  4  5  6  7  8  9 10 11 12 13 14)  | indexes     
d ← (0   1  2  1  2  3  2  1  2  3  3  2  3  3  2)  │ depths
P ← (0   0  1  0  3  4  3  0  7  8  8  7 11 11  7)  │ parent indices
    (¯1  0  1  0  3  4  3  0  7  8  8  7 11 11  7) | parents, take 3

              ∘:0                               0
┌──────────┬──┴─────────────────┐
a:1        b:3                 c:7              1
│      ┌───┴───┐     ┌──────────┼───────┐
p:2    q:4     r:6   s:8        t:11    u:14    2
       │             │          │
       │          ┌──┴──┐     ┌─┴───┐
       v:5        w:9   x:10  y:12  z:13        3
```
We have an off-by-one error for the `0` node! That's easily fixed, we simply
perform a maximum with `0` to move `¯1 -> 0`:

```
$  parents_take_3 ← 0⌈  ¯1 +  +/∨\⌽pred_higher
0 0 1 0 3 4 3 0 7 8 8 7 11 11 7
```

So, that's our function:

```
parents_take_3 ← 0⌈  ¯1 +  +/∨\⌽ ((d∘.>d) ∧ (⍳≢d)∘.>(⍳≢d))
0 0 1 0 3 4 3 0 7 8 8 7 11 11 7
```

Note that the time complexity for this is dominated by having to calculate
the outer products, which even given infinite parallelism, take $O(n)$ time.
We will slowly chip away at this, to be far better.

#### Converting from depth vector to parent vector, Take 4 (log critial depth)
We will use the Key(`⌸`) operator which allows us to create key value pairs.

```
$ d ← 0 1 2 1 2 3 2 1 2 3 3 2 3 3 2
$ ]disp (⍳≢d) ,¨ d ⍝ zip d with indexes
┌→──┬───┬───┬───┬───┬───┬───┬───┬───┬───┬────┬────┬────┬────┬────┐
│0 0│1 1│2 2│3 1│4 2│5 3│6 2│7 1│8 2│9 3│10 3│11 2│12 3│13 3│14 2│
└~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~─→┴~──→┴~──→┴~──→┴~──→┴~──→┘
```

```
$ d ← 0 1 2 1 2 3 2 1 2 3 3 2 3 3 2
$ ]display b ← {⍺ ⍵}⌸d  ⍝ each row i has tuple (i, js): d[js] = i 
┌→──────────────────┐
↓   ┌→┐             │
│ 0 │0│             │
│   └~┘             │
│   ┌→────┐         │
│ 1 │1 3 7│         │
│   └~────┘         │
│   ┌→────────────┐ │
│ 2 │2 4 6 8 11 14│ │
│   └~────────────┘ │
│   ┌→───────────┐  │
│ 3 │5 9 10 12 13│  │
│   └~───────────┘  │
└∊──────────────────┘
```

In fact, it allows us to apply an arbitrary function to combine keys and values.
We will use a function that simply returns all the values for each key.

```
$ d ← 0 1 2 1 2 3 2 1 2 3 3 2 3 3 2
$ ]display b ← {⍵}⌸d ⍝ each row i contains values j such that d[j] = i.
┌→──────────────┐
↓0 0  0  0  0  0│
│1 3  7  0  0  0│
│2 4  6  8 11 14│
│5 9 10 12 13  0│
└~──────────────┘
```

Our first try doesn't quite work: it winds up trying to create a numeric matrix,
which means that we can't have different rows of different sizes. So, the
information that _only_ index `0` is such that `d[0] = 0` is lost. What we
can to is to wrap the keys to arrive at:

```
$ d ← 0 1 2 1 2 3 2 1 2 3 3 2 3 3 2
$ ]display b ← {⊂⍵}⌸d ⍝ d[b[i]] = i
┌→───────────────────────────────────────────┐
│ ┌→┐ ┌→────┐ ┌→────────────┐ ┌→───────────┐ │
│ │0│ │1 3 7│ │2 4 6 8 11 14│ │5 9 10 12 13│ │
│ └~┘ └~────┘ └~────────────┘ └~───────────┘ │
└∊───────────────────────────────────────────┘
```
Consider the groups `b[2] = (2 4 6 8 11 14)` and `b[3] = (5 9 10 12 13)`. All of `3`'s parents
are present in `2`. Every element in `3` fits at some location in `2`. Here is what
the fit would look like:

```
b[2]  2 4 _ 6 8 _  _ 11 __ __ 14   (nodes of depth 2)
b[3]      5     9  10   12 13      (leaf nodes)
          4     8   8   11 11      (parents: predecessor of b[3] in b[2])

              ∘:0                               0
┌──────────┬──┴─────────────────┐
a:1        b:3                 c:7              1
│      ┌───┴───┐     ┌──────────┼───────┐
p:2    q:4     r:6   s:8        t:11    u:14    2
       │             │          │
       │          ┌──┴──┐     ┌─┴───┐
       v:5        w:9   x:10  y:12  z:13        3
```

We use the Interval Index(`⍸`) operator to solve the problem of finding the
parent / where we should sqeeze a node from `b[3]` into `b[2]`
(This is formally known as the
[predecessor problem](https://en.wikipedia.org/wiki/Predecessor_problem))

```
⍝ left[a[i]] is closest number < right[i]
⍝ left[a[i]] is the predecessor of right[i] in left[i].
$ a ← (1 10 100 1000) ⍸ (1 2000 300 50 2 )
0 3 2 1 0
```

Now, we can use the technology of predecessor to find parents
of depth 3 nodes among the depth 2 nodes:

```
$ depth2 ← 2 4 6 8 11 14
$ depth3 ← 5 9 10 12 13 ⍝ parents (from chart): 4 8 8 11 11
$ depth3parentixs ← depth2 ⍸ depth3
$ depth3parents  ← depth2[depth3parentixs]
4 8 8 11 11

              ∘:0                               0
┌──────────┬──┴─────────────────┐
a:1        b:3                 c:7              1
│      ┌───┴───┐     ┌──────────┼───────┐
p:2    q:4     r:6   s:8        t:11    u:14    2
       │             │          │
       │          ┌──┴──┐     ┌─┴───┐
       v:5        w:9   x:10  y:12  z:13        3
```

We need to know one-more APL-ism: the `2-scan`. When we write
a usual scan operation, we have:

```
$ ⍳5
1 2 3 4 5
```
```
$ +/⍳5 ⍝ reduce
15
```

```
$ 2+/⍳5 ⍝ apply + to _pairs_ (2 = pairs)
3 5 7 9 ⍝ (1+2) (2+3) (3+4) (4+5)
```

```
$ 3+/⍳5 ⍝  apply + to 3-tuples 
6 9 12 ⍝ (1+2+3) (2+3+4) (3+4+5)
```

We begin by assuming the parent of `i` is `i` by using `p←⍳≢d`.

```
$ d ← (0 1 2 1 2 3 2 1 2 3 3 2 3 3 2)
$ d2nodes ← {⊂⍵}⌸d 
┌→┬─────┬─────────────┬─────────────┐
│1│2 4 8│3 5 7 9 12 15│6 10 11 13 14│
└→┴~───→┴~───────────→┴~───────────→┘
$ p←⍳≢d
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15
```

Now comes the biggie:
```
$ findparent ← {parentixs ← ⍺⍸⍵ ⋄ p[⍵]←⍺[parentixs]} 
```
- `⍺` is the list of parent nodes. 
- `⍵` is the list of current child nodes.
- We first find the indexes of our parent nodes by using 
  the `pix ← parent ⍸ child` idiom.
- Then, we find the actual parents by indexing into
  the parent list: `pix[parentixs]`.
- We write these into the parents of the child using:
  `p[children] ← parent[parent ⍸ child]`


This finally culminates in:
```
$ d←0 1 2 1 2 3 2 1 2 3 3 2 3 3 2
$ p←⍳≢d ⋄ d2nodes←{⊂⍵}⌸d ⋄ findp←{pix ← ⍺⍸⍵ ⋄ p[⍵]←⍺[pix]} ⋄ 2findp/d2nodes ⋄ p
0 0 1 0 3 4 3 0 7 8 8 7 11 11 7


    (0   1  2  3  4  5  6  7  8  9 10 11 12 13 14)  | indexes     
d ← (0   1  2  1  2  3  2  1  2  3  3  2  3  3  2)  │ depths
P ← (0   0  1  0  3  4  3  0  7  8  8  7 11 11  7)  │ parent indices
              ∘:0                               0
┌──────────┬──┴─────────────────┐
a:1        b:3                 c:7              1
│      ┌───┴───┐     ┌──────────┼───────┐
p:2    q:4     r:6   s:8        t:11    u:14    2
       │             │          │
       │          ┌──┴──┐     ┌─┴───┐
       v:5        w:9   x:10  y:12  z:13        3
```

Which can be further golfed to:
```
$ p⊣2{p[⍵]←⍺[⍺⍸⍵]}⌿⊢∘⊂⌸d⊣p←⍳≢d
0 0 1 0 3 4 3 0 7 8 8 7 11 11 7
```

The total time complexity of this method assuming infinite parallelism is as follows:
```
$ p←⍳≢d ⋄ d2nodes←{⊂⍵}⌸d ⋄ findp←{pix ← ⍺⍸⍵ ⋄ p[⍵]←⍺[pix]} ⋄ 2findp/d2nodes ⋄ p
```
- `(p←⍳≢d)` can be filled in `O(1)` time.
- `(d2nodes←{⊂⍵}⌸d)` is searching for keys in a small integer domain, so this is `O(#nodes)` using
  radix sort as far as I know. However, the thesis mentions that this can be done in 
  `O(log(|#nodes|))`. I'm not sure how, I need to learn this.
- For each call of `findp`, the call `(pix ← ⍺⍸⍵)` can be implemented using binary search
  leading to a logarthmic complexity in the size of `⍺` (since we are looking up
  for predecessors of `⍵` in `⍺`).
- The time complexity of the fold `2findp/d2nodes` can be done entirely in parallel
  since all the writes into the `p` vector are independent: we only write the
  parent of the current node we are looking at.


### 3.4: Computing nearest Parent by predicate

I'm going to simplify the original presentation by quite a bit.


```
     a b c d e f g h i  | names
     0 1 2 3 4 5 6 7 8  | indexes
P ← (0 0 1 2 0 4 5 6 7) | parents
X ← (0 1 0 0 1 1 0 0 0) | marked nodes
      
     a:0    
┌────┴───┐
b:1(X)   e:4(X)        
|        |
c:2      f:5(X)                 
|        |
d:3      g:6
         │
         h:7
         |
         i:8
```

We want to find nodes marked as `X` that are the closest parents to a
given node. The `X` vector is a boolean vector that has a `1` at
the index of each `X` node: `(b, e, f)`. So, the indexes `(1, 4, 5)` 
are `1` in the `X` vector.

The output we want is the vector:

```
      0 1 2 3 4 5 6 7 8  | indexes
      a b c d e f g h i  | names
PX ← (0 0 1 1 0 4 5 5 5) | closest X parent index
      a a b b a e f f f  | closest X parent name

    a:0    
┌────┴───┐
b:1(X)   e:4(X)        
|        |
c:2      f:5(X)                 
|        |
d:3      g:6
         │
         h:7
         |
         i:8
```

The incantation is:

```
$ I←{(⊂⍵)⌷⍺} ⍝ index LHS by RHS | (100 101 102 103)[(3 1 2)] := 103 101 102
$ PX ← P I@{X[⍵]≠1} ⍣ ≡ P
0 0 1 1 0 4 5 5 5
```

TODO. At any rate, since this does not require any writes and purely reads,
and nor does it need any synchronization, this is fairly straightforward
to implement on the GPU.

### 3.5: Lifting subtrees to the root

Once we have marked our `X` nodes, we now wish to lift entire subtrees of `X`
up to the root.
-  This pass displays how to lift subtrees and add new nodes to replace the subtree's original nodes.
- Luckily, there are no _sibling_ relationships that need to be maintained since
  we are uprooting an entire subtree.
- There are no _ordering constraints_ on how the subtrees should be arranged at
  the top.
- Hence, we can simply add new nodes to the _end_ of the tree (in terms of the preorder traversal).
  Adding to the middle of the tree will be discussed later.

There is some good advice in the thesis:
> When using APL primitives this way, it may be good to map
> their names and definitions to the domain of trees. For example,
> the primitive `⍸Predicate` is read as "the nodes where `Predicate` holds"
> and not as "the indexes where `Predicate` is 1".

For example, given the tree:

```
      0 1 2 3 4 5  | indexes
      a b c d e f  | names
P  ← (0 0 1 0 3 4) | parents
X  ← (0 1 0 1 1 0) | X nodes
PX ← (0 0 1 0 3 4) | closest X parent index

    a:0    
┌────┴───┐
b:1(X)   d:3(X)        
|        |
c:2      e:4(X)                 
         |
         f:5
```

we want the transformed tree to be:

```
    a:0               
┌────┴───┐           
bp:1(X)   ep:4(X)        
---------
b:1(X)
|
c:2
---------
e:4
|
fp:5
---------
f:5(X)              
|
g:6
```

We first look for nodes that need to be lifted.  There are:
- Non-root nodes (ie, nodes whose parents are not themselves: `p≠(⍳≢p)`) 
- Which have the property `X`.
```
nodes←⍸(X ∧ p≠(⍳≢p))  ⍝ ⍸:pick indexes.
```

### 3.6: Wrapping Expressions
### 3.7: Lifting Guard Test Exprsessions
### 3.8: Couting rank of index operators
### 3.9: Flattening Expressions
### 3.10: Associating Frame slots and variables
### 3.11: Placing frames into a lexical stack
### 3.12: Recording Exported names
### 3.13: Lexical Resolution

### 5.2.1 Traversal Idioms
### 5.2.2 Edge Mutation Idioms
### 5.2.3 Node Mutation Idioms

# [Things I wish I knew when I was learning APL](#things-i-wish-i-knew-when-i-was-learning-apl)

- For pasting multi-line code, 
  [there is a bug in the bug tracker for RIDE](https://github.com/Dyalog/ride/issues/323).
  For multi-line dfns, one can use `∇`. For multi-line values, I don't know yet.

- Operators in APL terminology (such as `¨`) are higher order functions.
  Thus, an operator allows one to modify known functions.

- Use `]disp` and `]display` to understand the structure of APL arrays.

- Set `]box on -style=max` to _always enable_ drawing arrays with `]display`.
  This is supremely useful as a newbie to understand array structure.

- Set `]box on -trains=parens` to render trains as trees. Super
  helpful when attempting to grok `train` code.

- Set `]boxing on` to enable boxing for trains, arguments, everything.

# [Every ideal that is maximal wrt. being disjoint from a multiplicative subset is prime](#every-ideal-that-is-maximal-wrt-being-disjoint-from-a-multiplicative-subset-is-prime)

I ran across this when reading another question on math.se, so I
[posted this proof for verification](https://math.stackexchange.com/questions/3570129/proof-verification-request-complement-of-multiplicative-set-is-ideal-iff-the-id) just to be sure I wasn't missing
something.

We wish to characterise prime ideals as precisely those that are disjoint from
a multiplicative subset $S \subseteq R$. That is:

- An ideal $P$ is prime iff $P = R \setminus S$, where $S$ is a multiplicative subset
  that cannot be made larger (ie, is maximal wrt to the $\subseteq$ ordering).

I'll be using the definition of prime as:

- An ideal $P$ is prime if for all $x, y \in R$, 
  $xy \in P \implies x \in P \lor y \in P$.


#### Prime ideal implies complement is maximal multiplicative subset:

Let $S = \equiv R \setminus P$ be the complement of the prime ideal $P \subsetneq R$
in question.

- Since $P \neq R$, $1 \not \in $P. (if $1 \in P$, then every element $x . 1 \in P$
  since $P$ is an ideal, and must be closed under multiplication with the
  entire ring). Hence, $1 \in S$.

- For any $x, y \in S$, we need $xy \in S$ for $S$ to be mulitplicative.


- For contradiction, let us say that $x, y \in S$ such that $xy \not \in S$.
  Translating to $P$, this means that $x, y \not \in P$ such that $xy \in P$.
  This contradictions the definition of $P$ being prime.

#### Ideal whose complement is maximal multiplicative subset implies ideal is prime.

- Let $I$ be an ideal of the ring $R$ such that its complement $S \equiv R / I$
  is a maximal multiplicative subset.

- Let $i_1 i_2 \in I$. For $I$ to be prime, 
  we need to show that $i_1 \in I$ or $i_2 \in I$. 

- For contradiction, let $i_1, i_2 \not \in I$.
  Thus, $i_1, i_2 \in S$. Since $S$ is multiplicative, $i_1 i_2 \in S$. That is,
  $i_1 i_2 \not \in I$ (since $I$ is disjoint from $S$). 
  
- But this violates our assumption that $i_1 i_2 \in I$. Hence, contradiction.


# [Getting started with APL](#getting-started-with-apl)

- Install [Dyalog APL](https://www.dyalog.com/download-zone.htm).

- Setup [RIDE](https://github.com/Dyalog/ride), the IDE for dyalog APL. 
  This IDE comes with auto complete, good key bindings, a top bar chock-full of
  information of all the APL symbols. It's really well designed and a pleasure
  to use.

- Follow the [Dyalog tutorial](https://tutorial.dyalog.com/), solving it
  chapter by chapter.

- Bookmark [APLCart](https://aplcart.info/), a collection of APL idioms, and
  refer to it when in need.

# [SpaceChem was the best compiler I ever used](#spacechem-was-the-best-compiler-i-ever-used)

It's kind of sad that this is the case, but on thinking about this, I realised
that the SpaceChem game was essentially a compiler, and it was such a pleasure
to learn how to use and debug --- the visual nature of it made it amazing to
find out.

# [Mnemonic for Kruskal and Prim](#mnemonic-for-kruskal-and-prim)

I often forget which is which, so I came up with this:

- Prim is very prim and proper, and therefore doesn't spread herself out. She
  picks out the minimum spanning tree one vertex at a time.


# [Legendre transform](#legendre-transform)

![legendre-transform](./static/legendre.png)


# [Cartesian Trees](#cartesian-trees)

Cartesian trees construct a tree $T = C(A)$ given an array $A$, such that
range minimum query (RMQ) on the array $A$ is equivalent to the lowest common ancestor (LCA)
of the nodes of the tree $T$.

![cartesian-tree](./static/cartesian-tree.svg)

Note that the tree looks like a _min-heap_.

To see the connection to LCA, if we want to find the range minimum in the range containing the
elements `[12, 10, 20, 15, 18]` of the array, the minimum is `10`, which is
indeed the lowest common ancestor of the nodes of `12` and `18` in the tree.

#### Building a Cartesian tree in linear time:

#### Converting LCA to RMQ

We can go the other way, and convert an LCA problem into a RMQ problem. We
perform an inorder traversal of the nodes, scribbling down the
depth of the node ([Link to lecture at 15:30](https://youtu.be/0rCFkuQS968?t=934)).
We ask for the _argmin_ version of RMQ, that gives us the _index_ of
the node with the lowest depth. This gives us the index of where the node lives.

#### Universe reduction in RMQ

We can have an arbitrary ordered universe, on which we want to perform RMQ. 
We can convert this to LCA by using a cartesian tree, and then convert to
a "clean" RMQ (by using the LCA -> RMQ using depth conversion). This now
will give us way faster operations (since we now have integers).

#### `+-1` RMQ:

We want the differences between nodes to have a difference of only `+-1`. We
had a much wider gap. Here, we perform an Euler tour (walk the tree DFS search order),
and sribble down every vertex we visit.

To find the LCA, we perform the RMQ on the locations of the _first_ occurence
of the node. (I think we don't actually need the first occurence, any
occurence will do).

#### References

- Material shamelessly written down from
  [Eric Demaine's excellent (MIT 6.851 Advanced Data Structures): Lecture 15](https://www.youtube.com/watch?v=0rCFkuQS968)
- Image of the tree [taken from WikiMedia](https://upload.wikimedia.org/wikipedia/commons/d/d5/Cartesian_tree.svg)




# [DFS numbers as a monotone map](#dfs-numbers-as-a-monotone-map)

Really, we want a partial order that is defined with the tree as the
Hasse diagram. However, performing operations on this is hard. Hence,
the DFS numbering is a good monotone map from this partial order
to the naturals, which creates a total order.

I want to think about this deeper, I feel that this might be a good way
to think about the `low` numbers that show up in 
[tarjan's algorithm for strongly connected components](https://en.wikipedia.org/wiki/Tarjan%27s_strongly_connected_components_algorithm)

This also begs the question: can we use other partial orders, that chunk
some information, but don't lose _all_ the information as going to a total
order (the naturals) does?

# [Self attention? not really](#self-attention-not-really)

The code is taken from [The annotated transformer](https://nlp.seas.harvard.edu/2018/04/03/attention.html)
which explains the "attention is all you need paper".

On skimming the code, one sees the delightful line of code:

```py
class EncoderLayer(nn.Module):
  "Encoder is made up of self-attn and feed forward (defined below)"
  def __init__(self, size, self_attn, feed_forward, dropout):
     super(EncoderLayer, self).__init__()
     self.self_attn = self_attn
     self.feed_forward = feed_forward
     self.sublayer = clones(SublayerConnection(size, dropout), 2)
     self.size = size
  def forward(self, x, mask):
    "Follow Figure 1 (left) for connections."
    x = self.sublayer[0](x, lambda x: self.self_attn(x, x, x, mask))
    return self.sublayer[1](x, self.feed_forward)
```

where the line:

```py
x = self.sublayer[0](x, lambda x: self.self_attn(x, x, x, mask))
```

seems to imply that we are, indeed, performing a self attention with the same
value `x` as the query, key, and value. 

However, reading the code of the self-attention (or the paper) leads
one to realise:

```py
class MultiHeadedAttention(nn.Module):
  def __init__(self, h, d_model, dropout=0.1):
    "Take in model size and number of heads."
    super(MultiHeadedAttention, self).__init__()
    assert d_model % h == 0
    # We assume d_v always equals d_k
    self.d_k = d_model // h
    self.h = h
    self.linears = clones(nn.Linear(d_model, d_model), 4)
    self.attn = None
    self.dropout = nn.Dropout(p=dropout)
      
  def forward(self, query, key, value, mask=None):
    "Implements Figure 2"
    if mask is not None:
        # Same mask applied to all h heads.
        mask = mask.unsqueeze(1)
    nbatches = query.size(0)
    
    # 1) Do all the linear projections in batch from d_model => h x d_k 
    query, key, value = \
        [l(x).view(nbatches, -1, self.h, self.d_k).transpose(1, 2)
         for l, x in zip(self.linears, (query, key, value))]
    
    # 2) Apply attention on all the projected vectors in batch. 
    x, self.attn = attention(query, key, value, mask=mask, 
                             dropout=self.dropout)
    
    # 3) "Concat" using a view and apply a final linear. 
    x = x.transpose(1, 2).contiguous() \
         .view(nbatches, -1, self.h * self.d_k)
    return self.linears[-1](x)
```

where we notice:

```py
# 1) Do all the linear projections in batch from d_model => h x d_k 
query, key, value = \
  [l(x).view(nbatches, -1, self.h, self.d_k).transpose(1, 2)
   for l, x in zip(self.linears, (query, key, value))]

# 2) Apply attention on all the projected vectors in batch. 
x, self.attn = attention(query, key, value, mask=mask, 
                         dropout=self.dropout)
```

where we see that `query, key, value` are being linearly transformed
before being used. Hence, an input of $(x, x, x)$ is transformed
to $(q', k', v') = (Qx, Kx, Vx)$ where $Q, K, V$ are arbitrary matrices.

Next, when we pass these into attention, the output we get is:

$$
\text{softmax(q', k'^T) v = (Q x) (K x)^T (V x) = Q x x^T K^T V x
$$

the code below is the same thing, spelled out:


```
def attention(query, key, value, mask=None, dropout=None):
    "Compute 'Scaled Dot Product Attention'"
    d_k = query.size(-1)
    scores = torch.matmul(query, key.transpose(-2, -1)) \
             / math.sqrt(d_k)
    if mask is not None:
        scores = scores.masked_fill(mask == 0, -1e9)
    p_attn = F.softmax(scores, dim = -1)
    if dropout is not None:
        p_attn = dropout(p_attn)
    return torch.matmul(p_attn, value), p_attn
```

So It's not _really_ self attention: it's more like: modulated attention
to self `:)`


# [Coarse structures](#coarse-structures)

A coarse structure on the set $X$ is a collection of relations on $X$: 
$E \subseteq 2^{X \times X}$ (called as _controlled sets_ / _entourages_)
such that:

- $(\delta \equiv \{ (x, x) : x \in X \}) \in  E$.
- Closed under subsets: $\forall e \in E, f \subset e \implies f \in E$.
- Closed under transpose: if $e \in E$ then $(e^T \equiv \{ (y, x) : (x, y) \in e \}) \in E$.
- Closed under finite unions.
- Closed under composition: $\forall e, f \in E, e \circ f \in E$, where $\circ$
  is composition of relations.

The sets that are controlled are "small" sets. 

The bounded coarse structure on a metric space $(X, d)$ is the set of all relations
such that there exists a uniform bound such that all related elements are within
that bounded distance.
$$
(e \subset X \times X) \in E \iff \exists \delta \in \mathbb R, \forall (x, y) \in E, d(x, y) < \delta
$$


We can check that the functions:
- $f: \mathbb Z \rightarrow \mathbb R, f(x) \equiv x$ and
- $g: \mathbb R \rightarrow \mathbb Z, g(x) \equiv \lfloor x \rfloor$

are coarse inverses to each other.

I am interested in this because if topology is related to semidecidability,
then coarse structures (which are their dual) are related to..?

#### References
- [What is a.. coarse structure by AMS](http://www.ams.org/notices/200606/whatis-roe.pdf)

# [Matroids for greedy algorithms](#matroids-for-greedy-algorithms)

#### Definitions of matroids

A matrioid $M$ is a set $X$ equipped with an independence set $I \subseteq 2^X$.
- The empty set is independent: $\emptyset \in I$.
- The independence set is downward-closed/closed under subsets:  $ \forall i \in I, \forall i' \subseteq i, i' \in I$.
- For any independent sets $A, B \in I$, if $\vert A \vert$ is larger than 
  $\vert B \vert$, then we must be able to add an element from
  $a \in A$ into $B' \equiv B \cup {a}$ such that $B'$ is both independent and larger than $B$:
  $B' \in I \land \vert B' \vert > \vert B \vert$. (**The exchange property**)

#### Example 1: Linearly independent sets
Let $V$ be a vector space. The independent sets $I$ are of the form:


!! I \equiv \{ S \subseteq V ~:~ \text{vectors in $S$ are lineary independent} \} !!

This is an independence system because the empty set is linearly independent,
and subsets of a linearly independent collection of vectors will be linearly
independent.

The exchange property is satisfied because of linear algebraic reasons.

#### Example 2: The graphic/cyclic Matroid: Matroid of Forests

Let $G = (V, E)$ be a graph. Then collections of edges of the form:

$$ I \equiv \{ F \subseteq E : \text{$F$ contains no cycles} \} $$

is an independence system because the empty forest is a forest, and
a subset of edges of a forest continues to be a forest.

To check the exchange property, TODO

#### Example 3: The partition matroid

Consider the partition matroid $M \equiv (E, I)$, where we have a
partitioning of $E$ known as $E_i$, and numbers $k_i$ the
independence set consists of subsets $F$ which have at most $k_i$
elements in common with each $E_i$.
$$
I \equiv \{ F \subseteq E  : \forall i = 1, \dots N, \vert F \cap E_i \vert \leq k_i \}
$$

The independence axioms are intuitively satisfied, since our constraints on picking
edges are of the form $\vert F \cap E_i \vert \leq k_i$, which will continue to
hold as $F$ becomes smaller.

For the exchange axiom, let $\vert Y \vert > \vert X \vert$. Then, we can assert that for some index
$i$, it must be the case that $\vert Y \cap E_i \vert > \vert X \cap E_i \vert$. Hence,
we can add an element in $E_i \cap (Y / X)$ into $X$ whilst still maintaining independence.


#### Bases and Circuits

- **Bases** are the maximal independent sets of $I$ (ordered by inclusion). On adding an element into a basis element, they
  will become dependent. They are called bases by analogy with linear algebra.

- **Circuits** are minimal dependent sets of $I$. This comes from analogy with trees: if we remove an element
  from any circuit (loop) in a graph, what we are left with is a tree.

A matroid can be completely categorized by knowing either the bases or the circuits of that matroid.

#### Unique Circuit property
- **Theorem**: Let $M \equiv (E, I)$ be a matroid, and let $S \in I, e \in E$ such that $S \cup \{e \} \not \in I$.
Then, there exists a **unique circuit** $C \subseteq $S \cup \{ e \}$.

That is, when we go from independent to dependent by adding an element, we will have a **single, unique
circuit**. For example, when we add an edge into a forest to create a cycle, this cycle will
be unique!

##### Proof

Let $C_1, C_2$ be circuits
created when $e$ was added into $S$, where $C_1$ is the **largest** circuit of $S$,
and $C_2$ is the **smallest** circuit of $S$.

Notice that $C_1, C_2$ __must__ contain $e$ --- 
if they did not, then $C_1, C_2$ would be circuits in
$S$, contradicting the assumption that $S$ is independent.

Recall that $C_1, C_2$ are both circuits, which means that removing even a
single element from them will cause them to become independent sets. 

Let us contemplate $C \equiv C_1 \cup C_2$. Either $C = C_1$ in which
case we are done. 

Otherwise, \vert C \vert > \vert C_1 \vert$, $\vert C \vert > \vert C_2 \vert$.

Otherwise, consider $C' \equiv C \ \{ e \} = (C_1 \cup C_2) \ \{e\} = (C_1 \ \{e\}) \cup (C_2 \ \{ e \})$.
- $C' \subseteq S$, since $\C_1 \ \{e\}, C_2 \ \{e\} \subseteq S$. 
- $S$ is an independent set, all of whose subsets are independent by
  definition.  So $C'$ is an independent set.
- $\vert C' \vert \geq \vert C_1 \vert$, $\vert C' \vert \geq \vert C_2 \vert$.

Now, we consider $C$. Clearly, this is a dependent set,
since $C_1 \subsetneq C$, and $C_1S is a dependent set.

Since, $C = C' \cup \{e \}$, this means that $C'$ is a maximally independent set.
Since $C'$ does not contain $e$, $C' = S$.


#### Rank functions 

A rank function of a matroid $M \equiv \langle X, I \rangle$ 
is a function:

$$
r: 2^X \rightarrow \mathbb N : r(S) = \max \{ \vert T \vert : T \subseteq S \land T \in I \}
$$

That is, for any subset $S \subseteq X$, $r(S)$ is the cardinality of the
largest independent subset of $S$.

- In the matroid of linearly independent sets of vectors, the rank of
  a set of vectors is the dimension of their spanning set.


In this matroid, the 

TODO: picture



#### Bipartite matching as matroid intersection

Matchings in a bipartite graph $G = (V, E)$ with partition $(A, B)$ arise
as the intersection of the independent sets of two matroids.
We will denote by $\delta: V \rightarrow 2^E$ the function which takes
a vertex to the set of edges incident on that vertex.

Let $M_A$ be a _partition matroid_: $M_A \equiv (E, I_A)$ where $I_A$ is:
$$
I_A \equiv \{ F \subseteq E : \vert F \cap \delta(a) \vert \leq 1 \forall a \in A \}
$$
That is, in $I_A$, every independent set has for each vertex of $A$, at most
one edge incident. We need to check that this is an independent set.
The empty set of no edges is independent. If some collection of edges are 
such that they have at most one edge incident, then removing edges can
only _decrease_ incidence. Hence, it's also downward closed.


TODO: add picture

Similarly, we define $M_B \equiv (E, I_B)$:
$$
I_B \equiv \{ F \subseteq E : \vert F \cap \delta(b) \vert \leq 1 \forall b \in B \}
$$

Now, notice that any collection of edges $F \in I_A \cap I_B$ is a legal
matching, since the edges cover all vertices of $A$ and $B$ at most once.
The largest element of $I_A \cap I_B$ is the _maximum matching_ that we
are looking for.

#### Largest common independent set

Given two matroids $M_1 \equiv (E, I_1)$, $M_2 \equiv (E, I_2)$, with rank
functions $r_1$ and $r_2$. Let $S \in I_1 cap I_2$ and let $F \subseteq E$. 
-  $\vert S \vert = \vert S \cap F \vert$ + \vert S \cap (E / F) \vert$.


#### References:
- [Michel Goeman's standalone notes on matroids](http://math.mit.edu/~goemans/18433S11/matroid-notes.pdf)
- [Michel Goeman's standalone notes on matroid intersection](http://math.mit.edu/~goemans/18433S11/matroid-intersect-notes.pdf)
- [Lecture 11 of Michel Goeman's lecture on Advanced Combinatorial Optimisation](https://math.mit.edu/~goemans/18438F09/lec11.pdf)


# [Grokking Zariski](#grokking-zariski)

There's a lot written on the Zariski topology on the internet, but most
of them lack explicit examples and pictures. This is my attempt to
communicate what the Zariski topology looks like, from the perspectives
that tickle my fancy (a wealth of concrete examples,
topology-as-semi-decidability, and pictures).

#### The Zariski topology

Recall that the Zariski topology is defined by talking about what its
closed sets are. The common zero sets of a family of polynomials are
the closed sets of the Zariski topology. Formally, the topology $(\mathbb R^n, \tau)$
has as closed sets:

$$
\{ x \in \mathbb R^n : \forall f_i \in \mathbb R[X_1, X_2, \dots X_n],  f_i(x) = 0  \}
$$

Open sets (the complement of closed sets) are of them form:

$$
\{ x \in \mathbb R^n : \exists f_i \in \mathbb R[X_1, X_2, \dots X_n],  f_i(x) \neq 0  \} \in \tau
$$

The empty set is generated as $\{ x \in \mathbb R^n : 0 \neq 0 \}$ and the
full set is generated as $\{ x \in \mathbb R^n : 1 \neq 0 \}$.


#### Semi-decidability

Recall that in this view of topology, for a space $(X, \tau)$, for every
open set $O \in \tau$, we associate a turing machine $T_O$.
which obeys the relation:

$$
\begin{aligned}
x &&\in O \iff \text{$T_O$ halts on input $x$} \\
x &&\not \in O \iff \text{$T_O$ does not halts on input $o$}
\end{aligned}
$$

#### Geometry --- 1D

Let's consider functions of the form $(\mathbb R^2, Z) \xrightarrow{f} (\mathbb R^2, Z)$
where $Z$ is the Zariski topology. We are interested in discovering what
sort of functions $f$ are continuous.


#### Geometry --- 2D

Let's repeat the exercise for 2D. Here, we will manage to see much richer
behaviour. Let's consider functions of the form $(\mathbb R^2, Z) \xrightarrow{f} (\mathbb
R^2, Z)$ where $Z$ is the Zariski topology.


# [My preferred version of quicksort](#my-preferred-version-of-quicksort)

Wikipedia lists the implementation of quicksort as:

```cpp
algorithm quicksort(A, lo, hi) is
    if lo < hi then
        p := partition(A, lo, hi)
        quicksort(A, lo, p - 1)
        quicksort(A, p + 1, hi)

algorithm partition(A, lo, hi) is
    pivot := A[hi]
    i := lo
    for j := lo to hi do
        if A[j] < pivot then
            swap A[i] with A[j]
            i := i + 1
    swap A[i] with A[hi]
    return i
```

Here, the indeces `[lo..i-1]` have values less than the pivot, while
`[i..j]` are great or equal to the pivot.

##### The version I prefer

```cpp
// #define SWAP(ix, ix2) { int t = a[ix]; a[ix] = a[ix2]; a[ix2] = t; }
// sorts the interval [l, r]
void qs(int l, int r) {
    if (r - l < 0) return;
    int part = a[r]; // the partition

    // a[getill...n] >= part (getill = greater or equal till)
    // starts at r since we know that a[r] >= (partition=a[r])
    int getill = r; 
    // a[l..lttill] < part (lttill = less or equal till.
    // starts at (l-1) since we do not know about any value < partition
    int lttill = l-1; 


    // loop until they start probing into the other set
    while(!(lttill+1 >=getill || getill-1 <=lttill)) {
        // if the speculated element is < partition
        if (a[getill-1] < part) { 
            // swap the value at getill-1 will the slot at lttill+1
            SWAP(getill-1, lttill+1);
            // increment lttill, since we KNOW that the 
            // value at lttill+1 = a[getill-1] is < part
            lttill++;
        } else {
            // all we know is that a[getill-1] < part, so we can engulf
            // the region into 
            getill--;
        }
    }
    // the partitions must be next to each other, since we have engulfed everything
    assert(getill - lttill == 1);
    // move the partition value to the center.
    SWAP(getill, r);

    // recurse:solve [l..littil] (leave getill=part alone) solve [getill+1..r] 
    qs(l, lttill);
    qs(getill+1, r);
}
```

This implementation to me makes very clear to me what information is "known":
- The segments that is strictly less than the partition.
- The segment that is strictly great or equal the partition.

It also makes clear what is being "probed"/"tentative":
- anything we are accessing as `+-1` is not known yet, we are feeling out
  the boundaries of our partitions.

The termination condition is clear: when one partition starts reaching into
the other partitions resources, its done.

Due to using closed intervals everywhere, it's very easy to see precisely
what data starts and ends where.

What version of quicksort do you prefer? Drop me an email!

# [Geometric proof of Cauchy Schwarz inequality](#geometric-proof-of-cauchy-schwarz-inequality)

![geometric-proof-cauchy-schwarz](static/cauchy-schwarz.svg)

- All credit goes to `p0a` on `##math` on freenode for teaching me this proof!

Here's one fun application of Cauchy-Schwarz. We can apply it to two vectors
$x=(\sqrt a, \sqrt b)$ and $y=(\sqrt b, \sqrt a)$ to derive the AM-GM
inequality:




# [Dataflow analysis using Grobner basis](#dataflow-analysis-using-grobner-basis)

This was a quick experiment in using Grobner basis to model situations. We 
can represent our dataflow analysis constraints in terms of polynomial
rewrites over $F_2$. 

Given the program:

```py
p = { 0: ["=", "x", 'y'], 
      1: ['br', 2, 100], 
      2: ['=', 'z', 'x'], 
      3: ['br', 2],
      100: ['ret', 'z'] }
```

whose semantics I hope are fairly straightforward --- the dictionary represents
instruction locations. Instructions proceed sequentially. branch moves
control flow around. Note that `br` can branch to multiple locations,
since we are not control-flow sensitive.

The idea is that since in a dataflow analysis, we need information at 
each variable at each program point, we can create a ring of polynomials
over $F_2$ for each variable at each program point. So in this case,
we wold need:

```
R = F_2[x0, y0, z0, x1, y1, z1, x2, y2, z2, x3, y3, z3, x100, y100, z100]
```

We then add elements into the ideal that represents our constraints.
For example, to perform dataflow analysis, we need to add constraints
about how if a variable `z` is alive, all variables that are used
to compute `z` at `100` are alive. This sets up equations that may
have cycles (in the case of loops). 

These are usually resolved using the
[Kildall algorithm](https://en.wikipedia.org/wiki/Data-flow_analysis#An_iterative_algorithm).

However, we can also ask SAGE to kindly solve the Grobner basis. I hypothesize
that the "easy" dataflow problems out to be [toric ideals](https://hal.inria.fr/inria-00074446/document)
which admit much faster solutions.



# [Fenwick trees and orbits](#Fenwick-trees-and-orbits)

I learnt of a nice, formal way to prove the correctness of Fenwick
trees in terms of orbits that I wish to reproduce here.

One can use a Fenwick tree to perform cumulative sums
$Sum(n) \equiv \sum_i^n A[i]$, and updates $Upd(i, v) \equiv A[i] += v$. Naively,
cumulative sums can take $O(n)$ time and updates take $O(1)$ time. 

A Fenwick tree can perform _both_ in $\log(n)$. In general, we can perform
any monoid-based catenation and update in $\log(n)$.

#### organization

We allow indexes $[1, 2, \dots n]$. The node with factorization $i \equiv 2^k \times l$,
$2 \not \vert l$ (that is, $k$ is the highest power of $2$ in $i$)
is responsible for the interval $[i-2^k+1, i] = (i-2^k, i]$.


I'm going to state all the manipulations in terms of prime factorizations,
since I find it far more intuitive than bit-fiddling. In general, I want
to find a new framework to discover and analyze bit-fiddling heavy algorithms.

Some examples of the range of responsibility of an index are:

- $1 = 2^0 \times 1 = (0, 1]$ (Subtract $2^0 = 1$)
- $2 = 2\times 1 = (0, 2]$ (Subtract $2^1 = 2$)
- $3 = 3 = (2, 3]$
- $4 = 2^2 = (0, 4]$
- $5 = 5 = (4, 5]$
- $6 = 2\times 3 = (4, 6]$
- $7 = 7 = (6,7]$
- $8 = 2^3 = (0,8]$
- $9 = 9 = (8, 9]$
- $10 = 2\times 5 = (8, 10]$
- $11 = 11 = (10, 11]$
- $12 = 2^2\times 3 = (8, 12]$
- $13 = 13 = (12, 13]$
- $14 = 2\times 7 = (12, 14]$
- $15 = 15 = (14, 15]$
- $16 = 2^4 = (0, 16]$

![fenwick-structure](static/fenwick-structure.gif)


#### query

To perform a cumulative sum, we need to read from the correct overlap regions
that cover the full array. For example, to read from $15$, we would want
to read:

- $a[15] = (14, 15], a[14] = (12, 14], a[12] = (8, 12], a[8] = (0, 8]$.

So we need to read the indices:
- $15=2^0 \cdot 15 \xrightarrow{-2^0} 14=2^1 \cdot 7 \xrightarrow{-2^1} 12=2^2\cdot3 \xrightarrow{-2^2} 8=2^3\cdot1 \xrightarrow{-2^3} 0$

At each  location, we strip off the value $2^r$. We can discover this value
with bit-fiddling: We claim that $a \& (-a) = 2^r$.

Let $a = x 1 0^r$. Now, $-a = \lnot a + 1 = x01^r + 1 = \overline{x}10^r$.
Hence, $a \& (-a) = a \& (\lnot a + 1) = (x 10^r) \& (\overline{\x}10^r) = 0^{|\alpha|}10^r = 2^r$

So the full implementation of query is:

```cpp
#define LSB(x) x&(-x)
int a[N];
int q(int i) {
    int s = 0;
    while (i > 0) { s += a[i]; i -= LSB(i); }
    return s;
}

```

#### update

To perform an update at $i$, we need to update all locations which on querying
overlap with $i$. For example, to update the location $9$, we would want to
update:

- $a[9] = (8, 9], a[10] = (8, 10], a[12] = (8, 12], a[16] = (0, 16]$.

So we need to update the indices:

- $9=2^0 \cdot 9 \xrightarrow{+2^0} 10=2^1 \cdot 5 \xrightarrow{+2^1} 12=2^2\cdot3 \xrightarrow{+2^2} 16=2^4\cdot1 \xrightarrow{+2^4} \dots$

We use the same bit-fiddling technique as above to strip off the value $2^r$


```cpp
#define LSB(x) x&(-x)
int tree[N];
int u(int i, int v) {
    while (i < N) { tree[i] += v; i += LSB(i); }
}
```


#### correctness

We wish to analyze the operations $Query(q) \equiv \sum_{i=1}^q a[i]$, and
$Update(i, val) \equiv a[i]~\texttt{+=}~val$. To do this, we are allowed to maintain
an auxiliary array $d$ which we will manipuate. We will stipulate the
conditions of operations on $d$ such that they will reflect the values of 
$Query$ and $Update$, albeit much faster.

We will analyze the algorithm in terms of orbits. We have two operators, one
for update called $U$, and one for query called $Q$. Given an index $i$,
repeatedly applying the query operator gives us the indeces we need to read and
accumulate from the underlying array $a$ to get the total sum $a[0..i]$:

- $Query(i) = \sum_i d[Q^i(q)]$ 

Given an index $u$, repeatedly applying the update operator $U$ gives us all
the indeces we need to add the change to update:
- $Update(i, val) = \forall j~, d[U^j(i)]~\texttt{+=}~ val$

For query and update to work, we need the condition that:
- $q \geq u \iff \left\vert \{ Q^i(q)~:~ i \in \mathbb{N} \} \cap \{ U^i(u)~:~i \in \mathbb{N} \} \right\vert = 1$

That is, if and only if the query index $q$ includes the update location $u$,
will the orbits intersect. 

The intuition is that we want updates at an index $u$ to only affect queries
that occur at indeces $q \geq u$. Hence, we axiomatise that for an update
to be legal, it must the orbits of queries that are at indeces greater than it.

We will show that our operators:
- $Q(i=2^r\cdot a) = i - 2^r = 2^r(a-1)$
- $U(j=2^s\cdot b) = j + 2^{s} = 2^{s}(b+1)$

do satisfy the conditions above.

For a quick numerical check, we can use the code blow to ensure
that the orbits are indeed disjoint:
```py
# calculate orbits of query and update in fenwick tree

def lsb(i): return i & (-i)
def U(i): return i + lsb(i)
def Q(i): return i - lsb(i)
def orbit(f, i):
    s = set()
    while i not in s and i > 0 and i < 64:
        s.add(i); i = f(i)
    return s

if __name__ == "__main__":
    for q in range(1, 16):
        for u in range(1, 16):
            qo = orbit(Q, q); uo = orbit(U, u)
            c = qo.intersection(uo)
            print("q:%4s | u:%4s | qo: %20s | uo: %20s | qu: %4s" % 
                  (q, u, qo, uo, c))

        print("--")
```

##### Case 1: $q = u$

We note that $Q$ always decreases the value of $q$, and $u$ always increases
it. Hence, if $q = u$, they meet at this point, and 
$\forall i, j \geq 1, \quad Q^i (q) \neq U^j(u)$.
Hence, they meet exactly once as required.

##### Case 2: $q < u$

As noted above, $q$ always decreases and $u$ always increases, hence in this
case they will never meet as required.


##### Case 3: $q > u$

Let the entire array have size $2^N$.  
Let $q = \texttt{e1$f_q$}, u = \texttt{e0$f_u$}$, where 
$\texttt{e},f_q, f_u$ may be empty strings. 

Notice that $Q$ will always strip away rightmost ones in $f_q$,
leading to $q = \texttt{e10...0}$ at some point. 

Similarly, $U$ will keep on adding new rightmost ones, causing the
state to be $u = \texttt{e01...10...0} \xrightarrow{U} \texttt{e100...}$.

Hence, at some point $q = u$. 

#### References

- [Fenwick trees on PolyMath](http://michaelnielsen.org/polymath1/index.php?title=Updating_partial_sums_with_Fenwick_tree)
- [Hacker's delight](https://doc.lagout.org/security/Hackers%20Delight.pdf)

# [Dirichlet inversion](#Dirichlet-inversion)

We call all functions $f: \mathbb Z \rightarrow \mathbb R$ as
_arithmetic functions_, since they operate on the integers.

We introduce an operator $f \star g: \mathbb Z \rightarrow \mathbb R$.
It is defined by:
- $(f \star g)(n) \equiv \sum_{d \vert n} f(d) g(n/d)$

We will show that the set of arithmetic functions forms a group
under the operator $\star$, with identity:

-  $id_\star(n) \equiv \floor{1/n} = \begin{cases} 1 & $n = 1$ \\ 0 & \text{otherwise} \end{cases}$


The reason all of this is interesting is that the inverse of the constant function $1(n) \equiv 1$
is going to be this function called as the mobius function $\mu$:

$
\mu(n=p_1^\alpha_1 p_2^\alpha_2 \dots p_r^\alpha_r) \equiv
\begin{cases}\{
  0 & \textt{if any $\alpha_i > 1$} \\
  (-1)^{\alpha_1 + \alpha_2 + \dots + \alpha_r} & \text{if all $\alpha_i \in \{ 0, 1 \}$}
\end{cases}
$

The mobius function will allow us to perform _mobius inversion_:

$$
\begin{aligned}
  f(n) &\equiv \sum_{d \vert n} g(d) = \sum_{d \vert n} g(d) 1(n/d) = g \star 1 \\
  f \star 1^{-1} &=  g \star 1 \star 1^{-1} \\
  f \star \mu &= g
\end{aligned}

That is, we originally had $f$ defined in terms of $g$. We can
recover an expression for $g$ in terms of $f$.

### The algebra of multiplicative functions

We claim that the set of functions $\{ \mathbb Z \rightarrow \mathbb C \}$
is a commutative group, with the group operation $\star$ such that:

- $(f \star g)(n) \equiv \sum_{d \vert n} f(d) g(n/d)$.

with the identity element being $id_\star(n) \equiv \lfloor 1 / n \rfloor$. The idea
is that if $(n = 1)$, then $\lfloor 1/1 \rfloor = 1$, and for any other
number $n > 0$, $1/n < 1$, hence $\lfloor 1/n \rfloor = 0$.

### verification of $istar$ being the identity
- $(f \star id_\star)(n) \equiv \sum_{d \vert n} f(d) id_\star(n/d) 
  = f(n) id_\star(1) + \sum_{d \vert n, d > 1} f(n) id_\star(d)
  = f(n) \cdot 1 + \sum_{d \vert n, d > 1} f(n) \cdot 0
  = f(n)$
  
### associativity of $\star$
### commutativity of $\star$
### inverse operator
### $\mu$ as the inverse of the $one$ function
### Mobius inversion
### $n = \sum_{d \vert n} \phi(d)$ 

$$
\begin{array}{|c|c|}
\hline
   d & \{ 1 \leq x \leq 12 : (x, 12) = d \} & \{ 1 \leq x \leq 12: (x/d, 12/d) = 1\} & \text{size of set} \\
\hline
  1 & \{ 1, 5, 7, 11 \} & (x, 12) = 1 & 4 \\
\hline
 2 & \{2, 10 \} & (x/2, 6) = 1& 2 \\
\hline
 3 & \{3, 9 \} & (x/3, 4) = 1 & 2 \\
\hline
 4 & \{4, 8 \} & (x/4, 3) = 1 & 2 \\
\hline
  6 & \{ 6 \} & (x/6, 2) = 1 & 1
\hline
 12 & \{ 12 \} (x/12, 1) = 1 & 1
\end{array}
$$

Notice that the sizes of sets that we are calculating, for example, 
$|\{ 1 \leq x \leq 12 : (x/2, 6) = 1 \}| =  \phi(6)$. Summing over all of
what we have, we've counted the numbers in $[1, 2, \dots, 12]$ in two ways ---
one directly, and the other by partitioning into equivalence classes:

$$ 12 = \phi(1) + \phi(2) + \phi(3) + \phi(4) + \phi(6) + \phi(12) = \sum_{d \vert 12) \phi(12/d) $$

In general, the same argument allows us to prove that:

$$ n = \sum_{d \vert n} n/d $$

### Using mobius inversion on the euler totient function

### Other arithmetical functions and their relations


# [Incunabulum for the 21st century: Making the J interpreter compile in 2020](#incunabulum-for-the-21st-century-making-the-j-interpreter-compile-in-2020)

This is me trying to understand the fabled interpreter of the `J` language
working, so I could absorb Arthur Whitney's style of writing C: it's
cryptic, short, and fits in a page. [I learnt of this from the `J` language page](https://code.jsoftware.com/wiki/Essays/Incunabulum),
which comes with the quote:

> One summer weekend in 1989, Arthur Whitney visited Ken Iverson at Kiln Farm
> and produced—on one page and in one afternoon—an interpreter fragment on the
> AT&T 3B1 computer. I studied this interpreter for about a week for its
> organization and programming style; and on Sunday, August 27, 1989, at about
> four o'clock in the afternoon, wrote the first line of code that became the
> implementation described in this document.
> Arthur's one-page interpreter fragment is as follows:

#### The original source

```c
typedef char C;typedef long I;
typedef struct a{I t,r,d[3],p[2];}*A;
#define P printf
#define R return
#define V1(f) A f(w)A w;
#define V2(f) A f(a,w)A a,w;
#define DO(n,x) {I i=0,_n=(n);for(;i<_n;++i){x;}}
I *ma(n){R(I*)malloc(n*4);}mv(d,s,n)I *d,*s;{DO(n,d[i]=s[i]);}
tr(r,d)I *d;{I z=1;DO(r,z=z*d[i]);R z;}
A ga(t,r,d)I *d;{A z=(A)ma(5+tr(r,d));z->t=t,z->r=r,mv(z->d,d,r);
 R z;}
V1(iota){I n=*w->p;A z=ga(0,1,&n);DO(n,z->p[i]=i);R z;}
V2(plus){I r=w->r,*d=w->d,n=tr(r,d);A z=ga(0,r,d);
 DO(n,z->p[i]=a->p[i]+w->p[i]);R z;}
V2(from){I r=w->r-1,*d=w->d+1,n=tr(r,d);
 A z=ga(w->t,r,d);mv(z->p,w->p+(n**a->p),n);R z;}
V1(box){A z=ga(1,0,0);*z->p=(I)w;R z;}
V2(cat){I an=tr(a->r,a->d),wn=tr(w->r,w->d),n=an+wn;
 A z=ga(w->t,1,&n);mv(z->p,a->p,an);mv(z->p+an,w->p,wn);R z;}
V2(find){}
V2(rsh){I r=a->r?*a->d:1,n=tr(r,a->p),wn=tr(w->r,w->d);
 A z=ga(w->t,r,a->p);mv(z->p,w->p,wn=n>wn?wn:n);
 if(n-=wn)mv(z->p+wn,z->p,n);R z;}
V1(sha){A z=ga(0,1,&w->r);mv(z->p,w->d,w->r);R z;}
V1(id){R w;}V1(size){A z=ga(0,0,0);*z->p=w->r?*w->d:1;R z;}
pi(i){P("%d ",i);}nl(){P("\n");}
pr(w)A w;{I r=w->r,*d=w->d,n=tr(r,d);DO(r,pi(d[i]));nl();
 if(w->t)DO(n,P("< ");pr(w->p[i]))else DO(n,pi(w->p[i]));nl();}

C vt[]="+{~<#,";
A(*vd[])()={0,plus,from,find,0,rsh,cat},
 (*vm[])()={0,id,size,iota,box,sha,0};
I st[26]; qp(a){R  a>='a'&&a<='z';}qv(a){R a<'a';}
A ex(e)I *e;{I a=*e;
 if(qp(a)){if(e[1]=='=')R st[a-'a']=ex(e+2);a= st[ a-'a'];}
 R qv(a)?(*vm[a])(ex(e+1)):e[1]?(*vd[e[1]])(a,ex(e+2)):(A)a;}
noun(c){A z;if(c<'0'||c>'9')R 0;z=ga(0,0,0);*z->p=c-'0';R z;}
verb(c){I i=0;for(;vt[i];)if(vt[i++]==c)R i;R 0;}
I *wd(s)C *s;{I a,n=strlen(s),*e=ma(n+1);C c;
 DO(n,e[i]=(a=noun(c=s[i]))?a:(a=verb(c))?a:c);e[n]=0;R e;}

main(){C s[99];while(gets(s))pr(ex(wd(s)));}
```

It's a lot to take in --- it's quite breathtaking really, the way it all
hangs together in one page.

#### The attempt to get it run

Unfortunately, this does not work if we try to get it to run in 2020. I decided
to read the code and understand what would happen. I managed to read enough
to understand that the code `a=~3` ought to create an array with values `[0 1 2]`.
On attempting to _run_ this however, we get:

```
$ gcc -O0 -g -std=c89 -fsanitize=address -fsanitize=undefined incunabulum.c -o bin/incunabulum && ./bin/incunabulum
...
(many many GCC warnings elided)
...
a=~3
=================================================================
==23726==ERROR: AddressSanitizer: heap-buffer-overflow on address 
  0x60300000eff0 at pc 0x000000402be3 bp 0x7ffe6dde6b70 sp 0x7ffe6dde6b60
WRITE of size 8 at 0x60300000eff0 thread T0
    #0 0x402be2 in wd /home/bollu/work/w/incunabulum.c:40
    #1 0x402d28 in main /home/bollu/work/w/incunabulum.c:42
    #2 0x7f7ae901082f in __libc_start_main (/lib/x86_64-linux-gnu/libc.so.6+0x2082f)
    #3 0x400ca8 in _start (/home/bollu/w/bin/incunabulum+0x400ca8)
...
SUMMARY: AddressSanitizer: heap-buffer-overflow /home/bollu/work/w/incunabulum.c:40 wd
...
==23726==ABORTING
```

oops! The code uses a lot of punning between `int`
and `int*`. These assumptions break now that we're in 64-bit. The patch to
get this to work is:

#### the patch

```patch
diff --git a/incunabulum.c b/incunabulum.c
index 2cae744..778e35a 100644
--- a/incunabulum.c
+++ b/incunabulum.c
@@ -1,11 +1,11 @@
-typedef char C;typedef long I;
+typedef char C;typedef long long I;
 typedef struct a{I t,r,d[3],p[2];}*A;
 #define P printf
 #define R return
 #define V1(f) A f(w)A w;
 #define V2(f) A f(a,w)A a,w;
 #define DO(n,x) {I i=0,_n=(n);for(;i<_n;++i){x;}}
-I *ma(n){R(I*)malloc(n*4);}mv(d,s,n)I *d,*s;{DO(n,d[i]=s[i]);}
+I *ma(n){R(I*)malloc(n*8);}mv(d,s,n)I *d,*s;{DO(n,d[i]=s[i]);}
 tr(r,d)I *d;{I z=1;DO(r,z=z*d[i]);R z;}
 A ga(t,r,d)I *d;{A z=(A)ma(5+tr(r,d));z->t=t,z->r=r,mv(z->d,d,r);
  R z;}
@@ -34,9 +34,10 @@ I st[26]; qp(a){R  a>='a'&&a<='z';}qv(a){R a<'a';}
 A ex(e)I *e;{I a=*e;
  if(qp(a)){if(e[1]=='=')R st[a-'a']=ex(e+2);a= st[ a-'a'];}
  R qv(a)?(*vm[a])(ex(e+1)):e[1]?(*vd[e[1]])(a,ex(e+2)):(A)a;}
-noun(c){A z;if(c<'0'||c>'9')R 0;z=ga(0,0,0);*z->p=c-'0';R z;}
-verb(c){I i=0;for(;vt[i];)if(vt[i++]==c)R i;R 0;}
+I noun(c){A z;if(c<'0'||c>'9')R 0;z=ga(0,0,0);*z->p=c-'0';R z;}
+I verb(c){I i=0;for(;vt[i];)if(vt[i++]==c)R i;R 0;}
 I *wd(s)C *s;{I a,n=strlen(s),*e=ma(n+1);C c;
  DO(n,e[i]=(a=noun(c=s[i]))?a:(a=verb(c))?a:c);e[n]=0;R e;}
 
 main(){C s[99];while(gets(s))pr(ex(wd(s)));}
+
```

#### It runs!

After applying the patch, we manage to get the interpreter to run!

```
./bin/incunabulum
a=~3
3 
0 1 2 
```

#### The lock screen

I liked it so much that I took a screenshot and made it my lock screen.

![screenshot-j-incunabulum](static/screenshot-j-incunabulum.png)

#### Thoughts

I'm really fascinated by the code. I loved I could simply stare the screenshot
to absorb the code. There was no scrolling involved.  The variables are
well-named (to the extent I understand the code), and it's clearly extremely
well thought out. If there's someone who understands some of the thorny
aspects of the code:

- What is the `t` variable really tracking?
- How does one create a multi-dimensional array easily?
- What are some interesting programs one can run with this mini-interpreter?

I'd be really glad to know the details. Please leave [an issue or a pull request
against the repo](https://github.com/bollu/bollu.github.io/issues/new).

I'm going write a dissection of the code once I fully understand it, since I
couldn't find explanaing the code on the internet. 

Until then, enjoy the monolith of code!


# [An example of a sequence whose successive terms get closer together but isn't Cauchy (does not converge)](#an-example-of-a-sequence-whose-successive-terms-get-closer-together-but-isnt-cauchy-does-not-converge)

#### The problem
Provide an example of a sequence $a_n: \mathbb N \rightarrow \mathbb R$
such that $\lim_{n \rightarrow \infty} \vert a_{n+1} - a_n \vert \rightarrow 0$,
but $\lim_{n, m \rightarrow \infty, m > n} |a_n - a_m| \neq 0$. That is,
proide a series where the distances between successive terms converges to zero,
but where distances between terms that are "farther apart than 1" does
not converge to 0. That is, the sequence is not _Cauchy_.

#### Regular solution: Harmonic numbers

The usual solution is to take the harmonic numbers,
$H_n \equiv \sum_{i=1}^n 1/i$. Then, we show that:

$$
\begin{aligned}
\lim_{n \rightarrow \infty} \left| H_{n+1} - H_n \right|
&= \left| \frac{1}{n+1} - \frac{1}{n} \right| \\
&= \frac{1}{(n+1)n} \rightarrow 0
\end{aligned}
$$

$$
\begin{aligned}
\lim_{n \rightarrow \infty} \left|H_{2n} - H_n \right|
&= \left|\frac{1}{2n} - \frac{1}{n} \right| \\
&= \sum_{i=n+1}^{2n} \frac{1}{n+1} + \frac{1}{n+2} + \dots + \frac{1}{2n} \\
&\geq \sum_{i=n+1}^{2n} \frac{1}{2n} + \frac{1}{2n} + \dots + \frac{1}{2n} \\
&\geq \frac{n}{2n} = \frac{1}{2} \not \xrightarrow{x \rightarrow \infty} 0 \\
\end{aligned}
$$


#### Memorable solution: logarithm

We can much more simply choose $a_n = \log(n)$. This yields the simple
calculation:

$$
\begin{aligned}
\lim_{n \rightarrow \infty} a_{n+1} - a_n = \log(n+1) - \log(n) 
= \log((n+1)/n))
= \log(1 + 1/n) \xrightarrow{n \rightarrow \infty} \log(1) = 0
\end{aligned}
$$

while on the other hand,


$$
\begin{aligned}
\lim_{n \rightarrow \infty} a_{2n} - a_n 
= \log(2n) - \log(n) 
= \log(2) + \log(n) - \log(n)
= \log 2 \neq 0
\end{aligned}
$$

I find this far cleaner conceptually, since it's "obvious" to everyone
that $a_n = \log(n)$ diverges, while the corresponding fact for $H_n$
is hardly convincing. We also get straightforward equalities everywhere,
instead of inequalities. 

I still feel that I don't grok what precisely fails here, in that, my intuition
still feels that the local condition _ought_ to imply the Cauchy condition:
if $a_n$ tells $a_{n+1}$ to not be too far, and $a_{n+1}$ tells $a_{n+2}$,
surely this _must_ be transitive?

I have taught my instincts to not trust my instincts on analysis, which is a
shitty solution :) I hope to internalize this someday.

__EDIT:__ I feel I now understand what's precisely happening
after ruminating a bit.

The Cauchy convergence criterion allows us to drop a finite number
of terms, and then capture _everything after that point_ in a ball
of radius $\epsilon$. As $\epsilon$ shrinks, _all_ the terms in the
sequence are "squeezed togeher".

In the $a_{n+1} - a_n$ case, only successive terms must maintain
an $\epsilon$ distance. But as the $\log$ example shows, you can steadily
plod along, keeping $\epsilon$ ball next to $\epsilon$ ball, to reach:

$$
\lim_{n \rightarrow \infty} \lim_{\epsilon \rightarrow 0} f(n) \cdot \epsilon
$$
whose behaviour can do unexpected things depending on the choice of $\n$.

# [Krylov subspace method](#krylov-subspace-method)

<!-- https://www.youtube.com/watch?v=R9DHmkCE9oI -->

This is a class of methods used to solve $Ax = b$, where $A$ is sparse.
Krylov subspace methods are a class of methods which use the idea of a
Krylov subspace. There is conjugate gradient (CG), GMRES (Generalized minimal
residual method).

$$
K_m(A, v) \equiv span \{ v, Av, A^2v, \dots, A^m v\}
$$

Clearly, $K_m \subseteq K_{m+1}$, and there is a maximum $K_N$ that we can span
(the full vector space). We are interested in the smallest index $M$ 
such that $K_M = K_{M+1}$.

We notice that $K_M$ is invariant under the action of $A$.


Now, let's consider:
$$
\begin{aligned}
K_m(A, x) &\equiv span \{x, Ax, A^2x, \dots A^m x \} \\
        &= span \{ A^{-1} b, b, Ab, \dots A^{m-1} x \} \qquad \text{(substitute $x = A^{-1}b$)} \\
        &= A span \{ A^{-1} b, b, Ab, \dots A^{m-1} b\} \qquad \text{(Invariance of Krylov subspace)} \\
        &= span \{b, Ab, \dots A^m b\}  \\
        &= K_m(A, b)
\end{aligned}
$$

We learnt that $Ax = b$ has a solution in $K_m(A, b)$. Using this, we can build
solvers that exploit the Krylov subspace. We will describe GMRES and CG.

## Generalized minimal residual --- GMRES

We wish to solve $Ax = b$ where $A$ is sparse and $b$ is normalized. The $n$th
Krylov subspace is $K_n(A, b) \equiv span~\{b, Ab, A^2b, \dots, A^nb  \}$.

We approximate the actual solution with a vector $x_n \in K_n(A, b)$. We
define the _residual_ as $r_n \equiv A x_n - b$.

## Conjugate gradient descent

# [Good reference to the Rete pattern matching algorithm](#good-reference-to-the-rete-pattern-matching-algorithm)

The [Rete pattern matching algorithm](https://en.wikipedia.org/wiki/Rete_algorithm)
is an algorithm that allows matching a huge number of rules with a huge database
of "facts".

MLIR ("multi-language intermediate representation") is a new technology that
hopes to centralize much of the research and development of various compilers
into a single authoritative source. The major claim-to-fame is that it allows
one to mix various "dialects" (much as Racket does). So, to a first order
approximation, MLIR is "JSON for compiler intermediate representations".

What MLIR gets right is _tooling_. They take the experience that the LLVM project
has mined for the last decade and a half, and bake many of the good stuff that
came with LLVM right in. For example, MLIR comes in-built with a pretty printer,
a notion of types, a notion of "attributes", SSA, enforced provenance
tracking of code (so one can _always_ know what the original source code was
that led to some assembly). Sound engineering might see MLIR succeed where
many others failed.

I was reminded of Rete since the MLIR folks are trying to solve the pattern
matching problem in general for their [Generic DAG Rewriter](https://mlir.llvm.org/docs/GenericDAGRewriter/).

They currently just use a worklist based algorithm. I'm trying to understand
if Rete can be used instead. Rete is famous for being hard to understand,
so I began a quest to look for good sources to implement it. I found a great 
[PhD thesis written by Robert B. Doorenboos](http://reports-archive.adm.cs.cmu.edu/anon/1995/CMU-CS-95-113.pdf),
which quips:

> Since the Rete match algorithm provides the starting point for much of the work in this thesis,
> this chapter describes Rete. Unfortunately, most of the descriptions of Rete in the literature
> are not particularly lucid,1 which is perhaps why Rete has acquired \a reputation for extreme
> differentialculty."(Perlin, 1990b) To remedy this situation, this chapter describes Rete in a tutorial
> style, rather than just briey reviewing it and referring the reader to the literature for a full
> description. We will rst give an overview of Rete, and then discuss the principle data structures
> and procedures commonly used to implement it. High-level pseudocode will be given for many
> of the structures and procedures, so that this chapter may serve as a guide to readers who want
> to implement Rete (or some variant) in their own systems.

I now have a reference to an accessible description of this stuff. I might
implement Rete to understand it, so that it's part of my toolkit if I ever
need it.

# [Leapfrog Integration](#leapfrog-integration)

We have a system we wish to simulate using hamilton's equations:

$$
\begin{aligned}
\frac{\partial q}{\partial t} = \frac{\partial H}{\partial p}|_{(p_0, q_0)} \\
\frac{\partial p}{\partial t} = -\frac{\partial H}{\partial q}|_{(p_0, q_0)} \\
\end{aligned}
$$

We want to simulate a system using these differential equations. We will begin
with some initial position and momentum $(q_0, p_0)$, evaluate
$\frac{\partial q}{\partial t} \rvert_{(q_0, p_0)}$, $\frac{\partial p}{\partial t} \rvert_{(q_0, p_0)}$, and use
these to find $(q_{next}, p_{next})$. An integrator is a general algorithm
that produces the next position and momentum using current information:

$$
(q_{next}, p_{next}) = 
  I \left(q_0, 
    p_0,
    \frac{\partial q}{\partial t}\rvert_{(q_0, p_0)},
    \frac{\partial p}{\partial t}\rvert_{(q_0, p_0)} \right)
$$

The design of $I$ is crucial: different choices of $I$ will have different
trade-offs for accuracy and performance. Another interesting property
we might want is for $I$ to be a _symplectic integrator_ --- that is,
it preserves the total energy of the system. For example, here's a plot
of the orbits of planets using two integrators, one that's symplectic (leapfrog)
and one that isn't (Euler)

![leapfrog-integration](static/leapfrog-vs-euler.png)

Notice that since leapfrog attempts to keep energy conserved, the orbits stay
as orbits! On the other hand, the euler integrator quickly spirals out, since
we lose energy during the integration. Note that this is _not an
issue of numerical precision_: The euler integrator is ineherently such that
over long timescales, it will lose energy. On the other hand, the leapfrog
integrator will _always remain stable_, even with very large timesteps
and low precision. 

I present the equations of the leapfrog integrator, a proof sketch that it
is symplectic, and the code listing that was used to generate the above plot.
Often, code makes most ideas very clear!

#### The integrator


#### Code listing

##### Incantations 
```py
# Run HMC with a particular choice of potential
import numpy as np
from matplotlib.animation import FuncAnimation
import matplotlib.pyplot as plt
import numpy.linalg
```

```py
# dq/dt = dH/dp|_{p0, q0}
# dp/dt = -dH/dq|_{p0, q0}
def leapfrog(dhdp, dhdq, q0, p0, dt):
    p0 += -dhdq(q0, p0) * 0.5 * dt 

    # full step position
    # q += dt * p 
    q0 += dhdp(q0, p0) * dt
    
    # half step position
    p0 += -dhdq(q0, p0) * 0.5 * dt 
    return (q0, p0)
```

For reference, we also implement an euler integrator, that uses the derivative
to compute the position and momentum of the next timestep independently.

```py
def euler(dhdp, dhdq, q, p, dt):
    pnew = p + -dhdq(q, p) * dt
    qnew = q + dhdp(q, p) * dt
    return (qnew, pnew)
```


Finally, we implement `planet(integrator, n, dt)` which simulates gravitational
potential and usual kinetic energy, using the integrator given by `integrator`
for `n` steps, with each timestep taking `dt`.

```py
def planet(integrator, n, dt):
    STRENGTH = 0.5

    # minimise potential V(q): q, K(p, q) p^2
    q = np.array([0.0, 1.0])
    p = np.array([-1.0, 0.0])
    
    # H = STRENGTH * |q| (potential) + p^2/2 (kinetic)
    def H(qcur, pcur): return STRENGTH * np.linalg.norm(q) + np.dot(p, p) / 2
    def dhdp(qcur, pcur): return p
    def dhdq(qcur, pcur): return STRENGTH * 2 * q / np.linalg.norm(q)
    
    qs = []
    for i in range(n):
        print("q: %10s | p: %10s | H: %6.4f" % (q, p, H(q, p)))
        (q, p) = integrator(dhdp, dhdq, q, p, dt)
        qs.append(q.copy())
    return np.asarray(qs)
```


We plot the simulations using `matplotlib` and save them.
```py
NITERS = 15
TIMESTEP = 1

print("planet simulation with leapfrog")
planet_leapfrog = planet(leapfrog, NITERS, TIMESTEP)

plt.rcParams.update({'font.size': 12, 'font.family':'monospace'})
fig, ax = plt.subplots()
print(planet_leapfrog)
ax.plot(planet_leapfrog[:, 0], planet_leapfrog[:, 1], label='leapfrog',
        linewidth=3, color='#00ACC1')
print("planet simulation with euler")
planet_euler = planet(euler, NITERS, TIMESTEP)
ax.plot(planet_euler[:, 0], planet_euler[:, 1], label='euler',
        linewidth=3, color='#D81B60')

legend = plt.legend(frameon=False)
ax.set_title("leapfrog v/s euler: NITERS=%s dt=%s" % (NITERS, TIMESTEP))
ax.spines['top'].set_visible(False)
ax.spines['right'].set_visible(False)
ax.spines['bottom'].set_visible(False)
ax.spines['left'].set_visible(False)
plt.savefig("leapfrog-vs-euler.png")
plt.show()
```

# [Comparison of forward and reverse mode AD](#comparison-of-forward-and-reverse-mode-ad)

Quite a lot of ink has been spilt on this topic. My favourite reference
is the one by [Rufflewind](https://rufflewind.com/2016-12-30/reverse-mode-automatic-differentiation).

However, none of these examples have a good stock of examples for the diference.
So here, I catalogue the explicit computations between computing forward
mode AD and reverse mode AD.

In general, in forward mode AD, we fix how much the inputs wiggle with
respect to a parameter $t$. We figure out how much the output wiggles
with respect to $t$. If $output = f(input_1, input_2, \dots input_n)$,
then $\frac{\partial output}{\partial t} = \sum_i \frac{\partial f}{\partial input_i} \frac{\partial input_i}{\partial dt}$.

In reverse mode AD, we fix how much the parameter $t$ wiggles with
respect to the output. We figure out how much the parameter $t$
wiggles with respect to the inputs.
If $output_i = f_i(input, \dots)$, then $\frac{\partial t}{\partial input} = \sum_i \frac{\partial t}{\partial output_i} \frac{\partial f_i}{input}$.
This is a much messier expression, since we need to accumulate the data
over all outputs. 

Essentially, deriving output from input is easy, since how to compute an output
from an input is documented in one place. deriving input from output is
annoying, since many outputs can depent on a single output.

The upshot is that if we have few "root outputs" (like a loss function),
we need to run AD once with respect to this, and we will get the wiggles
of _all inputs_ at the same time with respect to this output, since we 
compute the wiggles output to input. 

The first example of `z = max(x, y)` captures the essential difference
between the two approached succinctly. Study this, and everything else will make
sense.


#### Maximum: `z = max(x, y)`


- Forward mode equations:

$$
\begin{aligned}
z &= max(x, y) \\
\frac{\partial x}{\partial t} &= ? \\
\frac{\partial y}{\partial t} &= ? \\
\frac{\partial z}{\partial t} 
  &= \begin{cases}
        \frac{\partial x}{\partial t} & \text{if $x > y$} \\
        \frac{\partial y}{\partial t} & \text{otherwise} \\
    \end{cases}
\end{aligned}
$$

We can compute $\frac{\partial z}{\partial x}$ by setting $t = x$.
That is, $\frac{\partial x}{\partial t} = 1, \frac{\partial y}{\partial t} = 0$.
Similarly, can compute $\frac{\partial z}{\partial y}$ by setting $t = y$.
That is, $\frac{\partial x}{\partial t} = 1, \frac{\partial y}{\partial t} = 0$.
If we want both gradients $\frac{\partial z}{\partial x}, \frac{\partial z}{\partial y}$,
we will have to **rerun the above equations twice** with the two initializations.

In our equations, we are saying that we know how sensitive
the inputs $x, y$ are to a given parameter $t$. We are deriving how sensitive
the output $z$ is to the parameter $t$ as a composition of $x, y$. If 
$x > y$, then we know that $z$ is as sensitive to $t$ as $x$ is.


- Reverse mode equations:

$$
\begin{aligned}
z &= max(x, y) \\
\frac{\partial t}{\partial z} &= ? \\
\frac{\partial t}{\partial x}
  &= \begin{cases}
    \frac{\partial t}{\partial z} & \text{$if x > y$} \\
    0 & \text{otherwise}
  \end{cases} \\
\frac{\partial t}{\partial y}
  &= \begin{cases}
    \frac{\partial t}{\partial z} & \text{$if y > x$} \\
    0 & \text{otherwise}
  \end{cases}
\end{aligned}
$$

We can compute $\frac{\partial z}{\partial x}, \frac{\partial z}{\partial y}$
**in one shot** by setting $t = z$. That is, $\frac{\partial z}{\partial t} = 1$.

In our equations, we are saying that we know how sensitive
the parameter $t$ is to a given output $z$. We are trying to see
how sensitive $t$ is to the inputs $x, y$. If $x$ is active (ie, $x > y$),
then $t$ is indeed sensitive to $x$ and $\frac{\partial t}{\partial x} = 1$.
Otherwise, it is not sensitive, and $\frac{\partial t}{\partial x} = 0$.


#### sin: `z = sin(x)`

- Forward mode equations:

$$
\begin{aligned}
z &= sin(x) \\
\frac{\partial x}{\partial t} &= ? \\
\frac{\partial z}{\partial t} 
  &= \frac{\partial z}{\partial x} \frac{\partial x}{\partial t} \\
  &= cos(x) \frac{\partial x}{\partial t}
\end{aligned}
$$

We can compute $\frac{\partial z}{\partial x}$ by setting $t = x$.
That is, setting $\frac{\partial x}{\partial t} = 1$.

- Reverse mode equations:

$$
\begin{aligned}
z &= sin(x) \\
\frac{\partial t}{\partial z} &= ? \\
\frac{\partial t}{\partial x}
  &= \frac{\partial t}{\partial z} \frac{\partial z}{\partial x} \\
  &= \frac{\partial t}{\partial z} cos(x)
\end{aligned}
$$


We can compute $\frac{\partial z}{\partial x}$ by setting $t = z$.
That is, setting $\frac{\partial z}{\partial t} = 1$.

#### addition: `z = x + y`:

- Forward mode equations:

$$
\begin{aligned}
z &= x + y \\
\frac{\partial x}{\partial t} &= ? \\
\frac{\partial y}{\partial t} &= ? \\
\frac{\partial z}{\partial t} 
  &= \frac{\partial z}{\partial x} \frac{\partial x}{\partial t} + 
    \frac{\partial z}{\partial y} \frac{\partial y}{\partial t} \\
  &= 1 \cdot \frac{\partial x}{\partial t} + 1 \cdot \frac{\partial y}{\partial t}
  = \frac{\partial x}{\partial t} + \frac{\partial y}{\partial t}
\end{aligned}
$$


- Reverse mode equations:

$$
\begin{aligned}
z &= x + y \\
\frac{\partial t}{\partial z} &= ? \\
\frac{\partial t}{\partial x}
  &= \frac{\partial t}{\partial z} \frac{\partial z}{\partial x} \\
  &= \frac{\partial t}{\partial z} \cdot 1 = \frac{\partial t}{\partial z} \\
\frac{\partial t}{\partial y}
  &= \frac{\partial t}{\partial z} \frac{\partial z}{\partial y} \\
  &= \frac{\partial t}{\partial z} \cdot 1 = \frac{\partial t}{\partial z}
\end{aligned}
$$


#### multiplication: `z = xy`

- Forward mode equations:

$$
\begin{aligned}
z &= x y \\
\frac{\partial x}{\partial t} &= ? \\
\frac{\partial y}{\partial t} &= ? \\
\frac{\partial z}{\partial t} 
  &= \frac{\partial z}{\partial x} \frac{\partial x}{\partial t} + 
    \frac{\partial z}{\partial y} \frac{\partial y}{\partial t} \\
  &= y \frac{\partial x}{\partial t} + x \frac{\partial y}{\partial t}
\end{aligned}
$$

- Reverse mode equations:

$$
\begin{aligned}
z &= x y \\
\frac{\partial t}{\partial z} &= ? \\
\frac{\partial t}{\partial x}
  &= \frac{\partial t}{\partial z} \frac{\partial z}{\partial x} 
  = \frac{\partial t}{\partial z} \cdot y \\
\frac{\partial t}{\partial y}
  &= \frac{\partial t}{\partial z} \frac{\partial z}{\partial y}
  = \frac{\partial t}{\partial z} \cdot x
\end{aligned}
$$


#### subtraction: `z = x - y`:

- Forward mode equations:

$$
\begin{aligned}
z &= x + y \\
\frac{\partial x}{\partial t} &= ? \\
\frac{\partial y}{\partial t} &= ? \\
\frac{\partial z}{\partial t} 
  &= \frac{\partial z}{\partial x} \frac{\partial x}{\partial t} -
    \frac{\partial z}{\partial y} \frac{\partial y}{\partial t} \\
  &= 1 \cdot \frac{\partial x}{\partial t} - 1 \cdot \frac{\partial y}{\partial t}
  = \frac{\partial x}{\partial t} - \frac{\partial y}{\partial t}
\end{aligned}
$$

- Reverse mode equations:

$$
\begin{aligned}
z &= x - y \\
\frac{\partial t}{\partial z} &= ? \\
\frac{\partial t}{\partial x}
  &= \frac{\partial t}{\partial z} \frac{\partial z}{\partial x} \\
  &= \frac{\partial t}{\partial z} \cdot 1 = \frac{\partial t}{\partial z} \\
\frac{\partial t}{\partial y}
  &= \frac{\partial t}{\partial z} \frac{\partial z}{\partial y} \\
  &= \frac{\partial t}{\partial z} \cdot -1 = -\frac{\partial t}{\partial z}
\end{aligned}
$$


# [An invitation to homology and cohomology, Part 1 --- Homology](#an-invitation-to-homology-and-cohomology-part-1--homology)

There are many introductions to homology on the internet, but none of them
really met my criteria for being simple, picture filled, and getting the
basic ideas across. I feel that Hatcher might come closest to what I want 
(and where I originally learnt the material), but their description of homology
is surrounded by the context of Algebraic Topology, while really, simplicial
homology is accessible to anyone who has seen some linear algebra and group
theory. This is my attempt to get the ideas across.

Let's first try to understand what we're trying to do here. We want to detect
holes in a space, broadly construed. We focus in _simplicial complexes_, which
are collections of triangles and triangle-like objects in higher (and lower)
dimensions. We define what holes are for these simplicial complexes, and we then
try to find algebraic objects that allow us to "detect" these holes.

### Simplices
- A 0-simplex is a point
![0-simplex](static/simplices/0-simplex.svg)

- A 1-simplex is a line
![1-simplex](static/simplices/1-simplex.svg)

- A 2-simplex is a filled triangle
![2-simplex](static/simplices/2-simplex.svg)


- A 3-simplex is a solid tetrahedra
![3-simplex](static/simplices/3-simplex.svg)

- A $k$-dimensional simplex is the convex hull of $k+1$
  linearly independent points $(u_i \in \mathbb R^{k+1})$
  in $k+1$ dimensional space.
  $ S_k \equiv \left \\{ \sum \theta_i u_i ~\mid~ \theta_i \geq 0, ~ \sum_i \theta_i = 1 \right\\} $

### Simplicial complexes

A simplicial complex $K$ is a collection of simplices where:
- (1) Every boundary of a simplex from $K$ is in $K$
- (2) The intersection of any two simplices in $K$ is also in $K$

Examples of simplicial complexes:

- Every simplex is trivially a simplicial complex.

![points](static/simplices/complex-0-simplices.svg)
- A collection of points is a simplicial complex with all simplices of degree $0$.

![unfilled-tri](static/simplices/complex-unfilled-triangle.svg)
- An unfilled triangle is a simplicial complex with simplices of degree $0$, $1$.

![complex-unfilled-butterfly](static/simplices/complex-unfilled-butterfly.svg)
- Non-triangular shapes such  as this "butterfly" are also simplicial complexes,
  this one of degree $0$, $1$.

![complex-half-filled-butterfly](static/simplices/complex-half-filled-butterfly.svg)
- This is the same shape as the unfilled butterly, except now containing a
  simplex of degree 2: the filling in of the bottom of the butterfly.


Non-examples of simplicial complexes are:

![non-simplex-1](static/simplices/non-simplex-1.svg)
- This does not contain the point at the lower-left corner, which should exist
  since it is a boundary of the straight line. This violates rule (1):
  Every boundary of a simplex from $K$ is in $K$


![non-simplex-2](static/simplices/non-simplex-2.svg)
- This does not contain the points which are at the intersection of the
  triangle and the line. This violates rule (2):
  The intersection of any two simplices in $K$ is also in $K$.

### Holes in a space: Homology of a triangle

Let's consider the simplest possible case of computing the homlogy, and we
do so, we will expand on what homology _is_, and what we're trying to do.

![homology-triangle-edges](static/simplices/homology-triangle-edges.svg)

Look at the triangle above. We have the red, green, and blue vertices, which
I'll notate $r, g, b$. We also have the edges that are orange ($o$), cyan ($c$), and
magenta ($m$).

What we are interested in doing is to be able to detect the "hole" in the
triangle in between the edges `o-m-c`. That is, we want some algorithm which
when offered the representation of the triangle, can somehow detect the hole.
Note that the hole doesn't really depend on the length of the edges. We can
"bend and stretch" the triangle, and the hole will still exist. The only way
to destroy the hole is to either _cut_ the triangle, or _fill in_ the triangle.

We first need to agree on an abstract _representation_ of the triangle,
which ideally does not change if we were to stretch out the edges,
before we can discuss how we can detect the existence of the hole.

##### Representation of the triangle: boundary operators

We first describe the shape of the triangle in terms
of two sets, $E$ and $V$ representing the edges and the vertices, and
a function $\partial_{EV}$, called as the 
boundary operator, which tells us how edges
are glued to vertices.

We first have a ground set of edges $E \equiv \\{o, m, c\\}$ and a set of
vertices $V \equiv \\{r, g, b \\}$. 

What we now need is to know how the edges are connected to the vertices,
since that's what really makes a triangle. We would like to say something
like "the boundary of the edge $o$ has points $r, g$". In fact, we have
slightly more information than that: the _orientation_. So what we 
really ought to be saying is "the edge $o$ points from $g$ to $r$".

To do this, we create a map from $o$ to $r - g$, where we think of $o$
as a "vector", pointing from $g$ to $r$. But hang on, what _is_ $r - g$?
we don't have a mathematical structure on $V$ that lets us add and subtract
vertices. So, we _create_ a new set $\mathcal V$, which represents linear
combinations of vertices in $V$. Similarly, anticipating some future
development, we also _create_ a new set $\mathcal E$ of linear combinations
of edges $E$.

##### Formal definition of the boundary operator

We define $\mathcal E \equiv \mathbb Z \times \mathbb Z \times \mathbb Z$
that represents linear combinations of edges. For example, $(1, 2, 3) \in \mathcal E$
represents $o + 2m + 3c$ --- that is, take 1 copy of the orange edge, 2
copies of the magenta edge, and 3 copies of the cyan edge.

We define $\mathcal V \equiv \mathbb Z \times \mathbb Z \times \mathbb Z$
which represents linear combinations of vertices. For example,
$(1, -1, 2) \in V$ represents $r - g + 2b$ --- that is, take a copy of the
red vertex, subtract the green vertex, and add two copies of the blue vertex.

The boundary operator $\partial_{EV}: \mathcal{E} \rightarrow \mathcal V$ is
depicted in the picture. This operator sends edges to their _boundary_, and is
therefore called the _boundary operator_.  The _boundary_ of an edge describes
the edge in terms of vertices, just like we would describe a direction vector
(to borrow physics parlance) by subtracting points.

The action of the operator on a linear combination of edges is:

$$
\begin{aligned}
&\partial_{EV}: \mathcal E \rightarrow \mathcal V \\
&\partial_{EV}(1, 0, 0) \equiv (1, -1, 0) \qquad o \mapsto r - g \\
&\partial_{EV}(0, 1, 0) \equiv (-1, 0, 1) \qquad m \mapsto b - r \\
&\partial_{EV}(0, 0, 1) \equiv (0, 1, -1) \qquad c \mapsto b - g \\
&\text{(Extend using linearity)} \\
&\partial_{EV}(s, t, u) \equiv 
  s \partial_{EV}(1, 0, 0) + 
  t \partial_{EV}(0, 1, 0) + 
  u \partial_{EV}(0, 0, 1) = (s - t, u - s, t - u)
\end{aligned}
$$

Now, notice that to traverse the cycle, we should traverse the orange edge, 
then the magenta edge, then the cyan edge, in that direction. That is,
the cycle can be thought of as $o + m + c$. However, how do we _detect_ this
cycle? The key idea is that if we look at the 
_image of the cycle $o + m + c$ under the boundary operator_ $\partial_{EV}$,
we will get $0$! For us to have completed a cycle, we must have both
entered and exited each vertex, so the total sum must be $0$.

Formally:

$$
\begin{aligned}
  &\partial_{EV}(s, t, u) \equiv (s - t, u - s, t - u) \\
  &o + m + c = (1, 1, 1) \in \mathcal E \quad
  \partial_{EV}((1, 1, 1) = (1 - 1, 1 - 1, 1 - 1) = (0, 0, 0)
\end{aligned}
$$

##### Formal definition of cycles

This is very nice, since we have converted the topological invariant
of a _hole in the space_ into an algebraic invariant of "linear combination
of edges that map to 0". That is, we want to consider all thoose loops
that belong to the _kernel_ of $\partial_{EV}$. (Terminology: 
the kernel of a linear transformation is the set of all things in the domain
which map to zero)

So, we define (tentatively) the first homology group:

$$
\begin{aligned}
H_1 \equiv Kernel(\partial_{EV}) \equiv
\left \{ (a, b, c) \in \mathcal E \mid \partial_EV((a, b, c)) = (0, 0, 0) \right \}
\subset \mathcal E
\end{aligned}
$$

If we try to compute this, we will have to have:

$$
\begin{aligned}
H_1 &\equiv Kernel(\partial_{EV}) \\
&= \{ (s, t, u) ~\mid~ \partial_{EV}(s, t, u) = (0, 0, 0) ~ s, t, u \in \mathbb Z \} \\
&= \{ (s, t, u) ~\mid~ (s-t, u-s, t-u) = (0, 0, 0) ~ s, t, u \in \mathbb Z  \} \\
&= \{ (s, t, u) ~\mid~ s = t = u \quad s, t, u \in \mathbb Z \} \\
&= \{ (x, x, x) ~\mid~ x \in \mathbb Z \} \simeq \mathbb Z
\end{aligned}
$$

So, we know that we have a $\mathbb Z$ worth of cycles in our triangle, which
makes sense: We can go clockwise (positive numbers)
and counter-clockwise (negative numbers) around the triangle,
and we can go as many times as we wish, so we have $\mathbb Z$ as the
number of cycles.

that is, it's the linear combination of edges that map to zero through the
boundary map. Note that this also includes combinations such as _two_ loops
around the triangle, such as $o + m + c + o + m + c$.

### (No) Holes in a space: Homology of a _filled_ triangle

![homology-triangle-faces](static/simplices/homology-triangle-faces.svg)

In this case, notice that the triangle is _filled_ with a face $f$.
Therefore, the "hole" that we had previously is now filled up, and does not
count anymore. So, we now need to amend our previous definition of $H_1$ to
kill the hole we had detected. 

The idea is that the hole we had previously is now the
_boundary of the new face $f$_.
Since it is the boundary of a "filled in" region, it does not count anymore,
since we can "shrink the hole" across the face to make it a non-loop.
Hence, we need to quotient our $H_1$ with the boundary of the face.

Formally, what we do is we create another group $\mathcal F \equiv \mathbb Z$,
which counts copies of our face $f$, and we define another boundary operator,
such that the boundary of the face $f$ is $o + m + c$.

$$
\begin{aligned}
&\partial_{FE} : \mathcal F \rightarrow \mathcal E \\
&\partial_{FE}(1) \equiv (1, 1, 1)  \\
&\text{(Extend using linearity)} \\
&\partial_{FE}(c) \equiv c \partial(1) = (c, c, c)
\end{aligned}
$$

Now, we should notice that the _image_ of $\partial_{FE}$ is a loop
$(o + m + c)$, which lies ie the _kernel_ of $\partial_{EV}$. This is a
general feature of homology, so it bears repeating:

- $Image(\partial_{FE}) \subset Kernel(\partial_{EV})$
- $\partial_{FE} \circ \partial_{EV} = 0$
- The above equation is sometimes stylishly (somewhat misleadingly) written as
  $\partial^2 = 0$. More faithfully, one can write $\partial_{EV} \circ \partial_{FE} = 0$.

Now, since the image of $\partial_{FE}$ lies entirely in the kernel of $\partial_{EV}$,
we can construct $H_1$ as:

- $H_1 \equiv Kernel(\partial_{EV}) / Image(\partial_{FE}) \subset E$


### A complicated space: Homology of a butterfly


# [An invitation to homology and cohomology, Part 2 --- Cohomology](#an-invitation-to-homology-and-cohomology-part-2--cohomology)

<!--
f is closed <=> df = 0
f is exact <=> f = dg
-->

![cohomology-triangle-vertices](static/simplices/cohomology-triangle-vertices.svg)

Once again, we have our humble triangle with vertices $V = \\{r, g, b\\}$,
edges $E = \\{o, m, c \\}$, faces $F = \\{ f \\}$ with boundary maps $\partial_{EV}$,
$\partial_{FE}$:

- $\partial_{FE}(f)= o + m + c$
- $\partial_{EV}(o) = r - g$
- $\partial_{EV}(m) = b - r$
- $\partial_{EV}(c)= g - b$

We define a function $h_v: V \rightarrow \mathbb R$ on the vertices as:
-  $h_v(r) = 3$, $h_v(g) = 4$, $h_v(b) = 10$.

We now learn how to _extend_ this function to the higher dimensional objects,
the edges and the faces of the triangle.

To extend this function to the edges, we define a new function:

- $h_e: E \rightarrow R$
- $h_e(e) \equiv \sum_i \alpha_i h_v(v_i)$ where $\partial_{EV} e = \sum_i \alpha_i v_i$

Expanded out on the example, we evaluate $h_v$ as:

- $h_e(o) \equiv d h_v(o)  = h_v(r) - h_v(g) = 3 - 4 = -1$
- $h_e(m) \equiv d h_v(m)  = h_v(b) - h_v(r) = 10 - 3 = +7$
- $h_e(c) \equiv d h_v(c)  = h_v(g) - h_v(b) = 4 - 10 = -6$

More conceptually, we have created an _operator_ called $d$ (the **coboundary operator**)
which takes functions defined on vertices to functions defined on edges. This
uses the boundary map on the edges to "lift" a function on the vertices to a
function on the edges.  It does so by assigning the "potential difference" of
the vertices to the edges.


- $d: (V \rightarrow \mathbb R) \rightarrow (E \rightarrow \mathbb R)$
- $d(h_v) \equiv h_e$, $h_e(e) \equiv \sum_i \alpha_i f(v_i)$ where $\partial_{EV} e = \sum_i \alpha_i v_i$


We can repeat the construction we performed above, to construct another operator
$d : (E \rightarrow \mathbb R) \rightarrow (F \rightarrow \mathbb R)$, defined
in _exactly the same way_ as we did before. For example, we can evaluate:

- $h_f \equiv d(h_e)$
- $h_f(f) \equiv d h_e(f) = h_e(o) + h_e(m) + h_e(c) = -1 + 7 -6 = 0$

What we have is a chain:

- $h_v \xrightarrow{d} h_e \xrightarrow{d} h_f$

Where we notice that $d^2 = d \circ d = 0$, since the function $h_f$ that we have gotten
evaluates to zero on the face $f$. We can prove this will happen _in general_,
for any choice of $h_v$. 
(it's a good exercise in definition chasing).


Introducing some terminology, A differential form $f$ is said to be a **closed differential form**
iff $df = 0$.

In our case, $h_e$ **is closed**, since $d h_e = h_f = 0$. On the other hand
$h_v$ is **not closed**, since $d h_v = h_e \neq 0$.

The intuition for why this is called "closed" is that its coboundary vanishes.

## Exploring the structure of functions defined on the edges

Here, we try to understand what functions defined on the edges can look like,
and their relationship with the $d$ operator. We discover that there are 
some functions $g_e: E \rightarrow \mathbb R$ which can be realised as the differential
of another function $g_v: V \rightarrow \mathbb R$. The differential 
forms such as $g_e$ which can be generated a $g_v$ through the $d$ operator
are called as **exact differential forms**. That is, $g_e = d g_v$ _exactly_,
such that there is no "remainder term" on applying the $d$ operator.

![cohomology-triangle-edges](static/simplices/cohomology-triangle-edges.svg)

We take an example of a differential form that is _not exact_, which has been
defined on the edges of the triangle above. Let's call it $h_e$.

It is defined on the edges as:
- $h_e(c) = 3$
- $h_e(m) = 2$
- $h_e(o) = 1$

We can calcuate $h_f = d h_e$ the same way we had before:
- $h_f(f) \equiv d h_e(f) = h_e(o) + h_e(m) + h_e(c) = 3 + 1 + 2 = 6$.

Since $d h_e \neq 0$, this form is not exact.

Let's also try to generate $h_e$ from a potential. We arbitrarily fix the
potential of $b$ to $0$. That is, we fix $h_v(b) = 0$, and we then try to
see what values we are forced to values of $h_v$ across the rest of the triangle.

- $h_v b = 0$ 
- $h_e(c) = h_v(g) - h_v(b)$. $h_v(g) =  h_v(b) + h_e(c) = 0 + 3 = 3$.
- $h_e(o) = h_v(r) - h_v(g)$. $h_v(r) =  h_v(g) + h_e(o) = 3 + 1 = 4$.
- $h_e(m) = h_v(b) - h_v(r)$ $2 = 0 - 4$. This is a contradiction!
- Ideally, we need $h_v(b) = 6$ for the values to work out.


Hence, there can exist no such $h_v$ such that $h_e \equiv d h_v$.
The interesting thing is, when we started out by assigning $h_v(b) = 0$,
we could make _local choices_ of potentials that seemed like they would fit
together, but they failed to fit _globally_ throughout the triangle. This
failure of _locally consistent choices_ to be _globally consistent_ is
the essence of cohomology.

# Cohomology of half-filled butterfly

![cohomology-half-filled-butterfly](static/simplices/cohomology-half-filled-butterfly.svg)

Here, we have vertices $V \equiv \\{ r, g, b, b, p \\}$, edges
$E \equiv \\{rb, gr, bg, m, o, c \\}$ and faces $F \equiv \\{ f \\}$.

Here, we see a differential form $h_e$ that is defined on the edges,
and also obeys the equation $dh_e = 0$ (Hence is closed). However, it 
_does not have an associated potential energy_ to derive it from. That is,
there cannot exist a certain $h_v$ such that $d h_v = h_e$.


So, while every exact form is closed, _not every_ closed form is exact.

Hence, this $g$ that we have found is a non-trivial element of $Kernel(d_{FE}) / Image(d_{EV})$,
since $dh_e = 0$, hence $h_e \in Kernel(d_{FE})$, while there does not exist
a $h_v$ such that $d h_v = h_e$, hence it is _not quotiented_ by the image of
$d_{EV}$.

So the failure of the space to be fully filled in (ie, the space has a hole),
is measured by the _existence of a function $h_e$ that is closed but not exact!_

This reveals a deep connection between homology and cohomology, which is
made explicit by the [Universal Coefficient Theorem](TODO)

# [Stuff I learnt in 2019](#stuff-i-learnt-in-2019)

I write these retrospective blog posts every year since 2017. I tend to post a
collection of papers, books, and ideas I've stumbled across that year.
Unfortunately, this year, the paper list will be sparser, since I lost some
data along the way to the year, and hence I don't have links to everything I
read. So this is going to be a sparser list, consisting of things that I found
_memorable_.

I also re-organised my website, letting the link die, since keeping it up was
taking far too many cycles (In particular, CertBot was far too annoying to
maintain, and the feedback of hugo was also very annoying). I now have a 
_single_ file, the
[`README.md`of the `bollu/bollu.github.io`](https://github.com/bollu/bollu.github.io)
repo,
to which I add notes on things I find interesting. I've bound the `i` alias 
(for idea) on all my shells everywhere, to open the `README.md` file, wait
for me to write to it, run a `git commit` so I can type out a commit, and 
then push. This has been _massive_ for what I manage to write down: I feel
like I've managed to write down a lot of one-liners / small facts that I've
picked up which I would not otherwise. I'm attempting to similarly pare down
other friction-inducing parts of my workflow. Suggestions here would be very 
welcome!


If there's a theme of the year (insofar as my scattered reading has a
theme...), it's "lattices and geometry". Geometry in terms of differential
geometry, topology, and topoi. Lattices in the sense of a bunch of abstract
interpretation and semantics.

#### Course work: optimisation theory, quantum computation, statistics

My course work was less interesting to me this time, due to the fact that I had
chosen to study some wild stuff earlier on, and now have to take reasonable stuff
to graduate. However, there were courses that filled in a lot of gaps in my
self-taught knowledge for me, and the ones I listed were the top ones in that
regard.

I wound up reading
[Boyd on optimisation theory](https://web.stanford.edu/~boyd/cvxbook/), 
[Nielsen and Chuang](http://mmrc.amss.cas.cn/tlb/201702/W020170224608149940643.pdf) for quantum computation,
where I also
[solved a bunch of exercises in Q#](https://github.com/bollu/quantum-course-exercises) 
which was very fun and rewarding. I'm beginning to feel that learning quantum
computation is the right route to grokking things like entanglement and
superposition, unlike the physics which is first of all much harder due to
infinite dimensionality, and less accessible since we can't _program_ it.

#### Formal research work: Compilers, Formal verification, Programming languages

My research work is on the above topics, so I try to stay abreast of what's
going on in the field. What I've read over the past year on these topics is:


- [`A^2I`: meta-abstract interpretation](https://popl19.sigplan.org/details/POPL-2019-Research-Papers/71/A-2-I-Abstract-2-Interpretation).
  This paper extends the theory of abstract interpretation to perform abstract
  interpretation on program analyses themselves. I'm not sure how _useful_ this
  is going to be, as I still hold on to the belief that AI as a framework is
  too general to allow one to prove complex results. But I am still interested
  in trying to adapt this to some problems I have at hand. Perhaps it's going
  to work.


- [Cubicial Agda](https://dl.acm.org/citation.cfm?id=3341691). This paper introduces
  cubical type theory and its implementation in Agda. It appears to solve many
  problems that I had struggled with during my formalization of loop
  optimisations: In particular, dealing with Coinductive types in Coq, and that
  of defining quotient types / setoids. Supposedly, cubical Agda makes dealing
  with Coinduction far easier. It allows allows the creation of "real" quotient
  types that respect equality, without having to deal with `setoid` style
  objects that make for large Gallina terms. I don't fully understand how the
  _theory_ works: In particular, as far as I can tell, the synthetic interval
  type `I` allows one to only access the start and end points (`0` and `1`),
  but not anything in between, so I don't really see how it allows for
  interpolation.  I also don't understand how this allows us to make Univalence
  computable.  I feel I need to practice with this new technology before I'm
  well versed, but it's definitely a paper I'm going to read many, many times
  till I grok it.


- [Naive Cubical type theory](https://arxiv.org/abs/1911.05844). This paper
  promises a way to perform informal reasoning with cubical type theory, the
  way we are able to do so with, say, a polymorphic type theory for lambda
  calculus. The section names such as "how do we think of paths",
  "what can we do with paths", inspire confidence

- [Call by need is Clairvoyant call by value](https://icfp19.sigplan.org/details/icfp-2019-papers/26/Call-By-Need-is-Clairvoyant-Call-By-Value). This key insight is to notice that call by need
  is "just" call by value, when we evaluate only those values that are
  eventually forced, and throw away the rest. Thus, if we had an oracle that
  tells us which values are eventually forced, we can convert call by need into
  call by value, relative to this oracle. This cleans up many proofs in the
  literature, and might make it far more intuitive to teach call by need to
  people as well. Slick paper, I personally really enjoyed reading this.

- [Shift/Reset the Penultimate Backpropagator](https://arxiv.org/abs/1803.10228)
  This paper describes how to implement backprop using delimited continuations.
  Also, supposedly, using staging / building a compiler out of this paradigm
  allows one to write high performance compilers for backprop without having
  to suffer, which is always nice.


- [Closed forms for numerical loops](https://www.cs.princeton.edu/~zkincaid/pub/popl19a.pdf)
  This paper introduces a new algebra of polynomials with exponentials. It then
  studies the eigenvalues of the matrix that describes the loop, and tries to
  find closed forms in terms of polynomials and exponentials. They choose
  to only work with rationals, but not extensions of rational numbers
  (in terms of field extensions of the rationals). Supposedly, this is easier
  to implement and reason about. Once again, this is a paper I'd like to
  reimplement to understand fully, but the paper is well-done!


- [Composable, sound transformations of Nested recursion and loops](https://engineering.purdue.edu/Papers/Sundararajah.pdf). 
  This paper attempts to bring ideas from polyhedral compilation
  into working with nested recursion. They create a representation using
  multitape finite automata, using which they provide a representation for
  nested recursion. I was somewhat disappointed that it does not handle
  mutual recursion, since my current understanding is that one can always
  convert nested recursion into a "reasonable" straight line program by 
  simply inlining calls and then re-using polyhedral techniques. 


- [Reimplementation of `STOKE` at `bollu/blaze`.](https://github.com/bollu/blaze/blob/master/notebooks/tutorial.ipynb)
  I reimplemented the [STOKE: stochastic superoptimisation](http://stoke.stanford.edu/)
  paper, and much to my delight, it was super-effective at regenerating common
  compiler transformations. I want to use this to generate loop optimisations
  as well, by transforming a polyhedral model of the original program.
  

#### Internship at [Tweag.io](http://tweag.io/) over the summer: Hacking on Asterius (Haskell -> WebAssembly compiler)

- [Blog post on the progress made by me hacking on Austerius over at Tweag](https://www.tweag.io/posts/2019-09-12-webassembly-internship.html)

I really enjoyed my time at Tweag! It was fun, and
[Shao Cheng](https://github.com/TerrorJack)
was a great mentor. I must admit that I was somewhat distracted, by all the new
and shiny things I was learning thanks to all the cool people there `:)` In
particular, I wound up bugging 
[Arnaud Spiwack](http://assert-false.net/arnaud/), 
[Simeon Carstens](http://simeon-carstens.com/),
and [Matthias Meschede](https://github.com/mmesch)
quite a bit, about type theory, MCMC sampling, and signal processing of storm
clouds.

I wound up reading a decent chunk of GHC source code, and while I can't link
to specifics here, I understood a lot of the RTS much better than I did before.
It was an enlightening experience, to say the least, and being paid to hack on
a GHC backend was a really fun way to spend the summer.

It also led me to fun discoveries, such as
[how does one debug debug info?](https://github.com/ghc/ghc/blob/535a26c90f458801aeb1e941a3f541200d171e8f/compiler/cmm/Debug.hs#L458)


I also really loved Paris as a city. My AirBnb host was a charming artist who
suggest spots for me around the city, which I really appreciated. Getting
around was disorienting for the first week or so, due to the fact that I could
not (and still do not) really understand how to decide in which direction to
walk inside the subways to find a particular line _going in a particular
direction_.

The city has some great spots for quiet work, though! In particular, the
[Louvre Anticafe](https://www.anticafe.eu/lieux/louvre-paris-75001/)
was a really nice place to hang out and grab coffee. The model is great: you
pay for hours spent at the Anticafe, with coffee and snacks free. They also
had a discount for students which I gratefully used. 
I bumped into interesting artists, programmers, and students who were open for
conversation there. I highly recommend hanging out there. 

#### Probabilistic programming & giving a talk at FunctionalConf

This was the first talk I'd ever given, and it was on probabilistic programming
in haskell. In particular, I explained the
[`monad-bayes`](https://github.com/adscib/monad-bayes) approach of
doing this, and why this was profitable. 
[The slides are available here](https://github.com/bollu/functionalconf-2019-slides-probabilistic-programming/blob/master/slides.pdf).


It was a fun experience giving a talk, and I'd like to do more of it, since I
got a lot out of attempting to explain the ideas to people. I wish I had more
time, and had a clearer idea of who the audience was. I got quite a bit of
help from [Michael Snoyman](https://www.snoyman.com/) to whip the talk into
shape, which I greatly appreciated.

The major ideas of probabilistic programming as I described it are
from Adam Scibior's thesis:

- [Adam Scibior: Formally justified and modular Bayesian inference for probabilistic programs](https://www.cs.ubc.ca/~ascibior/assets/pdf/thesis.pdf)

Along the way, I and others at tweag read the other major papers in the space,
including:

- [Church, a language for generative models](https://arxiv.org/pdf/1206.3255), 
  which is nice since it describes it's semantics in terms of sampling. This is
  unlike Adam's thesis, where they define the denotational semantics in terms
  of measure theory, which is then approximated by sampling.


- [Riemann Manifold Langevin and Hamiltonian Monte Carlo](https://pdfs.semanticscholar.org/16c5/06c5bb253f7528ddcc80c72673fabf584f32.pdf)
  which describes how to perform Hamiltonian Monte Carlo on the _information
  geometry_ manifold.  So, for example, if we are trying to sample from
  gaussians, we sample from a 2D Riemannian manifold with parameters mean and
  varince, and metric as the [Fisher information metric](https://en.wikipedia.org/wiki/Fisher_information_metric).
  This is philosophically the "correct" manifold to sample from, since it
  represents the intrinsic geometry of the space we want to sample from.

- [An elementary introduction to Information geometry by Frank Nielsen](https://arxiv.org/pdf/1808.08271.pdf)
  something I stumbled onto as I continued reading about sampling from
  distributions. The above description about the "correct" manifold for
  gaussians comes from this branch of math, but generalises it quite a bit
  further. I've tried to reread it several times as I gradually gained maturity
  in differential geometry. I can't say I understand it just yet, but I hope to
  do so in a couple of months. I need more time for sure to meditate on the
  objects.

- [Reimplementation of `monad-bayes`](https://github.com/bollu/shakuni).
  This repo holds the original implementation on which the talk is based on.
  I read through the `monad-bayes` source code, and then re-implemented the
  bits I found interesting. It was a nice exercise, and you can see
  the git history tell a tale of my numerous mis-understandings of MCMC methods,
  till I finally got what the hell was going on.

#### Presburger Arithmetic

Since we use a bunch of [presburger arithmetic](https://en.wikipedia.org/wiki/Presburger_arithmetic)
for [polyhedral compilation](http://polyhedral.info/)
which is a large research interest of mine, I've been trying to build a
"complete" understanding of this space. So this time, I wanted to learn
how to build good solvers:

- [`bollu/gutenberger`](https://github.com/bollu/gutenberger) is a decision
  procedure for Presburger arithmetic that exploits their encoding as finite
  automata. One thing that I was experimenting with was that we only use
  numbers of finite bit-width, so we can explore the entire state space
  of the automata and then perform NFA reduction using
  [DFA minimisation](https://en.wikipedia.org/wiki/DFA_minimization). The
  reference I used for this was the excellent textbook
  [Automata theory: An algorithmic approach, Chapter 10](https://www7.in.tum.de/~esparza/autoskript.pdf)


- [The taming of the semi-linear set](http://www.lsv.fr/~haase/documents/ch16.pdf)
  This uses a different encoding of presburger sets, which allows them to bound
  a different quantity (the norm) rather than the bitwidth descriptions. This allows
  them to compute _exponentially_ better bounds for some operations than
  were known before, which is quite cool. This is a paper I keep trying to
  read and failing due to density. I should really find a week away from civilization
  to just plonk down and meditate upon this.
  
##### Open questions for which I want answers

I want better references to being able to _regenerate_ the inequalities
description from a given automata which accepts the presburger set automata.
This will allow one to smoothly switch between the _geometric_ description
and the _algebraic_ description. There are some operations that only work
well on the geometry (such as optimisation), and others that only work well on
the algebraic description (such as state-space minimisation). I have not found
any good results for this, only scattered fragments of partial results.
If nothing else, I would like some kind of intuition for _why this is hard_. 

Having tried my stab at it, the general impression that I have is that the
space of automata is much larger than the things that can be encoded as
presburger sets. Indeed, it was shown that automata accept numbers which
are ultimately periodic. 

-  first order logic + "arithmetic with +" + (_another operation I cannot recall_).
   I'm going to fill this in once I re-find the reference.

But yes, it's known that automata accept a language that's broader than just
first order logic + "arithmetic with +", which means it's hard to dis-entangle
the presburger gits from the non-presburger bits of the automata. 
  
  
#### Prolog

I wanted to get a better understading of how prolog works under the hood, so I began
re-implementing the [WAM: warren abstract machine](http://wambook.sourceforge.net/).
It's really weird, this is the _only stable reference_ I can find to implementing
high-performance prolog interpreters. I don't really understand how to chase the
paper-trail in this space, I'd greatly appreciate references. My implementation
is at [`bollu/warren-cpp`](https://github.com/bollu/warren-cpp/). Unfortunately,
I had to give up due to a really hard-to-debug bug.

It's crazy to debug this abstract machine, since the internal representation gets
_super convoluted_ and hard to track, due to the kind of optimised encoding it
uses on the heap.

If anyone has a better/cleaner design for implementing good prologs, I'd love
to know.

Another fun paper I found in this space thanks to Edward Kmett was
[the Rete matching algorithm](http://www.drdobbs.com/architecture-and-design/the-rete-matching-algorithm/184405218),
which allows one to declare many many pattern matches, which are then "fused"
together into an optimal matcher that tries to reuse work across failed
matchers.

#### General Relativity

This was on my "list of things I want to understand before I die", so I wound
up taking up an Independent Study in university, which basically means that
I study something on my own, and visit a professor once every couple weeks,
and am graded at the end of the term. For GR, I wound up referencing a wide
variety of sources, as well as a bunch of pure math diffgeo books. I've read
everything referenced to various levels. I feel I did take away the core
ideas of differential and Riemannian geometry. I'm much less sure I've grokked
general relativity, but I can at least read the equations and I know all the
terms, so that's something.

- [The theoretical minimum by Leonard Susskind](https://theoreticalminimum.com/courses/general-relativity/2012/fall).
  The lectures are breezy in style, building up the minimal theory (and no proofs)
  for the math, and a bunch of lectures spent analysing the physics. While I wish
  it were a little more proof heavy, it was a really great reference to learn the
  basic theory! I definitely recommend following this and then reading other
  books to fill in the gaps.

- [Gravitation by Misner Thorne and Wheeler](https://en.wikipedia.org/wiki/Gravitation_(book))
  This is an imposing book. I first read through the entire thing (Well, the parts I thought I needed),
  to be able to get a vague sense of what they're going for. They're rigorous in
  a very curious way: It has a bunch of great _physics_ perspectives of looking
  at things, and that was invaluable to me. Their view of forms as "slot machines"
  is also fun. In general, I found myself repeatedly consulting this book for
  the "true physical" meaning of a thing, such as curvature, parallel transport,
  the equation of a geodesic, and whatnot.

- [Differential Geometry of Curves and Surfaces by do Carmo](http://www2.ing.unipi.it/griff/files/dC.pdf)
  This is the best book to intro differential geometry I found. It throws away
  all of the high powered definitions that "modern" treatments offer, and
  starts from the ground up, building up the theory in 2D and 3D. This is amazing,
  since it gives you small, computable examples for things like
  "the Jacobian represents how tangents on a surface are transformed locally".

- [Symplectic geometry & classical mechanics by Tobias Osborne](https://www.youtube.com/watch?v=pXGTevGJ01o&list=PLDfPUNusx1EoVnrQcCRishydtNBYU6A0c)
  This lecture series was great, since it re-did a lot of the math I'd seen
  in a more physicist style, especially around vector fields, flows, and
  Lie brackets. Unfortunately for me, I never even _got_ to the classical
  mechanics part by the time the semester ended. I began 
  [taking down notes in my repo](https://github.com/bollu/notes/blob/master/diffgeo/main.pdf), 
  which I plan to complete.

- [Introduction to Smooth manifolds: John Lee](https://sites.math.washington.edu/~lee/Books/ISM/)
  This was a very well written _mathematical_ introduction to differential geometry. 
  So it gets to the physically important bits (metrics, covariant derivatives)
  far later, so I mostly used it as a reference for problems and more rigour.


- [Einstein's original paper introducing GR, translated](http://hermes.ffn.ub.es/luisnavarro/nuevo_maletin/Einstein_GRelativity_1916.pdf)
  finally made it click as to _why_
  he wanted to use tensor equations: tensor equations of the form `T = 0` are
  invariant in _any coordinate system_, since on change of coordinates, `T`
  changes by a multiplicative factor! It's a small thing in hindsight, but it
  was nice to see it explicitly spelled out, since as I understand, no one
  among the physicists knew tensor calculus at the time, so he had to introduce
  all of it.

#### Discrete differential geometry

I can't recall how I ran across this: I think it was because I was trying to
get a better understanding of Cohomology, which led me to Google for 
"computational differential geometry", that finally led me to Discrete
differential geometry.

It's a really nice collection of theories that show us how to discretize
differential geometry in low dimensions, leading to rich intuitions and
a myriad of applications for computer graphics.

- [The textbook by Kennan Crane on the topic](https://www.cs.cmu.edu/~kmcrane/Projects/DDG/paper.pdf) 
  which I read over the summer when I was stuck (more often than I'd like) in
  the Paris metro. The book is very accessible, and requires just some
  imagination to grok. Discretizing differential geometry leads to most things
  being linear algebra, which means one can calculate things on paper easily.
  That's such a blessing.

- [Geodesics in Heat](https://arxiv.org/pdf/1204.6216)
  explores a really nice way to discover geodesics by simulating the heat
  equation for a short time. The intuition is that we should think of the heat
  equation as describing the evolution of particles that are performing random
  walks. Now, if we simulate this system for a short while and then look at the
  distribution, particles that reach a particular location on the graph _must
  have taken the shortest path_, since any longer path would not have allowed
  particles to reach there. Thus, the distribution of particles at time `dt`
  does truly represent distances from a given point.  The paper explores this
  analogy to find accurate geodesics on complex computational grids. This is
  aided by the use of differential geometry, appropriately discretized.

- [The vector heat method](https://arxiv.org/pdf/1805.09170.pdf)
  explores computing the parallel transport of a vector across a discrete
  manifold efficiently, borrowing techniques from the 'Geodesics in Heat'
  paper.

- [Another paper by Kennan Crane: Lie group integrators for animation and control of vehicles](https://www.cs.cmu.edu/~kmcrane/Projects/LieGroupIntegrators/paper.pdf)
  This paper describes a general recipe to tailor-make integrators for a system
  of constraints, by directly integrating over the lie group of the
  configuration space.  This leads to much more stable integrators. I have some
  misguided hope that we can perhaps adapt these techniques to build better FRP
  (functional reactive programming) systems, but I need to meditate on this a
  lot more to say anything definitively.

  
  

#### Synthetic differential geometry

It was [Arnaud Spiwack](http://assert-false.net/arnaud/)
who pointed me to this. It's a nice axiomatic
system of differential geometry, where we can use physicist style proofs of
"taking stuff upto order `dx`", and having everything work upto mathematical
rigor.

The TL;DR is that we want to add a new number called `dx` into the reals,
such that `dx^2 = 0`. But if such a number did exist, then clearly `dx = 0`.
However, the punchline is that to prove that `dx^2 = 0 => dx = 0` requires
the use of contradiction!

So, if we banish the law of excluded middle (and therefore no longer use
proof by contradiction), we are able to postulate the existence of a new
element `dx`, which obeys `dx^2 = 0`. Using this, we can build up the
whole theory of differential geometry in a pleasing way, without having to
go through the horror that is real analysis. (I am being hyperbolic, but really,
real analytic proofs are not pleasant).

[I began formalizing this in Coq and got a formalism going: `bollu/diffgeo`](https://www.github.com/bollu/diffgeo).

Once I was done with that, I realised I don't know how to exhibit _models_ of
the damn thing! So, reading up on that made me realise that I need around 8
chapters worth of a grad level textbook (the aptly named 
[Models of Smooth Infinitesimal Analysis](https://link.springer.com/book/10.1007/978-1-4757-4143-8)).

I was disheartened, so I [asked on `MathOverflow`](https://mathoverflow.net/questions/346385/constructing-computable-synthetic-differential-geometry)
(also my first ever question there), where I learnt about tangent categories and
differential lambda calculus. Unfortunately, I don't have the bandwidth to read
another 150-page tome, so this has languished.


### Optimisation on Manifolds

I began reading
[Absil: Optimisation on matrix manifolds](http://www.eeci-institute.eu/GSC2011/Photos-EECI/EECI-GSC-2011-M5/book_AMS.pdf)
which describes how to perform optimisation / gradient descent on 
_arbitrary Riemannian manifolds_, as well as closed forms for well-known
manifolds. The exposition in this book is really good, since it picks a
concrete manifold and churns out all the basic properties of it manually. The
only problem I had with the books was that there were quite a few gaps (?) in
the proofs -- perhaps I missed a bunch.

This led me to learn Lie theory to some degree, since that was the natural
setting for many of the proofs. I finally saw _why_ anyone gives a shit about
the tangent space at the identity: because it's _easier to compute!_ For a
flavour
of this, [consider this question on `math.se` by me that asks about computing
tangent spaces of $O(n)$](https://math.stackexchange.com/questions/3389983/explicit-description-of-tangent-spaces-of-on).

#### AIRCS workshop

I attended the
[AI risk for computer scientists](https://intelligence.org/ai-risk-for-computer-scientists/)
workshop hosted by
[MIRI (Machine intelligence research institute)](https://intelligence.org/) in 
December. Here, a bunch of people were housed at a bed & breakfast for a
week, and we discussed AI risk, why it's potentially the most important thing
to work on, and anything our hearts desired, really. I came away with new
branches of math I wanted to read, a better appreciation of the AI risk
community and a sense of what their "risk timelines" were, and some
explanations about sheaves and number theory that I was sorely lacking. All in
all, it was a great time, and I'd love to go back. 

#### P-adic numbers

While I was on a particularly rough flight back from the USA to India when
coming back from the AIRCS workshop, I began to read the textbook
[Introduction to p-adic numbers by Fernando Gouvea](https://www.springer.com/gp/book/9783540629115),
which fascinated me, so I then
[wrote up the cool parts introduced in the first two chapters as a blog post](http://bollu.github.io/#a-motivation-for-p-adic-analysis).
I wish to learn more about the p-adics and p-adic analysis, since they
seem to be deep objects in number theory.

In particular, a question that I thought might have a somewhat trivial answer
([why do the p-adics use base p in defining norm](https://math.stackexchange.com/questions/3482489/why-does-the-p-adic-norm-use-base-p))
turned out to have answers that were quite deep, which was something
unexpected and joyful!

#### Topology of functional programs

- [Slides by Martın Escardo](http://cs.ioc.ee/ewscs/2012/escardo/slides.pdf)
- [Synthetic topology of data types and classical spaces](https://pdf.sciencedirectassets.com/272990/1-s2.0-S1571066104X00177/1-s2.0-S1571066104051357/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIGQAb828p1io4csznEej60j0PwJteuXf7OoHLSCDhkUTAiEA9ITs1JrUEOE%2Ft%2Fl5TI9ZkNLUfBIx42IZ%2FoAqQpdX4twq2AII6%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARACGgwwNTkwMDM1NDY4NjUiDBQOxJ3s3HCbVxSheCqsAt65yorZMMtIhLF7ML5sJQ9S5wZxBayKDrRkUKOjSzXxtQWebXs70FXhhpToXKvJoDrLgsqDzdF%2FAshZY%2FkDUep6KILxKnYxCBrBINhjFqxDlRZH0s1Y991RgCyNNnwmFI%2BrH70lSrV0OxQ9Z5WdXXPDkTLXv8512Xz%2BJn5DqEqdqD49FLbOuHl6PRM0TnYyNJkLBXNVwt75kkGkaTfdgmgiqh7YpcXcHlbqI2oqNcaxFDewXwKDCC7qWD6ECclLgszoeOXOtRI91nvNac8%2BLV4bXkKLXpd99H94N2vXPUPz99p6oqfdY9ixtcfI9POFX8agUilYjXKVhAWk4FSzzzMqbtZLBfkCZT4ffDTxRgL52yD%2FmL5E0Pe4mczVlUoB5DKoB8Lkitrt0BumQzDr4ffvBTrQAjVRuzG5V0CC%2Fd1t%2BUMPkrywaYytbrXCZ%2BkDo0xDBqsljY8DaGIiFINr8BEEpT7UX42GRhcDzpnOnztdAOTea3qZ3SmXJwgEoh0aiz%2B87MmsC57s0Q%2F%2B%2FDDvHBY3zLCrz7rdewXOgk6VxI9d5mhG3Du1dwPRbgOe798S2waDCD8LQA3rw7w5wNGa9Uv3xtNVH%2BHw%2FXcQ6OiubO4GL9mK8U5g7TVPh1hLB26XBQooKJ564VGf4J9VqWxjlx3NicVhqnFlGevNJNKyVLiyRsRCyQGMV59%2BXqUwdEMQZYWLbfUwELNz1NKfWumvu9BXC5jjsJgNx%2FRERSb7hqT1svMJU91o%2FHtatGAnPvVjYaNthha9O9jm%2BG9nw1vMsdyJ0asI5w5SrlsEyb5C7Vk7aLBcHAEi3XPRhivY1Q4hZAN0xY9VfEZrF%2FoM9HCGxr5cYs%2BP9w%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20191221T113658Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY6QRXTPOC%2F20191221%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=8a26656e8f8c8772afdc2ae6caa9b583fd59a8ee6303d9770d25b4a3d8a6291f&hash=42518d3e5cc1e77ed961c359d0ea8f59bd582d1e5f13d69c3eeb2563a6c82abd&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S1571066104051357&tid=spdf-584e8188-4806-44bb-a118-9b63a53caaff&sid=f53691052392834d3e18a62484e2909639a9gxrqb&type=client)

Both of these describe a general method to transfer all topological ideas as
statements about _computability_ in a way that's far more natural (at least for
me, as a computer scientist). The notion of what a continuous function "should
be" (keeping inverse images of open sets open) arises naturally from this
computational viewpoint, and many proofs of topology amount to finding
functional programs that fit a certain type. It's a great read, and I feel gave
me a much better sense of what topology is trying to do.

- [I've written some exposition on this topic](http://bollu.github.io/#topology-is-really-about-computation--part-1),
  which maybe a more accessible read than the links above, since it tries to
  distill the fundamental idea into a blog post.

#### Philosophy

I've wanted to understand philosophy as a whole for a while now, at least
enough to get a general sense of what happened in each century. The last year,
I meandered through some philosophy of science, which led me to some really
wild ideas (such as that of
[Paul Feyerabend's 'science as an anarchic enterprise'](https://en.wikipedia.org/wiki/Epistemological_anarchism) 
which I really enjoyed).

I also seem to get a lot more out of audio and video than text in general, so
I've been looking for podcasts and video lectures. I've been following:

- [The history of philosophy without any gaps](https://historyofphilosophy.net/)
  for a detailed exposition on, say, the greeks, or the arabic philosophers.
  Unfortunately, this podcast focuses on far too much detail for me to have been
  able to use it as a way to get a broad idea about _philosophy_ in itself.

- [Philosophize This! by Stephen West](http://philosophizethis.org/)
  Is a good philosophy podcast for a _broad_ overview of different areas
  of Philosophy. I got a lot out of this, since I was able to get a sense
  of the progression of ideas in (Western) Philosophy. So I now know what
  [Phenomenology](https://plato.stanford.edu/entries/phenomenology/) is, 
  or what Foucault was reacting against.


I also attempted to read a bunch of philosophers, but the only ones I could
make a good dent on were the ones listed below. I struggled in writing this
section, since it's much harder to sanity check my understanding of philosophy,
versus mathematics, since there seems to be a range of interpretations of the
same philosophical work, and the general imprecise nature of language doesn't
help here at all. So please take all the descriptions below with some salt 
to taste.

- [Discipline and Punish by Michel Foucault](https://en.wikipedia.org/wiki/Discipline_and_Punish)
  Here, Foucault traces the history of the criminal justice system of society,
  and how it began as something performed 'on the body' (punishment),
  which was then expanded to a control 'of the mind' (reform). As usual,
  the perspective is fun, and I'm still going through the book.

- [Madness and Civilization by Michel Foucault](https://en.wikipedia.org/wiki/Madness_and_Civilization)
  which attempts to chronicle how our view of madness evolved as society did.
  It describes how madmen, who were on the edges of society, but still
  "respected" (for exmaple, considered as 'being touched by the gods') were
  pathologized by the Renaissance, and were seen as requiring treatment. I'm
  still reading it, but it's enjoyable so far, as a new perspective for me.

  
- [The value of science by Henri Poincare](https://en.wikipedia.org/wiki/The_Value_of_Science).
  Here, he defends the importance of experimentation, as well as the value of
  intuition to mathematics, along with the importance of what we consider
  formal logic. It's a tough read sometimes, but I think I got something out of
  it, at least in terms of perspective about science and mathematics.

#### Information theory

I've been on a quest to understand information theory far better than I
currently do. In general, I feel like this might be a much better way to
internalize probability theory, since it feels like it states probabilistic
objects in terms of "couting" / "optimisation of encodings", which is a 
perspective I find far more natural.

Towards this aim, I wound up reading:

- [Information theory, Learning, and inference algorithms](http://www.inference.org.uk/mackay/itila/book.html)
  This book attempts to provide the holistic view I was hoping for. It has
  great illustrations of the basic objects of information theory. However,
  I was hoping that the three topics would be more "unified" in the book,
  rather than being presented as three separate sections with some amount
  of back-and-forth-referencing among them. Even so, it was a really fun read.

- [Elements of information theory](http://www.cs-114.org/wp-content/uploads/2015/01/Elements_of_Information_Theory_Elements.pdf)

#### Building intuition for Sheaves, Topoi, Logic

I don't understand the trifecta of sheaves, topoi, geometry, and logic, and
I'm trying to attack this knot from multiple sides at once.

- [Understanding networks and their behaviours using sheaf theory](https://arxiv.org/pdf/1308.4621)
- [Sheaves, objects, and distributed systems](https://www.sciencedirect.com/science/article/pii/S1571066108005264)
- [Sheaves are the canonical data strucure for sensor integration](https://arxiv.org/pdf/1603.01446.pdf)
- [Elementary applied topology, Chapter 9: Sheaves](https://www.math.upenn.edu/~ghrist/EAT/EATchapter9.pdf)
- [Sheaf theory: The mathematics of data fusion (video) (link to HackerNews)](https://news.ycombinator.com/item?id=13677308)

All of these provide geometric viewpoints of what sheaves are, in low-dimensional
examples of graphs which are easy to visualize. I'm also trudging through the
tome:

- [Sheaves in geometry and logic: A first introduction to Topos theory](https://www.springer.com/gp/book/9780387977102)

which appears to follow the "correct path" of the algebraic geometers, but this
requires a lot of bandwidth.

- [The Rising Sea: foundations of algebraic geometry by Ravi Vakil](http://math.stanford.edu/~vakil/216blog/FOAGnov1817public.pdf)

This is a hardcore algebraic geometry textbook, and is arguably 
_great for studying sheaves_ because of it. Sheaves are Chapter 2, and allows
one to see them be developed in their "true setting" as it were. In that
Grothendeick first invented sheaves for algebraic geometry, so it's good to
see them in the home they were born in. Once again, this is a book I lack
bandwidth for except to breezily read it as I go to bed. I did get something
out from doing this. I'm considering taking this book up as an independent
study, say the first four chapters. I'll need someone who knows algebraic
geometry to supervise me, though, which is hard to find in an institute geared
purely for computer science. (If anyone on the internet is kind enough to
volunteer some of their time to answer questions, I'll be very glad! Please
email me at `rot13(fvqqh.qehvq@tznvy.pbz)`)

#### The attic

This section contains random assortments that I don't recall how I stumbled
across, but too cool to not include on the list. I usually read these in bits
and pieces, or as bedtime reading right before I go to bed to skim.  I find
that skimming such things gives me access to knowing about tools I would not
have known otherwise. I like knowing the existence of things, even if I don't
recall the exact thing, since knowing that something like `X` exists has saved me
from having to reinvent `X` from scratch.

- [Group Theory: Birdtracks, Lie's and Exceptional Groups by Predrag Cvitanovic](http://www.cns.gatech.edu/GroupTheory/version9.0/GroupTheory.pdf)
  is an exposition of Lie theory using some notation called as "Birdtrack notation",
  which is supposedly a very clean way of computing invariants, inspired by
  Feynmann notation. The writing style is informal and pleasant, and I decided
  to save the book purely because the first chapter begins with
  "Basic Concepts: A typical quantum theory is constructed from a few building blocks...".
  If a book considers building quantum theories as its starting point, I really
  want to see where it goes.

- [Elementary Applied topology by Robert M Ghirst](https://www.math.upenn.edu/~ghrist/notes.html)
  I wouldn't classify the book as elementary because it skims over too much to be
  useful as a reference, but it's great to gain an intuition for what, say,
  homology or cohomology is. I am currently reading the section on Sheaf theory,
  and I'm getting a lot out of it, since it describes how to write down, say,
  min-cut-max-flow or niquist-shannon in terms of sheaves. I don't grok it yet,
  but even knowing this can be done is very nice. The book is a wonderful
  walkthrough in general.


- [On polysemous mathematical illustration by Robert M Ghirst](https://icerm.brown.edu/video_archive/?play=2034)
  This is a talk on the wonderful illustrations by the above author, about
  the different types of mathematical illustrations one can have, and different
  "levels of abstraction".

- [Mathematical Impressions: The illustrations of AT Femenko](http://chronologia.org/en/math_impressions/poster016.html)
  These are _beautiful_ illustrated pictures of various concepts in math, which
  tend to _evoke_ the feeling of the object, without being too direct about it.
  For example, consider "gradient descent" below. I highly recommend going
  through the full gallery.


- [Gradient Descent](http://chronologia.org/art/math/123a176.jpg)
  <img width=200 height=200 src="http://chronologia.org/art/math/123a176.jpg">

- [Topological Zoo](http://chronologia.org/art/math/077a011.jpg)
  <img width=200 height=200 src="http://chronologia.org/art/math/077a011.jpg">

- [Persistent Homology in Multivariate Data Visualization](https://bastian.rieck.me/research/Dissertation_Rieck_2017.pdf)
  This is the PhD dissertation of [Bastian Rieck](https://bastian.rieck.me/),
  who's now a postdoc at ETH. I deeply enjoyed reading it, since it pays
  a lot of attention to the _design_ of analyses, and how to interpret
  topological data. I really enjoyed getting a good sense of how one can 
  use persistent homology to understand data, and the trade-offs between
  [Vietoris-Rips complex](https://en.wikipedia.org/wiki/Vietoris%E2%80%93Rips_complex)
  and the [Cech complex](https://en.wikipedia.org/wiki/%C4%8Cech_complex).

- [An introduction to Geometric algebra](https://arxiv.org/pdf/1205.5935.pdf)
  I fell in love with geometric algebra, since it provides a really clean way
  to talk about _all possible subspaces_ of a given vector space. This provides
  super slick solutions to many geometry and linear algebra problems. The
  way I tend to look at it is that when one does linear algebra, there's a strict
  separation between "vectors" (which are elements of the vector space), and,
  say, "hyperplanes" (which are _subspaces_ of the vector space), as well as
  objects such as "rotations" (which are _operators_ on the vector space). 
  Geometric algebra provides a rich enough _instruction set_ to throw all
  these three distinct things into a blender. This gives a really concise
  language to describe all phenomena that occurs in the vector space world --- 
  which, let's be honest, is _most_ tractable phenomena! I had a blast
  reading about GA and the kinds of operators it provides.

- [Circuits via Topoi](https://arxiv.org/pdf/1807.07159). This paper attempts
  to provide an introduction to topos theory by providing a semantics for
  both combinational and sequential circuits under a unifying framework. I keep
  coming back to this article as I read more topos theory. Unfortunately, I'm
  not "there yet" in my understanding of topoi. I hope to be next year!


- [Fearless Symmetry](https://press.princeton.edu/books/paperback/9780691138718/fearless-symmetry)
  This is definitely my favourite non-fiction book that I've read in 2019, hands
  down. The book gives a great account of the mathematical objects that went
  into Wiles' book of Fermat's last theorem. It starts with things like
  "what is a permutation" and ends at questions like "what's a reciprocity law"
  or "what's the absolute galois group". While at points, I do believe the book
  goes far too rapidly, all in all, it's a solid account of number theory
  that's distilled, but not in any way diluted. I really recommend reading this
  book if you have any interest in number theory (or, like me, a passing
  distaste due to a course on elementary number theory I took, with proofs that
  looked very unmotivated). This book made me decide that I should, indeed, 
  definitely learn algebraic number theory, upto at least
  [Artin Reciprocity](https://en.wikipedia.org/wiki/Artin_reciprocity_law).


- [Rememberance of Earth's past trilogy by Liu Cixin](https://en.wikipedia.org/wiki/Remembrance_of_Earth%27s_Past)
  While I would not classify this as "mind-blowing" (which I do classify Greg 
  Egan books as), they were still a solidly fun read into how humanity would
  evolve and interact with alien races. It also poses some standard solutions
  to the Fermi Paradox, but it's done well. I felt that the fact that it was
  translated was painfully obvious in certain parts of the translation, which
  I found quite unfortunate. However, I think book 3 makes up in grandeur for
  whatever was lost in translation.

- [Walkaway by Cory Doctorow](https://en.wikipedia.org/wiki/Walkaway_(Doctorow_novel))
  The book is set in a dystopian nightmare, where people are attempting to
  "walk away" from society and set up communes, where they espouse having
  a post-scarcity style economy based on gifting. It was a really great
  description of what such a society could look like. I took issue with some
  weird love-triangle-like-shenanigans in the second half of the book, but
  the story arc more than makes up for it. Plus, the people throw a party
  called as a "communist party" in the first page of the book, which grabbed
  my attention immediately!

- [PURRS: Parma University Recurrence Relation Solver](http://www.cs.unipr.it/purrs/)
  I wanted better tactics for solving recurrences in Coq, which led me into
  a rabbit hole of the technology of recurrence relation solving. This was the
  newest _stable_ reference to a complete tool that I was able to find. Their
  references section is invaluable, since it's been vetted by them
  actually implementing this tool!

- [Term rewriting and all that](https://www21.in.tum.de/~nipkow/TRaAT/).
  I read this book purely for its description of Groebner bases and the Bucchberger
  algorithm in a way that _made sense_ for the first time.
  [I've written about this more extensively before](http://bollu.github.io/#what-the-hell-is-a-grobner-basis-ideals-as-rewrite-systems)
  so I'm not going to repeat myself here. In general, I think it's a great book
  that's worth reading, if nothing else, for at least the chapter on Groebner
  bases.

- [Lucid: The dataflow programming language](http://worrydream.com/refs/Wadge%20-%20Lucid,%20the%20Dataflow%20Programming%20Language.pdf)
  This document is the user manual of Lucid. I didn't fully understand the
  book, but what I understood as their main argument is that full access too
  looping is un-necessary to perform most of the tasks that we do. Rather,
  one can provide a "rich enough" set of combinators to manipulate streams
  that allows one to write all programs worthy of our interest.

- [Bundle Adjustment — A Modern Synthesis](https://hal.inria.fr/inria-00548290/document)
  I learnt about Bundle Adjustment from a friend taking a course on robotics.
  The general problem is to reconstruct the 3D coordinates of a point cloud
  given 2D projections of the points and the camera parameters, as the camera
  moves in time. I found the paper interesting since it winds up invoking a
  decent amount of differential geometric and gauge theoretic language to
  describe the problem at hand. I was unable to see why this vocabulary helped
  in this use-case, but perhaps I missed the point of the paper. It was hard to
  tell.

#### Conclusions

I always feel a little wrong posting this at the end of every year, since I
feel that among the things I cover under "read", I've internalized some things
far better than others: For example, I feel I understannd Riemannian geometry
far better than I do General Relativity. I try to put up the caveats at the
beginning of each section, but I'd really like a way to communicate my
confidence without reducing readability.


The final thing that I wish for is some kind of reading group? It's hard
to maintain a group when my interests shift as rapidly as they do, which
was one of the reason I really loved the AIRCS workshop: They were people
who were working on formal methods, compilers, type theory, number theory,
embedded systems, temporal logic... It was very cool to be in a group of
people who had answers and intuitions to questions that had bugged me for
some time now. I wonder if attending courses at a larger research university
feels the same way. My uni is good, but we have quite small population, which
almost by construction means reduced diversity.

I also wish that I could openly add more references to repos I've been working
on for a while now, but I can't due to the nature of academia and publishing.
This one bums me out, since there's a long story of a huge number of commits
and trial-by-fire that I think I'll be too exhausted to write about once the
thing is done. 

Sometimes, I also wish that I could spend the time I spend reading _disparate_
topics on _focused reading on one topic_. Unfortunately, I feel like I'm not
wired this way, and the joy I get from sampling many things at the same time
and making connections is somehow much deeper than the joy I get by deeply
reading one topic (in exclusion of all else). I don't know what this says
about my chances as a grad student in the future `:)`.


# [A motivation for p-adic analysis](#a-motivation-for-p-adic-analysis)

I've seen the definitions of p-adic numbers scattered around on the internet,
but this analogy as motivated by the book 
[p-adic numbers by Fernando Gouvea](https://www.springer.com/gp/book/9783540629115) 
really made me understand why one would study the p-adics, and why the
definitions are natural. So I'm going to recapitulate the material, with the
aim of having somoene who reads this post be left with a sense of why it's
profitable to study the p-adics, and what sorts of analogies are fruitful when
thinking about them.

We wish to draw an analogy between the ring $\mathbb C[X]$, where $(X - \alpha)$
are the prime ideals, and $\mathbb Z$ where $(p)$ are the prime ideals. We wish
to take all operations one can perform with polynomials, such as generating
functions ($1/(X - \alpha) = 1 + X + X^2 + \dots$ ), 
taylor expansions (expanding aronund $(X - \alpha)$),
and see what their analogous objects will look like in $\mathbb Z$
relative to a prime $p$.

#### Perspective: Taylor series as writing in base $p$:

Now, for example, given a prime $p$, we can write any positive integer $m$
in base $p$, as $(m = \sum_{i=0}^n a_i p^i)$ where $(0 \leq a_i \leq p - 1)$.

For example, consider $m = 72, p = 3$. The expansion of 72 is 
$72 = 0\times 1 + 0 \times 3 + 2 \times 3^2 + 2 \times 3^3$.
This shows us that 72 is divisible by $3^2$.

This perspective to take is that this us the information local to prime $p$,
about what order the number $m$ is divisible by $p$,
just as the taylor expansion tells us around $(X - \alpha)$ of a polynomial $P(X)$ 
tells us to what order $P(X)$ vanishes at a point $\alpha$.

#### Perspective: rational numbers and rational functions as infinite series:

Now, we investigate the behaviour of expressions such as 
- $P(X) = 1/(1+X) = 1 - X + X^2 -X^3 + \dots$.

We know that the above formula is correct formally from the theory of
generating functions.  Hence, we take inspiration to define values for
_rational numbers_.

Let's take $p \equiv 3$, and we know that $4 = 1 + 3 = 1 + p$.

We now calculate $1/4$ as:

$$
1/4 = 1/(1+p) = 1 - p + p^2 - p^3 + p^4 - p^5 + p^6 + \cdots
$$

However, we don't really know how to interpret $(-1 \cdot p)$, since we assumed
the coefficients are always non-negative. What we can do is to rewrite $p^2 = 3p$,
and then use this to make the coefficient positive. Performing this transformation
for every negative coefficient, we arrive at:


$$
\begin{aligned}
1/4 &= 1/(1+p) = 1 - p + p^2 - p^3 + p^4 + \cdots \\
&= 1 + (- p + 3p) + (- p^3 + 3p^3)  +  \cdots \\
&= 1 + 2p + 2p^3 + \cdots
\end{aligned}
$$

We can verify that this is indeed correct, by multiplying with $4 = (1 + p)$
and checking that the result is $1$:

$$
\begin{aligned}
&(1 + p)(1 + 2p + 2p^3 + \cdots) \\
&= (1 + p) + (2p + 2p^2) + (2p^3 + 2p^4) + \cdots \\
&= 1 + 3p + 2p^2 + 2p^3 + 2p^4 + \cdots \\
&\text{(Rewrite $3p = p \cdot p = p^2$)} \\
&= 1 + (p^2 + 2p^2) + 2p^3 + 2p^4 + \cdots \\
&= 1 + 3p^2 + 2p^3 + 2p^4 + \cdots \\
&\text{(Rewrite $3p^2 = p^3$ and collect $p^3$)} \\
&= 1 + 3p^3 + 2p^4 + \cdots \\
&= 1 + 3p^4 + \cdots \\
&= 1 + \cdots = 1
\end{aligned}
$$

What winds up happening is that all the numbers after $1$ end up being cleared
due to the carrying of $(3p^i \mapsto p^{i+1})$.

This little calculation indicates that we can also define take the $p$-adic
expansion of _rational numbers_.

#### Perspective: -1 as a p-adic number

We next want to find a p-adic expansion of -1, since we can then expand
out theory to work out "in general". The core idea is to "borrow" $p$, so
that we can write -1 as $(p - 1) - p$, and then we fix $-p$, just like we fixed
$-1$. This eventually leads us to an infinite series expansion for $-1$. Written
down formally, the calculation proceeds as:

$$
\begin{aligned}
-1 &= -1 + p - p  \qquad \text{(borrow $p$, and subtract to keep equality)} \\
&= (p - 1) - p \qquad \text{(Now we have a problem of $-p$)} \\
&= (p - 1) - p + p^2 - p^2  \\
&= (p - 1) + p(p - 1) - p^2 \\
&= (p - 1) + p(p - 1) - p^2 + p^3 - p^3 \\
&= (p - 1) + p(p - 1) + p^2(p - 1) - p^3 \\
&\text{(Generalizing the above pattern)} \\
-1 &= (p - 1) + p(p - 1) + p^2(p - 1) + p^3(p - 1) + p^4(p - 1) + \cdots \\
\end{aligned}
$$

This now gives us access to negative numbers, since we can formally multiply
the series of two numbers, to write $-a = -1 \cdot a$. 


Notice that this definition of $-1$ also curiously matches the 2s complement 
definition, where we have $-1 = 11\dots 1$. In this case, the expansion is
_infinite_, while in the 2s complement case, it is finite. I would be very
interested to explore this connection more fully.

#### What have we achieved so far?

We've now managed to completely reinterpret all the numbers we care about in 
the rationals as power series in base $p$. This is pretty neat. We're next
going to try to _complete_ this, just as we complete the rationals to get
the reals. We're going to show that we get a _different_ number system on
completion, called $\mathbb Q_p$. 

To perform this, we first look at how the $p$-adic numbers help us solve
congruences mod p, and how this gives rise to completions to equations such
as $x^2 - 2 = 0$, which in the reals give us $x = \sqrt 2$, and in $\mathbb Q_p$
give us a different answer!

#### Solving $X^2 \equiv 25 \mod 3^n$

Let's start by solving an equation we already know how to solve:
$X^2 \equiv 25 \mod 3^n$. 

We already know the solutions to $X^2 \equiv 25 \mod 3^n$ in $\mathbb Z$ are 
$X \equiv \pm 5 \mod 3^n$.

Explicitly, the solutions are:
- $X \equiv 3 \mod 3$
- $X \equiv 5 \mod 9$
- $X \equiv 5 \mod 27$
- At this point, the answer remains constant.

This was somewhat predictable. We move to a slightly more interesting case.

#### Solving $X = -5 \mod 3^n$

The solution sets are:
- $X \equiv -5 \equiv 1 \mod 3$
- $X \equiv -5 \equiv 4 = 1 + 3 \mod 9$
- $X \equiv -5 \equiv 22 = 1 + 3 + 2 \cdot 9 \mod 27$
- $X \equiv -5 \equiv 76 = 1 + 3 + 2 \cdot 9 + 2 \cdot 27 \mod 81$



This gives us the infinite 3-adic expansion:

- $X = -5 = 1 + 1\cdot 3 + 2\cdot 3^2 + 2\cdot 3^3 + \dots$

Note that we can't really _predict_ the digits in the 3-adic sequence of -5,
but we can keep expanding and finding more digits. 

Also see that the solutions are "coherent". In that, if we look at the
solution mod 9, which is $4$, and then consider it mod 3, we get $1$. So,
we can say that given a sequence of integers $0 \leq \alpha_n \leq p^n - 1$,
**$\alpha_n$ is p-adically coherent sequence** iff:

- $ \alpha_{n+1} = \alpha_n \mod p^n$.


#### Viewpoint: Solution sets of $X^2 = 25 \mod 3^n$

Since our solution sets are coherent, we can view the solutions as a tree,
with the expansions of $X = 5, X = -5 \mod 3$ and then continuing onwards
from there. That is, the sequences are

- $2 \rightarrow 5 \rightarrow 5 \rightarrow 5 \rightarrow \dots$
- $1 \rightarrow 4 \rightarrow 22 \rightarrow 76 \rightarrow \dots$

#### Solving $X^2 \equiv 2 \mod 7^n$

We now construct a solution to the equation $X^2 = 1$ in the 7-adic system,
thereby showing that $\mathbb Q_p$ is indeed strictly _larger_ than $\mathbb Q$,
since this equation does not have rational roots.

For $n=1$, we have the solutions as $X \equiv 3 \mod 7$, $X \equiv 4 \equiv -3 \mod 7$.

To find solutions for $n = 2$, we recall that we need our solutions to be consistent
with those for $n = 1$. So, we solve for:
- $(3 + 7k)^2 = 2 \mod 49$, $(4 + 7k)^2 = 2 \mod 49$.

Solving the first of these:

$$
\begin{aligned}
(3 + 7k)^2 &\equiv 2 \mod 49 \\
9 + 42 k + 49k^2 &\equiv 2 \mod 49 \\
9 + 42 k + 0k^2 &\equiv 2 \mod 49 \\
7 + 42 k &\equiv 0 \mod 49 \\
1 + 6 k &\equiv 0 \mod 49 \\
k &\equiv 1 \mod 7
\end{aligned}
$$

This gives the solution $X \equiv 10 \mod 49$. The other branch ($X = 4 + 7k$)
gives us $X \equiv 39 \equiv -10 \mod 49$.

We can continue this process indefinitely (_exercise_), giving us the sequences:

- $3 \rightarrow 10 \rightarrow 108 \rightarrow 2166 \rightarrow \dots$
- $4 \rightarrow 39 \rightarrow 235 \rightarrow 235 \rightarrow \dots$

We can show that the sequences of solutions we get satisfy the equation 
$X^2 = 2 \mod 7$. This is so by construction. Hence, $\mathbb Q_7$ contains
a solution that $\mathbb Q$ does not, and is therefore strictly bigger, since
we can already represent every rational in $\mathbb Q$ in $\mathbb Q_7$.


#### Use case: Solving $X = 1 + 3X$ as a recurrence

Let's use the tools we have built so far to solve the equation $X = 1 + 3X$.
Instead of solving it using algebra, we look at it as a recurrence $X_{n+1} = 1 + 3X_n$.
This gives us the terms:
- $X_0 = 1$
- $X_1 = 1 + 3$
- $X_2 = 1 + 3 + 3^2$
- $X_n = 1 + 3 + \dots + 3^n$

In $\mathbb R$, this is a divergent sequence. However, we know that the
solution so $1 + X + X^2 + \dots = 1/(1-X)$, at least as a generating function.
Plugging this in, we get that the answer should be:

- $1/(1 - 3) = -1/2$

which is indeed the correct answer.

Now this required some really shady stuff in $\mathbb R$. However, with a change
of viewpoint, we can explain what's going on. We can look at the above series
as being a series in $\mathbb Q_3$.  Now, this series does _really_ converge,
and by the same argument as above, it converges to $-1/2$.

The nice thing about this is that a dubious computation becomes a legal one
by changing one's perspective on where the above series lives.

#### Viewpoint: 'Evaluation' for p-adics

The last thing that we need to import from the theory of polynomials
is the ability to _evaluate_ them: Given a rational function $F(X) = P(X)/Q(X)$, 
where $P(X), Q(X)$ are polynomials, we can
evaluate it at some arbitrary point $x_0$, as long as $x_0$ is not a zero 
of the polynomial $Q(X)$.

We would like a similar function, such that for a fixed prime $p$, we obtain
a ring homomorphism from $\mathbb Q \rightarrow \mathbb F_p^x$, which we will
denote as $p(x_0)$, where we are imagining that we are "evaluating" the prime
$p$ against the rational $x_0$.

We define the value of $x_0 = a/b$ at the prime $p$ to be equal to
$ab^{-1} \mod p$, where $b b^{-1} \equiv 1 \mod p$. That is, we compute the
usual $ab^{-1}$ to evaluate $a/b$, except we do this $(\mod p)$, to stay with
the analogy.

Note that if $b \equiv 0 \mod p$, then we cannot evaluate
the rational $a/b$, and we say that $a/b$ has a pole at $p$. The order
of the pole is the number of times $p$ occurs in the prime factorization of $b$.

I'm not sure how profitable this viewpoint is, so I 
[asked on math.se](https://math.stackexchange.com/questions/3483369/profit-of-definition-evaluation-of-a-rational-at-a-p-adic),
and I'll update this post when I recieve a good answer.


#### Perspective: Forcing the formal sum to converge by imposing a new norm:

So far, we have dealt with infinite series in base $p$, which have terms
$p^i, i \geq 0$.
Clearly, these sums are divergent as per the usual topology on $\mathbb Q$.
However, we would enjoy assigning analytic meaning to these series. Hence, we
wish to consider a new notion of the absolute value of a number, which makes it
such that $p^i$ with large $i$ are considered small. 


We define the absolute value for a field $K$ as a function
$|\cdot |: K \rightarrow \mathbb R$. It obeys the axioms:


1. $\lvert x \rvert = 0 \iff x = 0$
2. $\lvert xy \rvert =  \lvert x \rvert  \lvert y \rvert$ for all $x, y \in K$
3. $\lvert x + y \rvert \leq \lvert x \rvert + \lvert y \rvert$, for all $x, y \in K$.


We want the triangle inequality so it's metric-like, and the norm to be
multiplicative so it measures the size of elements. 

The usual absolute value $\lvert x \rvert \equiv \\{ x : x \geq 0; -x : ~ \text{otherwise} \\}$ satisfies
these axioms.

Now, we create a new absolute value that measures primeness. We first introduce
a gadget known as a valuation, which measures the $p$-ness of a number. We use
this to create a norm that makes number smaller as their $p$-ness increases.
This will allow infinite series in $p^i$ to converge.

#### p-adic valuation: Definition

First, we introduce
a valuation $v_p: \mathbb Z - \\{0\\} \rightarrow \mathbb R$, where $v_p(n)$ is
the power of the prime $p^i$ in the prime factorization of $n$. More formally,
$v_p(n)$ is the unique number such that:

- $n = p^{v_p(n)} m$, where $p \nmid m$.
- We extend the valuation to the rationals by defining $v_p(a/b) = v_p(a) - v_p(b)$.
- We set $v_p(0) = +\infty$. The intuition is that $0$ can be divided by $p$
  an infinite number of times.

The valuation gets larger as we have larger powers of $p$ in the prime
factorization of a number. However, we want the norm to get _smaller_. Also,
we need the norm to be multiplicative, while $v_p(nm) = v_p(n) + v_p(m)$, which
is additive. 


To fix both of these, we create a norm by exponentiating $v_p$.
This converts the additive property into a multiplicative property. We
exponentiate with a negative sign so that higher values of $v_p$ lead to 
smaller values of the norm.

#### p-adic abosolute value: Definition

Now, we define the **p-adic absolute value** of a number $n$ as
$|n|_p \equiv p^{-v_p(n)}$.

- the norm of $0$ is $p^{-v_p(0)} = p^{-\infty} = 0$.
- If $p^{-v_p(n)} = 0$, then $-v_p(n) = \log_p 0 = -\infty$, and hence $n = 0$.
- The norm is multiplicative since $v_p$ is additive.
- Since $v_p(x + y) \geq \min (v_p(x), v_p(y)), |x + y|_p \leq max(|x|_p, |y|_p) \leq |x|_p + |y|_p$.
  Hence, the triangle inequality is also satisfied.

So $|n|_p$ is indeed a norm, which measures $p$-ness, and is smaller as $i$
gets larger in the power $p^i$ of the factorization of $n$, causing our
infinite series to converge.

There is a question of why we chose a base $p$ for $|n|_p = p^{v_p(n)}$. It would
appear that any choice of $|n|_p = c^{v_p(n)}, c > 1$ would be legal.
[I asked this on `math.se`](https://math.stackexchange.com/questions/3482489/why-does-the-p-adic-norm-use-base-p),
and the answer is that this choosing a base $p$ gives us the nice formula

$$
\forall x \in \mathbb Z, \prod_{\{p : p~\text{is prime}\} \cup \{ \infty \}} |x|_p = 1
$$

That is, the product of all $p$ norms and the usual norm 
(denoted by $\lvert x \rvert_\infty $ )
give us the number 1. The reason is that the $ \lvert x\rvert_p $ give us 
multiples $p^{-v_p(x)}$,
while the usual norm $\lvert x \rvert_\infty$ contains a multiple 
$p^{v_p(x)}$, thereby cancelling each other out.


#### Conclusion

What we've done in this whirlwind tour is to try and draw analogies between
the ring of polynomials $\mathbb C[X]$ and the ring $\mathbb Z$, by trying
to draw analogies between their prime ideals: $(X - \alpha)$ and $(p)$. So,
we imported the notions of generating functions, polynomial evaluation, and
completions (of $\mathbb Q$) to gain a picture of what $\mathbb Q_p$ is like.

We also tried out the theory we've built against some toy problems, that shows
us that this point of view maybe profitable. If you found this interesting,
I highly recommend the book 
[p-adic numbers by Fernando Gouvea](https://www.springer.com/gp/book/9783540629115).



# [Line of investigation to build physical intuition for semidirect products](#line-of-investigation-to-build-physical-intuition-for-semidirect-products)

To quote wikipedia:
> In crystallography, the space group of a crystal splits as the semidirect
> product of the point group and the translation group if and only if the space
> group is symmorphic

The if and only if is interesting: The geometry ofthe crystal lattice truly
appears to capture the structure of the semidirect product. It's a discrete
object as well, which makes it way easier to visualize. I'm going to hunt down
the definitions involved so I can finally feel like I truly understand semidirect
products from the "action" perspective.

# [Topology is really about computation --- part 2](#topology-is-really-about-computation--part-2)

Here, we're going to describe whatever I've picked up of sheaves in the past
couple of weeks. I'm trying to understand the relationship between sheaves,
topoi, geometry, and logic. I currently see how topoi allows us to model logic,
and how sheaves allow us to model geometry, but I see nothing about the
relationship! I'm hoping that writing this down will allow me to gain some
perspective on this.

## What is a sheaf?

Let's consider two sets $P, A$, $P \subseteq A$. Now, given a function
$f: A \rightarrow X$, we can restrict this function to $ A_P: P \rightarrow X $.
So, we get to _invert the direction_:

$$
(P \subseteq A) \iff (f: A \rightarrow X) \rightarrow (f_P: P \rightarrow X)
$$.

We should now try to discover some sort of structure to this "reversal"
business. Perhaps we will discover a contravariant functor! (Spoiler: we will).


# [Topology is really about computation --- part 1](#topology-is-really-about-computation--part-1)

Most people believe that topology is about some notion of "nearness" or
"closeness", which has been abstracted out from our usual notion of
continuity that we have from a metric space. Here, I make the claim that
topology is really about _computation_, and more specifically, _decidability_.
These are not new ideas. I learnt of this from a monograph [The topology of
computation](https://pdf.sciencedirectassets.com/272990/1-s2.0-S1571066104X00177/1-s2.0-S1571066104051357/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIGQAb828p1io4csznEej60j0PwJteuXf7OoHLSCDhkUTAiEA9ITs1JrUEOE%2Ft%2Fl5TI9ZkNLUfBIx42IZ%2FoAqQpdX4twq2AII6%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARACGgwwNTkwMDM1NDY4NjUiDBQOxJ3s3HCbVxSheCqsAt65yorZMMtIhLF7ML5sJQ9S5wZxBayKDrRkUKOjSzXxtQWebXs70FXhhpToXKvJoDrLgsqDzdF%2FAshZY%2FkDUep6KILxKnYxCBrBINhjFqxDlRZH0s1Y991RgCyNNnwmFI%2BrH70lSrV0OxQ9Z5WdXXPDkTLXv8512Xz%2BJn5DqEqdqD49FLbOuHl6PRM0TnYyNJkLBXNVwt75kkGkaTfdgmgiqh7YpcXcHlbqI2oqNcaxFDewXwKDCC7qWD6ECclLgszoeOXOtRI91nvNac8%2BLV4bXkKLXpd99H94N2vXPUPz99p6oqfdY9ixtcfI9POFX8agUilYjXKVhAWk4FSzzzMqbtZLBfkCZT4ffDTxRgL52yD%2FmL5E0Pe4mczVlUoB5DKoB8Lkitrt0BumQzDr4ffvBTrQAjVRuzG5V0CC%2Fd1t%2BUMPkrywaYytbrXCZ%2BkDo0xDBqsljY8DaGIiFINr8BEEpT7UX42GRhcDzpnOnztdAOTea3qZ3SmXJwgEoh0aiz%2B87MmsC57s0Q%2F%2B%2FDDvHBY3zLCrz7rdewXOgk6VxI9d5mhG3Du1dwPRbgOe798S2waDCD8LQA3rw7w5wNGa9Uv3xtNVH%2BHw%2FXcQ6OiubO4GL9mK8U5g7TVPh1hLB26XBQooKJ564VGf4J9VqWxjlx3NicVhqnFlGevNJNKyVLiyRsRCyQGMV59%2BXqUwdEMQZYWLbfUwELNz1NKfWumvu9BXC5jjsJgNx%2FRERSb7hqT1svMJU91o%2FHtatGAnPvVjYaNthha9O9jm%2BG9nw1vMsdyJ0asI5w5SrlsEyb5C7Vk7aLBcHAEi3XPRhivY1Q4hZAN0xY9VfEZrF%2FoM9HCGxr5cYs%2BP9w%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20191221T113658Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY6QRXTPOC%2F20191221%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=8a26656e8f8c8772afdc2ae6caa9b583fd59a8ee6303d9770d25b4a3d8a6291f&hash=42518d3e5cc1e77ed961c359d0ea8f59bd582d1e5f13d69c3eeb2563a6c82abd&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S1571066104051357&tid=spdf-584e8188-4806-44bb-a118-9b63a53caaff&sid=f53691052392834d3e18a62484e2909639a9gxrqb&type=client), but this does not seem very well known,
so I decided to write about it.

The idea is this: We have turing machines which can compute things. We then
also have a set $S$. Now, a topology $\tau \subset 2^S$ precisely encodes
which of the subsets of $S$ can be separated from the rest of the space by a turing machine.
Thus, a discrete space is a very nice space, where every point can be separated
from every other point. An indescrete space is one where no point can be separated.

Something like the reals is somewhere in between, where we can separate 
stuff inside an open interval from stuff clearly outside, but there's some
funny behaviour that goes on at the boundary due to things like `(0.999... = 1)`,
which we'll see in detail in a moment.

#### Semidecidability

A subset $Q\subseteq S$ is _semidecidable_, if there exists a turing machine
$\hat Q: Q \rightarrow \{ \bot, \top \}$, such that:

$$
\begin{aligned}
\hat Q(q) = \top \iff q \in Q \\
\hat Q(q) = \bot \iff q \notin Q \\
\end{aligned}
$$

Where $\top$ signifies stopping at a state and returning `TRUE`, and
$\bot$ signifies _never halting at all_!. So, the subset $Q$ is
_semidedicable_, in that, we will halt and say `TRUE` if the element
belongs in the set. But if an element does not belong in the set, we are
supposed to never terminate.

#### Deep dive: semidecidability of the interval $(1, 2)$

Let's start with an example. We consider the interval $I = (1, 2)$, as a
subset of $\mathbb{R}$.Let the turing machine recieve the real number
as a function $f: \mathbb N \rightarrow \{0, 1, \dots 9\}$, such that
given a real number ${(a_0 \cdot a_1 \cdot a_2 \dots)}$, this is encoded as a
function ${f_a(i) = a_i}$. 

We now build a turing machine $\hat I$ which when given the input the function $f_a$,
semi-decides whether ${a \in I}$. 

Let's consider the numbers in $I$:

$$
0 \rightarrow \texttt{NO} \\
0.\overline{9} \rightarrow \texttt{NO} \\
1 \rightarrow \texttt{NO} \\
1.a_1 a_2 \dots \rightarrow \texttt{YES} \\
1.\overline{9} \rightarrow \texttt{NO} \\
2.0 \rightarrow \texttt{NO} \\
2.a_1 a_2 \rightarrow \texttt{NO}
$$

So, we can write a turing machine (ie, some code) that tries to decide whether
a real number $a$'s encoding $f_a$ belongs to the interval $I = (1, 2)$
as follows:

```py
def decide_number_in_open_1_2(f):
  # if the number is (1.abcd)
  if f(0) == 1:
    # (1.99...99x) | look for the x.
    # If the number is 1.999..., do not terminate.
    # if the number is any other number of the form 1.99..x, terminate
    i = 1
    while f(i) != 9: i += 1
    return
  # if the number is not 1.abcd, do not terminate
  while True: pass
```

Hence, we say that the interval $I = (1, 2)$ is _semi-decidable_, since we 
have a function
$\hat I \equiv \texttt{decide-number-in-open-1-2}$
such that
$\hat I (f_a) \text{ terminates } \iff a \in I$. 
We don't make _any claim_ about
what happens if $a \notin I$. This is the essence of semidecidability: We
can precisely state when elements in the set belong to the set, but not
when they don't.

### Semi decidability in general

To put this on more solid ground, we define a topology on a set $S$ by considering
programs which recieve as input elements of $S$, suitably encoded. For example,
the way in which we encoded real numbers as functions from the index to the
digit. Similarly, we encode other mathematical objects in some suitable way.

Now, we define:

- For every program $P$ which takes as inputs elements in $S$, the set 
  ${halts(P) \equiv \\{ s \in S \vert P(s) \text{halts} \\}}$ is called as a
  _semidecidable set_.

- Alternatively, we can say for a subset ${T \subset S}$, if there
  exists a program ${\hat T}$, such that
  ${s \in T \iff \hat T(s) \text{ halts}}$, then $T$ is semi-dedecidable.

These are just two viewpoints on the same object. In one, we define the
set based on the program. In the other, we define the program based on the
set.

### Semi decidability of the empty set and the universe set.

The empty set is semi-decidable, due to the existence of the program:
```py
def semidecide_empty(x):
  while True: continue
```


The universe set is semi-decidable, due to the existence of the program:
```py
def semidecide_univ(x): return
```

### Semi decidability of the union of sets

infinite unions of sets are semi decidable, since we can "diagonalize" on
the steps of all programs. That way, if any program halts, we will reach
the state where it halts in our diagonalized enumeration.



Let `A00, A01... A0n` be the initial states of the machines. We are trying to
semidecide whether any of them halt. We lay out the steps of the machines
in an imaginary grid:

```
A00 A01 A02 ... A0n
A10 A11 A12 ... A1n
A20 A21 A22 ... A2n
Am0 Am1 Am2 ... Amn
```

For example, machine `A0` has states:

```
A00 -> A10 -> .. -> Am0
```
We can walk through the combined state-space of the machines as:

```
A00
A01 A10
A02 A11 A20
A03 A12 A21 A30
...
```

Where on the `k`'th line, we collect all states $A_{ij}$ such that $(i + j = k)$.

Now, if any of the machines have a state that is `HALT`, we will reach the
state as we enumerate the diagonals, and the machine that explores the
combined state space can also return `HALT`.

### Semi decidability of the intersection of sets

infinite intersections of sets are _not_ semi decidable, since by running
these programs in parallel, we cannot know if an infinite number of programs
halt in finite time. We _can_ tell if _one_ of them halts, but of if _all_
of them halt.

For example, consider the sequence of machines produced by `machine_creator`:

```py
# creates a machine that stops after n steps
def machine_creator(n):
    # f terminates after n steps
    def f(x):
      for _ in range(n):
        continue
    return

    return f
```

We wish to check if the intersection of all `machine_creator(n)` halt, for all
$n \geq 0, n \in \mathbb N$. Clearly, the answer is an infinite number of steps,
even though every single machine created by `machine_creator` halts in a
finite number of steps.

# [PSLQ algorithm: finding integer relations between reals](#pslq-algorithm-finding-integer-relations-between-reals)

An algorithm to find _integer_ relations between _real_ numbers. It was
apparently named "algorithms of the century" by Computing in science and
engineering.

- [Wolfram link](http://mathworld.wolfram.com/PSLQAlgorithm.html)

# [Geometric characterization of normal subgroups](#geometric-characterization-of-normal-subgroups)
> $Stab(Orb(x)) = Stab(x) \iff Stab(x) \text{ is normal}$

> $\forall x' \in Orb(x), Stab(x') = Stab(x) \iff Stab(x) \text{ is normal}$


#### Forward: if the stabilizer is normal, then all elements in the orbit have the same stabilizer

Let a group $G$ act on a set $X$ with action $(~\dot~) : G \times X \rightarrow X$.  
Let $H \subseteq G$ be the stabilizer of a point $x \in X$. Now, let 
$K = kHk^{-1}$, a conjugacy class of $H$. Clearly, the element $(k \cdot x)$
in the orbit of $x$ is stabilized by $K$.

If the group $H$ is normal, then $K = H$. So every element in the orbit of $x$
is stabilized by $H$. 

#### Interaction of stablizer and the orbit:

> $Stab(g \cdot x) = g Stab(x) g^{-1}$

> $g^{-1} Stab(g \cdot x) g = Stab(x)$

-  Proof of $s \in Stab(x) \implies gsg^{-1} \in Stab(g \cdot x)$:
   The action of $gsg^{-1}$ on $g \cdot x$ is:
   $(g \cdot x \rightarrow_{g^-1} x \rightarrow_s x \rightarrow_g g \cdot x)$.

- Proof of $s' \in Stab(g \cdot x) \implies g^{-1}s'g \in Stab(x)$:
  The action of $g^{-1}s'g$ on $x$ is:
  $(x \rightarrow_{g} g \cdot x \rightarrow_{s'} g \cdot x \rightarrow_{g^{-1}} x)$.

Hence, both containments are proved.

#### Backward: if all elements in the orbit have the same orbit, then the stabilizer is normal.

From the above equation $Stab(g \cdot x) = g Stab(x) g^{-1}$. If the
entire orbit has the same stabilizer, $Stab (g \cdot x) = Stab(x)$. Hence,
we get $Stab(x) = g Stab(x) g^{-1}$, proving that it's normal.

# [Handy characterization of adding an element into an ideal, proof that maximal ideal is prime](#handy-characterization-of-adding-an-element-into-an-ideal-proof-that-maximal-ideal-is-prime)

##### The characterization

Let $I$ be an ideal. The ideal generated by adding $(a \in R)$ to $I$ is 
defined as $A \equiv (I \cup \{ a\})$. We prove that $A = I + aR$.


$$
(I \cup \{a \})  \\
= \quad \{ \alpha i + \beta a | i \in I, \alpha, \beta \in R \} \\
= \quad \{ i' + \beta a | i' \in I, \alpha, \beta \in R \} \qquad \text{($I$ is closed under multiplication by $R$)} 
= I + aR
$$

##### Quotient based proof that maximal ideal is prime 

An ideal $P$ is prime iff the quotient ring $R/P$ is an integral domain. An
ideal $M$ is maximal $R/M$ is a field. Every field is an integral domain,
hence:

$M \text{ is maximal } \implies R/M \text{ is a field } \implies R/M \text {is an integral domain} \implies M \text{ is prime}$.

I was dissatisfied with this proof, since it is not ideal theoretic: It argues
about the behaviour of the quotients. I then found this proof that argues
purly using ideals:

#### Ideal theoretic proof that maximal ideal is prime

##### Sketch
Let $I$ be a maximal ideal. Let $a, b \in R$ such that $ab \in I$. We need
to prove that $a \in I \lor b \in I$. If $a \in I$, the problem is done.
So, let $a \notin I$. Build ideal $A = (I \cup {a})$. $I \subsetneq A$. Since
$I$ is maximal, $A = R$. Hence, there are solutions for
$1_R \in A \implies 1_r \in I + aR \implies \exists i \in I, r \in R, 1_R = i  + ar$.
Now, $b = b \cdot 1_R = b(i + ar) = bi + (ba)r \in I + IR = I$. ($ba \in I$ by assumption).
Hence, $b \in I$.


##### Details

let $i$ be a maximal ideal. let $a, b \in r$ such that $ab \in i$. we need
to prove that $a \in i \lor b \in i$.

if $a \in i$, then the problem is done. so, let $a \notin i$. consider
the ideal $A$ generated by adding $a$ into $I$. $A \equiv (I \cup \{a\})$.

We have shown that $A = I + aR$. Hence, $I + a0 = I \subset A$. 
Also, $0 + ac \dot 1 = a \in A$, $a \neq I$ \implies $A \neq I$. Therefore,
$I \subsetneq A$. Since $I$ is maximal, this means that $A = R$

Therefore, $I + aR = R$. Hence, there exists some $i \in I, r \in R$ such
that $i + ar = 1_R$.

Now, $b = b \cdot 1_R = b \cdot (i + ar) = bi + (ba) r \in I + IR = I$ Hence,
$b \in I$.



# [Radical ideals, nilpotents, and reduced rings](#radical-ideals-nilpotents-and-reduced-rings)

##### Radical Ideals
A radical ideal of a ring $R$ is an ideal such that
$\forall r \in R, r^n \in I \implies r \in I$.
That is, if any power of $r$ is in $I$, then the element
$r$ also gets "sucked into" $I$.

##### Nilpotent elements
A nilpotent element of a ring $R$ is any element $r$ such that there exists
some power $n$ such that $r^n = 0$.

Note that every ideal of the ring contains $0$. Hence, if an ideal $I$
of a ring is known to be a radical ideal, then for any nilpotent $r$,
since $\exists n, r^n = 0 \in I$, since $I$ is radical, $r \in I$.

That is, _a radical ideal with always contain all nilpotents!_ It will
contain other elements as well, but it will contain nilpotents for sure.

##### Radicalization of an ideal
Given a ideal $I$, it's radical idea $\sqrt I \equiv \{ r \in R, r^n \in I \}$.
That is, we add all the elements $I$ needs to have for it to become a radical.

Notice that the radicalization of the zero ideal $I$ will precisely contain
all nilpotents. that is, $\sqrt{(0)} \equiv \{ r \in R, r^n = 0\}$.

##### Reduced rings
A ring $R$ is a reduced ring if the only nilpotent in the ring is $0$.

##### creating reduced rings (removing nilpotents) by quotienting radical ideals
Tto remove nilpotents of the ring $R$, we can create $R' \equiv R / \sqrt{(0}$. Since
$\sqrt{(0)}$ is the ideal which contains all nilpotents, the quotient ring $R'$ will contain
no nilpotents other than $0$.

Similarly, quotienting by any larger radical ideal $I$ will remove all nilpotents
(and then some), leaving a reduced ring.

> A ring modulo a radical ideal is reduced

##### Integral domains
a Ring $R$ is an integral domain if $ab = 0 \implies a = 0 \lor b = 0$. That is,
the ring $R$ has no zero divisors.

##### Prime ideals

An ideal $I$ of a ring $R$ is a prime ideal if
$\forall xy \in R, xy \in I \implies x \in I \lor y \in I$. This generalizes
the notion of a prime number diving a composite: $p | xy \implies p | x \lor p | y$.

##### creating integral domains by quotenting prime ideals

Recall that every ideal contains a $0$. Now, if an ideal $I$ is prime, and if
$ab = 0 \in I$, then either $a \in I$ or $b \in I$ (by the definition of prime).

We create $R' = R / I$. We denote $\overline{r} \in R'$ as the image of $r \in R$
in the quotient ring $R'$.

The intuition is that quotienting by a  $I$, since if $ab = 0 \implies a \in I \lor b \in I$,
we are "forcing" that in the quotient ring $R'$, if $\overline{a} \overline{b} = 0$, then either 
$\overline{a} = 0$ or $\overline{b} = 0$, since $(a \in I \implies \overline a = 0)$,
and $b \in I \implies \overline b = 0)$. 

> A ring modulo a prime ideal is an integral domain.


I learnt of this explanation from this
[excellent blog post by Stefano Ottolenghi](http://quickmathintuitions.org/relationship-between-reduced-rings-radical-ideals-and-nilpotent-elements/).

# [My disenchantment with abstract interpretation](#my-disenchantment-with-abstract-interpretation)

When I first ran across the theory of abstract interpretation, it seemed magical:
Define two functions, check that they're monotone maps, and boom, we have
on our hands an analysis.

However, the problem appears to be that in reality, it's not as simple. Here is
the list of issues I've run across when trying to use abstract interpretation
for a "real world" use-case:


First of all, all interesting lattices are infinte height, requiring some
choice of widening.  Defining a good widening is a black art.  Secondly, while
there is a lot of theory on combining abstract domains (reduced products and
the like), it seems hard to deploy the theory in the real world.

I read a fair bit into the theory of abstract acceleration, where the idea is
that instead of widening indiscriminately, if our theory is powerful enough to
compute an exact closed form, we choose to do so. However, the problem is that
this regime does not "fit well" into abstract interpretation: We have the
abstract interpreter on the one hand, and then the acceleration regime on the
other, which is a separate algorithm. So the full analysis looks something
like:

```python
def analyze(program):
  analysis = {}
  for loop in inner to outer:
     loop_data = abstract_interpret(loop)
     analaysis.append(accelerate(loop))
  return analysis
```

That is, what used to be a nice theory of just "do things in any order and
it will converge", now becomes a new algorithm, that uses abstract interpretation
as a subroutine. This was not the hope I had! I wanted to _get away_ from having
to do proofs by analyzing an algorithm, this was the entire promise: Define
a lattice well enough and the proof is guaranteed. Rather, what I had 
imagined was:

```python
def analyze(program):
  return abstract_interpret_using_acceleration_domain(program)
```

Now this `acceleration_domain` maybe frightfully complicated, but I'm willing
to pay that price, as long as it's an honest-to-god abstract interpretation.
This was a huge bummer for me to find out that this is not the case.


# [Computing equivalent gate sets using grobner bases](#computing-equivalent-gate-sets-using-grobner-bases)

Here's a fun little problem, whose only solution I know involves a fair
bit of math and computer algebra:

We are given the grammar for a language `L`:

```
E = T +_mod8 E | T -_mod8 E | T
T = V | V ^ V | V ^ V ^ V
V = 'a1' | 'a2' | ...
```


where `+_mod8` is addition modulo 8, `-_mod8` is subtraction modulo 8,
and `^` is XOR. 

This language is equipped with the obvious
evaluation rules, corresponding to those of arithmetic. We are guaranteed 
that during evaluation, the variables `a_i` will only have values `0` and `1`.
Since we have addition, we can perform multiplication by a constant
by repeated addition. So we can perform `3*a` as `a+a+a`.


We are then given the input expression `(a0 ^ a1 ^ a2 ^ a3)`. We wish
to find an equivalent expression in terms of the above language `L`.

We think of `E` as some set of logic gates we are allowed to use, and we are
trying to express the operation `(a0 ^ a1 ^ a2 ^ a3)` in terms of these gates.

The first idea that I thought was that of employing a grobner basis,
since they essentially embody rewrite rules modulo polynomial equalities, which
is precisely our setting here.

In this blog post, I'm going to describe what a grobner basis is and why it's
natural to reach for them to solve this problem, the code, and the eventual
solution.

As a spolier, the solution is:

```
a^b^c^d =
-a - b + c + 3*d - 3*axorb - axorc
+ axord - bxorc + bxord + 3*cxord 
- 3*axorbxorc - axorbxord 
+ axorcxord + bxorcxord
```

Clearly, this contains only additions/subtractions and multiplications by
a constant.

If there's some principled way to derive this (beyond throwing symbolic
algebra machinery), I'd really love to know --- 
[Please raise an issue with the explanation!](https://github.com/bollu/bollu.github.io/issues)

##### What the hell is Grobner Basis?

The nutshell is that a grobner basis is a way to construct rewrite rules which
also understand arithmetic (I learnt this viewpoint from the book "Term
rewriting and all that". Fantastic book in general). Expanding on the
nutshell, assume we have a term rewriting system:

```
A -> -1*B -- (1)
C -> B^2  -- (2)
```

over an alphabet `{A, B, C}`.

Now, given the string `C + AB`, we wish to find out if it can be rewritten to 
`0` or not. Let's try to substitute and see what happens:

```
C + AB -2-> B^2 + AB -1-> B^2 + (-1*B)B
```

At this point, we're stuck! we don't have rewrite rules to allow us to
rewrite `(-1*B)B` into `-B^2`. Indeed, creating such a list would be 
infinitely long. But if we are willing to accept that we somehow have
the rewrite rules that correspond to polynomial arithmetic, where we view
`A, B, C` as variables, then we _can_ rewrite the above string to 0:

```
B^2 + (-1*B)B -> B^2 - B^2 -> 0
```

A Grobner basis is the algorithmic / mathematical machine that allows us
to perform this kind of substitution.

In this example, this might appear stupid: what is so special? We simply
substituted variables and arrived at `0` by using arithmetic. What's
so complicated about that? To understand why this is not always so easy,
let's consider a pathological, specially constructed example


##### A complicated example that shatters dreams

Here's the pathological example:

```
A -> 1     -- (1)
AB -> -B^2 -- (2)
```

And we consider the string `S = AB + B^2`.  If we blindly apply the
first rule, we arrive at:

```
S = AB + B^2 -1-> 1B + B^2 = B + B^2 (STUCK)
```

However, if we apply `(2)` and then `(1)`:

```
S = AB + B^2 -2-> -B^2 + B^2 -> 0
```

This tells us that we _can't just apply the rewrite rules willy-nilly_. 
It's sensitive to the _order_ of the rewrites! That is, the rewrite system
is not [confluent](https://en.wikipedia.org/wiki/Confluence_(abstract_rewriting)).


The grobner basis is a function from rewrite systems to rewrite systems.
When given a rewrite system `R`, it produces a _new_ rewrite system `R'`
that _is confluent_. So, we can apply the rewrite rules of `R'` in any order,
and we guaranteed that _we will only get a 0 from `R'` if and only if
we could have gotten a `0` from `R`_ for all strings.

We can then go on to phrase this whole rewriting setup in the language of
ideals from ring theory, and that is the language in which it is most 
often described. [I've gone into more depth on that perspective here: "What is a grobner basis? polynomial
factorization as rewrite systems"](#what-the-hell-is-a-grobner-basis-ideals-as-rewrite-systems).

Now that we have a handle on what a grobner basis is, let's go on to solve
the original problem:


##### An explanation through a slightly simpler problem

I'll first demonstrate the idea of how to solve the original problem
by solving a slightly simpler problem:

> Rewrite `a^b^c` in terms of `a^b`, `b^c`, `c^a` and the same `+_mod8` instruction
> set as the original problem. The only difference this time
> is that we do _not_ have `T -> V ^ V ^ V`.


The idea is to construct the polynomial ring over `Z/8Z` (integers modulo 8) with 
variables as `a, b, c, axorb, bxorc, axorc`. Now, we know that `a^b = a + b - 2ab`. So, 
we setup rewrite rules such that `a + b - 2ab -> axorb`, `b + c - 2bc -> bxorb`, 
`c + a - 2ca -> cxora`.


We construct the _polynomial_ `f(a, b, c) = a^b^c`, which
has been written in terms of addition and multiplication, defined
as `f_orig(a, b, c) = 4*a*b*c - 2*a*b - 2*a*c - 2*b*c + a + b + c`. We then
rewrite `f_orig` with respect to our rewrite rules. Hopefully, the rewrite
rules should give us a clean expression in terms of one variable and 
two-variable `xor`s. There is the danger that we may have some term
such as `a * bxorc`, and we do get such a term (`2*b*axorc`) in this case,
but it does not appear in the _original_ problem.



```py
# Create ring with variables a, b, c, axorb, bxorc, axorc
R = IntegerModRing(8)['a, b, c, axorb, bxorc, axorc']
(a, b, c, axorb, bxorc, axorc) = R.gens()


# xor of 2 numbers as a polynomial
def xor2(x, y): return x + y - 2*x*y

# xor of 3 numbers as a polynomial
def xor3(x, y, z): return xor2(x, xor2(y, z))

# define the ideal which contains relations:
# xor2(a, b) -> axorb, xor2(b, c) -> bxorc, xor2(a, c) -> axorc
# we also add the relation (a^2 - a = 0 => a = 0 or a = 1)
# since we know that our variables are only {0, 1}
I = ideal((axorb - xor2(a, b), bxorc - xor2(b, c), axorc - xor2(a, c), a*a-a, b*b-b, c*c-c))

# the polynomial representing a^b^c we wish to reduce
f_orig = xor3(a, b, c)

# we take the groebner basis of the ring to reduce the polynomial f.
IG = I.groebner_basis()

# we reduce a^b^c with respect to the groebner basis.
f_reduced = f_orig.reduce(IG)

print("value of a^b^c:\n\t%s\n\treduced: %s" % (f_orig, f_reduced))

# Code to evaluate the function `f` on all inputs to check correctness
def evalxor2(f):
    for (i, j, k) in [(i, j, k) for i in [0, 1] for j in [0, 1] for k in [0, 1]]:
      ref = i^^j^^k
      eval = f.substitute(a=i, b=j, c=k, axorb=i^^j, bxorc=j^^k, axorc=i^^k)
      print("%s^%s^%s: ref(%s) =?= f(%s): %s" % 
        (i, j, k, ref, eval, ref == eval))

# check original formulation is correct
print("evaulating original f for sanity check:")
evalxor2(f_orig)

# Check reduced formulation is correct
print("evaulating reduced f:")
evalxor2(f_reduced)
```

Running the code gives us the reduced polynomial `-2*b*axorc + b + axorc`
which unfortunately contains a term that is `b * axorc`. So, this approach
does not work, and I was informed by my friend that she is unaware
of a solution to this problem (writing `a^b^c` in terms of smaller xors and
sums).


The full code output is:

```
value of a^b^c:
	4*a*b*c - 2*a*b - 2*a*c - 2*b*c + a + b + c
	reduced: -2*b*axorc + b + axorc
evaulating original f for sanity check:
0^0^0: ref(0) =?= f(0): True
0^0^1: ref(1) =?= f(1): True
0^1^0: ref(1) =?= f(1): True
0^1^1: ref(0) =?= f(0): True
1^0^0: ref(1) =?= f(1): True
1^0^1: ref(0) =?= f(0): True
1^1^0: ref(0) =?= f(0): True
1^1^1: ref(1) =?= f(1): True
evaulating reduced f:
0^0^0: ref(0) =?= f(0): True
0^0^1: ref(1) =?= f(1): True
0^1^0: ref(1) =?= f(1): True
0^1^1: ref(0) =?= f(0): True
1^0^0: ref(1) =?= f(1): True
1^0^1: ref(0) =?= f(0): True
1^1^0: ref(0) =?= f(0): True
1^1^1: ref(1) =?= f(1): True
```

That is, both the original polynomial and the reduced polynomial match
the expected results. But the reduced polynomial is not in our language `L`,
since it has a term that is a _product_ of `b` with `axorc`. 


##### Tacking the original problem.

We try the exact same approach to the original problem of expressing
`a ^ b ^ c ^ d`. We find that the reduced polynomial is 

```
-a - b + c + 3*d - 3*axorb - axorc
+ axord - bxorc + bxord + 3*cxord 
- 3*axorbxorc - axorbxord 
+ axorcxord + bxorcxord
```

which happily has no products between terms! It also passes our sanity
check, so we've now found the answer.

The full output is:
```
value of a^b^c^d:
	4*a*b*c + 4*a*b*d + 4*a*c*d + 4*b*c*d 
      - 2*a*b - 2*a*c - 2*b*c - 2*a*d 
      - 2*b*d - 2*c*d + a + b + c + d
reduced: -a - b + c + 3*d - 3*axorb 
      - axorc + axord - bxorc + bxord 
      + 3*cxord - 3*axorbxorc 
      - axorbxord + axorcxord + bxorcxord
evaluating original a^b^c^d
0^0^0^0: ref(0) =?= f(0): True
0^0^0^1: ref(1) =?= f(1): True
0^0^1^0: ref(1) =?= f(1): True
0^0^1^1: ref(0) =?= f(0): True
0^1^0^0: ref(1) =?= f(1): True
0^1^0^1: ref(0) =?= f(0): True
0^1^1^0: ref(0) =?= f(0): True
0^1^1^1: ref(1) =?= f(1): True
1^0^0^0: ref(1) =?= f(1): True
1^0^0^1: ref(0) =?= f(0): True
1^0^1^0: ref(0) =?= f(0): True
1^0^1^1: ref(1) =?= f(1): True
1^1^0^0: ref(0) =?= f(0): True
1^1^0^1: ref(1) =?= f(1): True
1^1^1^0: ref(1) =?= f(1): True
1^1^1^1: ref(0) =?= f(0): True
evaluating reduced a^b^c^d
0^0^0^0: ref(0) =?= f(0): True
0^0^0^1: ref(1) =?= f(1): True
0^0^1^0: ref(1) =?= f(1): True
0^0^1^1: ref(0) =?= f(0): True
0^1^0^0: ref(1) =?= f(1): True
0^1^0^1: ref(0) =?= f(0): True
0^1^1^0: ref(0) =?= f(0): True
0^1^1^1: ref(1) =?= f(1): True
1^0^0^0: ref(1) =?= f(1): True
1^0^0^1: ref(0) =?= f(0): True
1^0^1^0: ref(0) =?= f(0): True
1^0^1^1: ref(1) =?= f(1): True
1^1^0^0: ref(0) =?= f(0): True
1^1^0^1: ref(1) =?= f(1): True
1^1^1^0: ref(1) =?= f(1): True
1^1^1^1: ref(0) =?= f(0): True
```

##### code for `a^b^c^d` reduction:


```py
def xor3(x, y, z): return xor2(x, xor2(y, z))

R = IntegerModRing(8)['a, b, c, d, axorb, axorc, axord, bxorc, bxord, cxord, axorbxorc, axorbxord, axorcxord, bxorcxord']

(a, b, c, d, axorb, axorc, axord, bxorc, bxord, cxord, axorbxorc, axorbxord, axorcxord, bxorcxord) = R.gens()
I = ideal((axorb - xor2(a, b),
           axorc - xor2(a, c),
           axord - xor2(a, d),
           bxorc - xor2(b, c),
           bxord - xor2(b, d),
           cxord - xor2(c, d),
           axorbxorc - xor3(a, b, c),
           axorbxord - xor3(a, b, d),
           axorcxord - xor3(a, c, d),
           bxorcxord - xor3(b, c, d),
           a*a-a,
           b*b-b,
           c*c-c,
           d*d-d
           ))
IG = I.groebner_basis()
f_orig = (xor2(a, xor2(b, xor2(c, d))))
f_reduced = f_orig.reduce(IG)
print("value of a^b^c^d:\n\t%s\n\treduced: %s" % (f_orig, f_reduced))

def evalxor3(f):
    for (i, j, k, l) in [(i, j, k, l) for i in [0, 1] for j in [0, 1] for k in [0, 1] for l in [0, 1]]:
      ref = i^^j^^k^^l
      eval = f.substitute(a=i, b=j, c=k, d=l,
                          axorb=i^^j, axorc=i^^k,
                          axord=i^^l, bxorc=j^^k,
                          bxord=j^^l, cxord=k^^l,
                          axorbxorc=i^^j^^k, axorbxord=i^^j^^l,
                          axorcxord=i^^k^^l, bxorcxord=j^^k^^l)
      print("%s^%s^%s^%s: ref(%s) =?= f(%s): %s" % 
        (i, j, k, l, ref, eval, ref == eval))

print("evaluating original a^b^c^d")
evalxor3(f_orig)


print("evaluating reduced a^b^c^d")
evalxor3(f_reduced)
```

##### Closing thoughts

This was a really fun exercise: Around a hundred lines of code illuminates
the use of machinery such as grobner basis for solving real-world problems!
I really enjoyed hacking this up and getting nerd sniped.


# [The janus programming language --- Time reversible computation](#the-janus-programming-language--time-reversible-computation)

- [Wiki link](https://en.wikipedia.org/wiki/Janus_(time-reversible_computing_programming_language))
- [Original letter to Landlauer](http://tetsuo.jp/ref/janus.pdf)

I found out it's called Janus, since Janus is the god of doorways in greek
mythology. Hence, he is also the god of duality and transitions --- he
_literally_ looks both into the future and into the past.

> He is usually depicted as having two faces, since he looks to the future and
> to the past.

An apt name for the language!

# [`A = B` --- A book about proofs of combinatorial closed forms](#a--b--a-book-about-proofs-of-combinatorial-closed-forms)


The book explains algorithms on solving closed forms for combinatorial
recurrences, by means of [Zeilberger's algorithm](http://mathworld.wolfram.com/ZeilbergersAlgorithm.html).

The book is written by Zeilberger himself, and supposedy also teaches one Maple.
I'd like to learn the algorithm, since it might be useful eventually for
Groebner basis / loop analysis shenanigans I like to play as part of
my work on compilers.

- [Download link here](https://www.math.upenn.edu/~wilf/AeqB.pdf)

# [Generating `k` bitsets of a given length `n`](#generating-k-bitsets-of-a-given-length-n):

The problem is to generate all bitvectors of length `n` that have `k` bits
set. For example, generate all bitvectors of length `5` that have `3` bits
set.

I know that an algorithm exists in Hacker's delight, but I've been too sick
to crack open a book, so I decided to discover the algorithm myself. The one
I came up with relies on looking at the numbers moving at a certain velocity,
and them colliding with each other. For example, let us try to generate all
`5C3` combinations of bits.


We start wih:
```
#1           count of position
a b c d e    positions
1 1 1 0 0    bitset 
< - - - -    velocity
```

Where the `<` represents that the `1` at position `a` is moving leftwards.
Our arena is _circular_, so the leftmost `1` can wrap around to the right.
This leads to the next state

```
#2
a b c d e
0 1 1 0 1
- - - - <
```

We continue moving left peacefully.

```
#3
a b c d e
0 1 1 1 0
- - - < -
```

whoops, we have now collided with a block of `1`s. Not to worry, we simply
transfer our velocity by way of collision, from the `1` at `d` to the `1` at `b`.

I denote the transfer as follows:
```
#3
a b c d e
0 1 1 1 0  original state
- - - < -
- < < < -  transfer of velocity
- < - - -  final state after transfer of velocity
```    

The `1` at `b` proceeds along its merry way with the given velocity

```
#4
a b c d e
1 0 1 1 0
< - - - -
```

Once again, it wraps around, and suffers a collision

```
#5
a b c d e
0 0 1 1 1
- - - - - < (collision, transfer)
- - < < < transfer of velocity
- - < - - final state after transfer of velocity
```

This continues:

```
0 1 0 1 1  #6
- < - - -
1 0 0 1 1  #7
< - - - - (collision, transfer velocity)
< - - < <
- - - < -
1 0 1 0 1 #8
- - < - -
1 1 0 0 1 #9
- < - - - (colision, transfer velocity
< < - - <
- - - - <
1 1 0 1 0 #10
- - - < - 
1 1 1 0 0 #11: wrap around to initial state
```

I don't have a proof of correctness, but I have an intuition that this
should generate all states. Does anyone have a proof?

_EDIT:_ [this algorithm does not work](https://math.stackexchange.com/questions/3398241/correctness-proof-for-algorithm-to-generate-k-bitsets-of-n-bits-nck),
since it will keep clusters of $k-1$ bits next to each other, when a 
bit hits a cluster of $k - 1$ bits.  For completeness, I'm going to draft out
the usual algorithm in full:

### Usual Algorithm

Let's consider the same example of `5C3`:

```
   a b c d e
1| 0 0 1 1 1 (LSB)
```

We start with all bits at their lowest position. Now, we try to go to
the next smallest number, which still has 3 bits toggled. Clearly, we need
the bit at position `b` to be 1, since that's the next number. Then,
we can keep the lower 2 bits `d, e` set to 1, so that it's still as small a
number as possible.

```
   a b c d e
2| 0 1 0 1 1 (LSB)
```

Once again, we now move the digit at `d` to the digit at `c`, while keeping
the final digit at `e` to make sure it's still the smallest possible.

```
   a b c d e
3| 0 1 1 0 1 (LSB)
```

Now, we can move the `1` at `e` to `d`, since that will lead to the smallest
increase:

```
   a b c d e
4| 0 1 1 1 0 (LSB)
```

At this point, we are forced to move to location `a`, since we have exhausted
all smaller locations. so we move the `1` at `b` to `a`, and then reset all
the other bits to be as close to the LSB as possible:

```
   a b c d e
5| 1 0 0 1 1 (LSB)
```

Continuing this process gives us the rest of the sequence:

```
    a b c d e
5 | 1 0 0 1 1
6 | 1 0 1 0 1
7 | 1 0 1 1 0
8 | 1 1 0 0 1 (note the reset of d!)
9 | 1 1 0 1 0
10| 1 1 1 0 0
```
# [Bondi k-calculus](#bondi-k-calculus)

- [Link here](https://en.wikipedia.org/wiki/Bondi_k-calculus)

An alternative formalism to derive special relativity geometrically,
resting purely on hypotehses about the way light travels.

However, I've not been able to prove the correctness of the assumptions made,
by using coordinate geometry. I suspect this is because I will need to use
hyperbolic geometry for the "side lengths" to work out.


Indeed, I found another source, called as [The k-calculus fiddle](http://bearsoft.co.uk/Kcalc.html)
which attempts to discredit k-calculus. The author of the above blog writes at
the end:

> In asking Ray D'Inverno's permission to use his book as the example of
> k-calculus, he was kind enough to point out that the arguments I have given
> are invalid. Chapter 2 of his book should be read through to the end and then
> reread in the light of the fact that the geometry of space and time is
> Minkowskian. Euclidean geometry should not be used in interpreting the
> diagrams because their geometry is Minkowskian.

which seems to imply that we need to use hyperbolic geometry for this.

# Topology as an object telling us what zero-locus is closed:

- [Idea from this amazing post on `math.se`](https://math.stackexchange.com/questions/53852/is-there-a-way-of-working-with-the-zariski-topology-in-terms-of-convergence-limi)

# [Vivado toolchain craziness ](#vivado-toolchain-craziness)

I found this file as I was cleaning up some old code, for a project to implement
a [fast K/V store on an FPGA](https://github.com/AakashKT/CuckooHashingHLS),
so I thought I should put this up for anyone else who stumbles on the
same frustrations / errors. I'm not touching this particular toolchain again
with a 10-foot pole till the tools stabilize by *a lot*.

##### Vivado HLS issues


- Unable to create BRAM for fields such as `bool`, `int16`. The data buses
will be `8/16` bits long, with error:

```
[BD 41-241] Message from IP propagation TCL of /blk_mem_gen_7: set_property
error: Validation failed for parameter 'Write Width A(Write_Width_A)' for BD
Cell 'blk_mem_gen_7'. Value '8' is out of the range (32,1024) Customization
errors found on 'blk_mem_gen_7'. Restoring to previous valid configuration.
```

- I had an array of structs:

```cpp
struct S {
    bool b;
    int16 x;
    int16 y;
}
```

This gets generated as 3 ports for memory, of widths `1`, `16`, `16`. Ideally,
I wanted *one* port, of width `16+16+1=33`, for each struct value.
However, what was generated were three ports of widths `1`, `16`, and `16`
which I cannot connect to BRAM.

- `data_pack` allows us to create one port of width `16+16+1=33`

- Shared function names allocated on BRAM causes errors in synthesis:


```cpp
struct Foo {...};
void f (Foo conflict) {
    #pragma HLS interface bram port=conflict
}

void g (Foo conflict) {
    #pragma HLS interface bram port=conflict
}
```

- Enums causes compile failure in RTL generation  (commit `3c0d619039cff7a7abb61268e6c8bc6d250d8730`)
- `ap_int` causes compile failurre in RTL generation (commit `3c0d619039cff7a7abb61268e6c8bc6d250d8730`)
- `x % m` where `m != 2^k` is very expensive -- there must be faster encodings of modulus?
- How to share code between HLS and vivado SDK? I often wanted to share constant values between
  my HLS code and my Zynq code.
- Can't understand why array of structs that were packed does not get deserialized correctly. I had to manually
  pack a struct into a `uint32`. For whatever reason, having a `#pragma pack` did something to the representation of the struct
  as far as I can tell, and I couldn't treat the memory as just a raw `struct *` on the other side:


```cpp
// HLS side
struct Vec2  { int x; int y};
void f(Vec2 points[NUM_POINTS]) {
	#pragma HLS DATA_PACK variable=points
    #pragma HLS INTERFACE bram port=points

    points[0] = {2, 3};
}

// Host side
Vec2 *points = (Vec2 *)(0xPOINTER_LOCATION_FROM_VIVADO);

int main() {
    // points[0] will *not* be {2, 3}!
}
```

- If I change my IP, there is no way to preserve the current connections in the
  GUI why just updating the "changed connections". I'm forced to remove the IP
  and add it again (no, the Refresh IP button does not work).
- On generating a new bitstream from Vivado, Vivado SDK tries to reload the config,
fails at the reloading (thinks `xil_print.h` doesn't exist), and then fails to compile code.
Options are to either restart Vivado SDK, or refresh `xil_print.h`.


- It is entirely unclear what to version control in a vivado project, unless one
has an omniscient view of the _entire toolchain_. I resorted to `git add` ing 
everything, but this is a terrible strategy in so many ways.


#### SDAccel bugs

**[link to tutorial we were following](https://www.xilinx.com/support/documentation/sw_manuals/xilinx2017_1/ug1028-sdsoc-intro-tutorial.pdf)**
- The executable is named `.exe` while it's actually an ELF executable (The SDAccel tutorials say it is called as `.elf`)
- the board is supposed to automatically boot into linux, which it does not. One is expected to call `bootd` manually (for "boot default") so it boots ito linux. (The SDAccel tutorials say it automatically boots into it)
- At this point, the SD card is unreadable. It took a bunch of time to figure out that the SD card needs to be mounted by us, and has the mount name `/dev/mmcblk0p1`. (The SDAccel tutorials say that it should be automatically mounted)
- At this point, we are unable to run `hashing.elf`. It dies with a truly bizarre error: `hashing.elf: command not found`. This is almost un-googleable, due to the fact that the same problem occurs when people don't have the correct file name.
- I rewrote `ls` with `hashing.elf` to see what would happen, because I conjectured that the shell was able to run `coreutils`. 
- This dies with a different error `ls: core not found`. I'd luckily seen this during my android days, and knew this was from busybox.
- This led me to google "busybox unable to execute executable", which led me to this [StackOverflow link](https://stackoverflow.com/questions/1562071/how-can-i-find-which-elf-dependency-is-not-fulfilled) that clued me into the fact that the ELF interpreter is missing.
- When I discovered this, I wound up trying to understand how to get the right ELF interpreter. `readelf -l <exe name>` dumps out `[Requesting program interpreter: /lib/ld-linux-armhf.so.3]`. So, I bravely copied: `cp /lib/ld-linux.so.3 /lib/ld-linux-armhf.so.3`.
- Stuff is *still* broken, but I now get *useful* error messages:
```
zynq> /hashing.elf 
/hashing.elf: error while loading shared libraries:
libxilinxopencl.so: cannot open shared object file: No such file or directory
```
At this point, clearly we have some linker issues (why does `xocc` not correctly statically link? What's up with it? Why does it expect it to be able to load a shared library? **WTF is happening**). do note that this is _not_ the way the process
is supposed to go according to the tutorial!  
- Of course, there's no static library version of `libxilinxopencl.so`, so that's a dead end. I'm completely unsure if the tutorial even makes sense. 
- This entire chain of debugging is full of luck.

- [Link talking about generating `BOOT` file](https://www.xilinx.com/html_docs/xilinx2018_2/sdsoc_doc/compiling-and-running-applications-on-arm-processor-hjy1504034381720.html)


At some point, I gave up on the entire enterprise.

# [What the hell _is_ a Grobner basis? Ideals as rewrite systems](#what-the-hell-is-a-grobner-basis-ideals-as-rewrite-systems)

##### A motivating example

The question a Grobner basis allows us to answer is this: can the polynomial
$p(x, y) = xy^2 + y$ be factorized in terms of $a(x, y) = xy + 1, b(x, y) = y^2 - 1$,
such that $p(x, y) = f(x, y) a(x, y) + g(x, y) b(x, y)$ for some _arbitrary_ polynomials
$f(x, y), g(x, y) \in R[x, y]$.

One might imagine, "well, I'll divide and see what happens!" Now, there are two
routes to go down:

- $xy^2 + y = y(xy + 1) = y a(x, y) + 0 b(x, y)$. Well, problem solved?
- $xy^2 + y = xy^2 - x + x + y = x (y^2 - 1) + x + y = x b(x, y) + (x + y)$. Now what? we're stuck, and we can't apply `a(x, y)`!

So, clearly, the _order_ in which we perform of factorization / division starts
to matter! Ideally, we want an algorithm which is _not sensitive_ to the order
in which we choose to apply these changes. $x^2 + 1$.


##### The rewrite rule perspective


An alternative viewpoint of asking "can this be factorized", is to ask
"can we look at the factorization as a rewrite rule"? For this perspective,
notice that "factorizing" in terms of $xy + 1$ is the same as being
able to set $xy = -1$, and then have the polynomial collapse to zero.
(For the more algebraic minded, this relates to the fact that $R[x] / p(x) \sim R(\text{roots of p})$).
The intuition behind this is that when we "divide by $xy + 1$", really what
we are doing is we are setting $xy + 1 = 0$, and then seeing what remains. But
$xy + 1 = 0 \iff xy = -1$. Thus, we can look at the original question as:

How can we apply the rewrite rules $xy \rightarrow -1$, $y^2 \rightarrow 1$,
along with the regular rewrite rules of polynomial arithmetic to the polynomial
$p(x, y) = xy^2 + y$, such that we end with the value $0$?

Our two derivations above correspond to the application of the rules:

- $xy^2 + y \xrightarrow{xy = -1} -y + y = 0$
- $xy^2 + y \xrightarrow{y^2 = 1} x + y \nrightarrow \text{stuck!}$

That is, our [rewrite rules are not confluent](https://en.wikipedia.org/wiki/Confluence_(abstract_rewriting))

The grobner basis is a mathematical object, which is a  _a confluent set of rewrite rules_
for the above problem. That is, it's a set of polynomials which manage to find
the rewrite $p(x, y) \xrightarrow{\star} 0$, regardless of the order in which
we apply them. It's also _correct_, in that it only rewrites to $0$ if the
original system had _some way_ to rewrite to $0$.

###### The buchberger's algorithm

We need to identify 
[critical pairs](https://en.wikipedia.org/wiki/Critical_pair_(logic)), 
which in this setting are called as S-polynomials.

Let $f_i = H(f_i) + R(f_i)$ and $f_j = H(f_j) + R(f_j)$. Let $m = lcm(H(f_i), H(f_j))$,
and let $m_i, m_j$ be monomials such that $m_i \cdot H(f_i) = m = m_j \cdot H(f_j)$.
The S-polynomial induced by $f_i, f_j$ is defined as $S(f_i, f_j) = m_i f_i - m_i f_j$.


##### References
- [The term rewriting perspective is from the book "term rewriting and all that"](https://www21.in.tum.de/~nipkow/TRaAT/)
- [Sympy has excellent reading material on grobner basis](https://mattpap.github.io/masters-thesis/html/src/groebner.html)


# [Lie bracket versus torsion](lie-bracket-versus-torsion)


![torsion-vs-parallel-transport](static/lie-bracket-versus-torsion.png)

This picture _finally_ made the difference between these two things clear.
The lie bracket moves along the _flow_, while the torsion moves along
_parallel transport_. 

This is why the sides of the parallelogram that measure torsion form,
well, a parallelogram: we set them up using parallel transport.

On the other hand, the lie bracket measures the actual failure of the parallelogram
from being formed.

# [Blog post: Weekend paper replication of STOKE, the stochastic superoptimizer](https://github.com/bollu/blaze/blob/master/notebooks/tutorial.ipynb)

Click the title to go to the post. We replicate the `STOKE` paper in haskell,
to implement a superoptimiser based on MCMC methods.

# Collapsing `BlockId`, `Label`, `Unique`: 

We have this hiearchy of `BlockId`, `Label`, and `Unique` that can be
collapsed. 


# [Spatial partitioning data structures in molecular dynamics](#spatial-partitioning-data-structures-in-molecular-dynamics)

- [Cell lists](https://en.wikipedia.org/wiki/Cell_lists)
- [Verlet lists](https://en.wikipedia.org/wiki/Verlet_list)

appear to be version of spatial hierarchical data structures for fast
interaction computation. Apparently, multipole expansions are not useful
in this case since multipole expansions are useful to take into account
long range effects, but not short range effects.


# [Vector: Arthur Whitney and text editors](#vector-arthur-whitney-and-text-editors)

- http://archive.vector.org.uk/art10501320


# Representing CPS in LLVM using the `@coro.*` intrinsics

This is part of a larger thread --- [Adding CPS call support to LLVM](http://lists.llvm.org/pipermail/llvm-dev/2017-April/112212.html) where there is a large discussion on the correct design of how to teach LLVM about CPS.

Gor Nishanov proided the above example of encoding CPS using the llvm `coro` instructions.

- https://gist.github.com/bollu/e0573dbc145028fb42f89e64c6dd6742

# Bug in the LLVM code generator: Lowering of `MO_Add2` and `MO_AddWordC`

[Both of these are lowered the same way](https://github.com/ghc/ghc/blob/bf73419518ca550e85188616f860961c7e2a336b/compiler/llvmGen/LlvmCodeGen/CodeGen.hs#L817),
but they should be different. 

In particular, `GHC.Prim` explains:
- [`AddWordC#`](http://hackage.haskell.org/package/ghc-prim-0.5.3/docs/GHC-Prim.html#v:addWordC-35-) returns `(result, carry)`
- [`PlusWordC#`](http://hackage.haskell.org/package/ghc-prim-0.5.3/docs/GHC-Prim.html#v:plusWord-35-) returns `(carry, result)`

Honestly, this is confusing, but I guess there's some story to having two separate primops for this?


# [Discrete random distributions with conditioning in 20 lines of haskell](#discrete-random-distributions-with-conditioning-in-20-lines-of-haskell)

```hs
newtype D a = D { unD :: [(a, Double)] } deriving(Eq, Show, Ord)

instance Functor D where
    -- fmap :: (a -> b) -> D a -> D b
    fmap f (D xs) = D $ fmap (\(a, d) -> (f a, d)) xs

instance Monad D where
    return x = D $ [(x, 1.0)]
    -- f :: a -> (D b)
    (D as) >>= f = D $ do -- list monad
                      (a, p) <- as
                      (b, p2) <- unD (f a)
                      return $ (b, p * p2)

-- [(a, 0.5), (b, 0.5)]
-- [(a, 0.3), (a, 0.2), (b, 0.1), (b, 0.4)]
--
instance Applicative D where
    pure = return
    ff <*> fa = do
        f <- ff
        a <- fa
        return $ f  a

condition :: Bool -> D ()
condition True = D [((), 1.0)]
condition False = D [((), 0.0)]


dice :: D Int
dice = let p = 1.0 / 6 in D $ [(x, p) | x <- [1..6]]


dice_hard :: D Int
dice_hard = do
    x <- dice
    condition $ x > 3
    return $ x


main :: IO ()
main = do
    print dice
    print dice_hard
```

This gives the output:

```
D {unD = [(1,0.16666666666666666),
          (2,0.16666666666666666),
          (3,0.16666666666666666),
          (4,0.16666666666666666),
          (5,0.16666666666666666),
          (6,0.16666666666666666)]}
          
D {unD = [(1,0.0),
          (2,0.0),
          (3,0.0),
          (4,0.16666666666666666),
          (5,0.16666666666666666),
          (6,0.16666666666666666)]}
```

Notice that `D a ~= WriterT (Product Float) []`!

# [Everything you know about word2vec is wrong](#everything-you-know-about-word2vec-is-wrong)

The classic explanation of `word2vec`, in skip-gram, with negative sampling,
in the paper and countless blog posts on the internet is as follows:

```
while(1) {
   1. vf = vector of focus word
   2. vc = vector of context word
   3. train such that (vc . vf = 1)
   4. for(0 <= i < negative samples):
           vneg = vector of word *not* in context
           train such that (vf . vneg = 0)
}
```

Indeed, if I google "word2vec skipgram", the results I get are:
- [The wikipedia page which describes the algorithm on a high level](https://en.wikipedia.org/wiki/Word2vec#Training_algorithm)
- [The tensorflow page with the same explanation](https://www.tensorflow.org/tutorials/representation/word2vec)
- [The towards data science blog which describes the same algorithm](https://towardsdatascience.com/word2vec-skip-gram-model-part-1-intuition-78614e4d6e0b)
the list goes on. However, __every single one of these implementations is wrong__.

The original word2vec `C` implementation does _not_ do what's explained above,
and is _drastically different_. Most serious users of word embeddings, who use
embeddings generated from `word2vec` do one of the following things:

1. They invoke the original C implementation directly.
2. They invoke the `gensim` implementation, which is _transliterated_ from the
   C source to the extent that the variables names are the same.

Indeed, the `gensim` implementation is the _only one that I know of which 
is faithful to the C implementation_.

### The C implementation

The C implementation in fact maintains _two vectors for each word_, one where
it appears as a focus word, and one where it appears as a context word. 
(Is this sounding familiar? Indeed, it appears that GloVe actually took this
idea from `word2vec`, which has never mentioned this fact!)

The setup is incredibly well done in the C code:

- An array called `syn0` holds the vector embedding of a word when it occurs
as a _focus word_. This is __random initialized__. 

```cpp
https://github.com/tmikolov/word2vec/blob/20c129af10659f7c50e86e3be406df663beff438/word2vec.c#L369
  for (a = 0; a < vocab_size; a++) for (b = 0; b < layer1_size; b++) {
    next_random = next_random * (unsigned long long)25214903917 + 11;
    syn0[a * layer1_size + b] = 
       (((next_random & 0xFFFF) / (real)65536) - 0.5) / layer1_size;
  }

```

- Another array called `syn1neg` holds the vector of a word when it occurs
as a _context word_. This is __zero initialized__.

```cpp
https://github.com/tmikolov/word2vec/blob/20c129af10659f7c50e86e3be406df663beff438/word2vec.c#L365
for (a = 0; a < vocab_size; a++) for (b = 0; b < layer1_size; b++)
  syn1neg[a * layer1_size + b] = 0;
```

- During training (skip-gram, negative sampling, though other cases are 
also similar), we first pick a focus word. This is held constant throughout
the positive and negative sample training. The gradients of the focus vector
are accumulated in a buffer, and are applied to the focus word 
_after it has been affected by both positive and negative samples_.

```cpp
if (negative > 0) for (d = 0; d < negative + 1; d++) {
  // if we are performing negative sampling, in the 1st iteration,
  // pick a word from the context and set the dot product target to 1
  if (d == 0) {
    target = word;
    label = 1;
  } else {
    // for all other iterations, pick a word randomly and set the dot
    //product target to 0
    next_random = next_random * (unsigned long long)25214903917 + 11;
    target = table[(next_random >> 16) % table_size];
    if (target == 0) target = next_random % (vocab_size - 1) + 1;
    if (target == word) continue;
    label = 0;
  }
  l2 = target * layer1_size;
  f = 0;

  // find dot product of original vector with negative sample vector
  // store in f
  for (c = 0; c < layer1_size; c++) f += syn0[c + l1] * syn1neg[c + l2];

  // set g = sigmoid(f) (roughly, the actual formula is slightly more complex)
  if (f > MAX_EXP) g = (label - 1) * alpha;
  else if (f < -MAX_EXP) g = (label - 0) * alpha;
  else g = (label - expTable[(int)((f + MAX_EXP) * (EXP_TABLE_SIZE / MAX_EXP / 2))]) * alpha;

  // 1. update the vector syn1neg,
  // 2. DO NOT UPDATE syn0
  // 3. STORE THE syn0 gradient in a temporary buffer neu1e
  for (c = 0; c < layer1_size; c++) neu1e[c] += g * syn1neg[c + l2];
  for (c = 0; c < layer1_size; c++) syn1neg[c + l2] += g * syn0[c + l1];
}
// Finally, after all samples, update syn1 from neu1e
https://github.com/tmikolov/word2vec/blob/20c129af10659f7c50e86e3be406df663beff438/word2vec.c#L541
// Learn weights input -> hidden
for (c = 0; c < layer1_size; c++) syn0[c + l1] += neu1e[c];
```

### Why random and zero initialization?

Once again, since none of this actually explained in the original papers
_or on the web_, I can only hypothesize.

My hypothesis is that since the negative samples come from all over the text
and are not really weighed by frequency, you can wind up picking _any word_,
and more often than not, _a word whose vector has not been trained much at all_.
If this vector actually had a value, then it could move the actually important
focus word randomly. 

The solution is to set all negative samples to zero, so that _only vectors
that have occurred somewhat frequently_ will affect the representation of
another vector.

It's quite ingenious, really, and until this, I'd never really thought of
how important initialization strategies really are.


### Why I'm writing this

I spent two months of my life trying to reproduce `word2vec`, following
the paper exactly, reading countless articles, and simply not succeeding.
I was unable to reach the same scores that `word2vec` did, and it was not
for lack of trying.

I could not have imagined that the paper would have literally fabricated an
algorithm that doesn't work, while the implementation does something completely
different.

Eventually, I decided to read the sources, and spent three whole days convinced
I was reading the code wrong since literally everything on the internet told me
otherwise.

I don't understand why the original paper and the internet contain zero
explanations of the _actual_ mechanism behind `word2vec`, so I decided to put
it up myself.

This also explains GloVe's radical choice of having a separate vector
for the negative context --- they were just doing what `word2vec` does, but
they told people about it `:)`.

Is this academic dishonesty? I don't know the answer, and that's a heavy
question. But I'm frankly incredibly pissed, and this is probably the last
time I take a machine learning paper's explanation of the algorithm
seriously again --- from next time, I read the source _first_. 

# Hamiltonian monte carlo, leapfrog integrators, and sympletic geometry

This is a section that I'll update as I learn more about the space, since I'm studying
differential geometry over the summer, I hope to know enough about "sympletic manifolds".
I'll make this an append-only log to add to the section as I understand more.

##### 31st May

- To perform hamiltonian monte carlo, we use the hamiltonian and its derivatives to provide
a momentum to our proposal distribution --- That is, when we choose a new point from the
current point, our probability distribution for the new point is influenced by our
current momentum

- For some integral necessary within this scheme, Euler integration doesn't cut it 
since the error diverges to infinity

- Hence, we need an integrator that guarantees that the energy of out system is conserved.
Enter the leapfrog integrator. This integrator is also _time reversible_ -- We can run it
forward for `n` steps, and then run it backward for `n` steps to arrive at the same state.
Now I finally know how Braid was implemented, something that bugged the hell out of 9th grade me
when I tried to implement Braid-like physics in my engine!

- The actual derivation of the integrator uses Lie algebras, Sympletic geometry, and other
diffgeo ideas, which is great, because it gives me motivation to study differential geometry `:)`

- Original paper: [Construction of higher order sympletic integrators](https://www.sciencedirect.com/science/article/abs/pii/0375960190900923)

##### Simulating orbits with large timesteps

![euler-vs-leapfrog](static/leapfrog-vs-euler.png)

Clearly, the leapfrog integrator preserves energy and continues to move
in an orbit, while the euler integrator goes batshit and causes orbits
to spiral outwards. Full code is available below. More of the code is 
spent coaxing matplotlib to look nice, than doing the actual
computation.

```py
import numpy as np
import matplotlib.pyplot as plt
import numpy.linalg

# dq/dt = dH/dp | dp/dt = -dH/dq (a = -del V)
def leapfroge(dhdp, dhdq, q, p, dt):
    p += -dhdq(q, p) * 0.5 * dt # halfstep momentum
    q += dhdp(q, p) * dt # fullstep position
    p += -dhdq(q, p) * 0.5 * dt # halfstep momentum
    return (q, p)

def euler(dhdp, dhdq, q, p, dt):
    pnew = p + -dhdq(q, p) * dt
    qnew = q + dhdp(q, p) * dt

def planet(integrator, n, dt):
    STRENGTH = 0.5

    q = np.array([0.0, 1.0]); p = np.array([-1.0, 0.0])
    
    # H = STRENGTH * |q| (potential) + p^2/2 (kinetic)
    def H(qcur, pcur): return STRENGTH * np.linalg.norm(q) + np.dot(p, p) / 2
    def dhdp(qcur, pcur): return p
    def dhdq(qcur, pcur): return STRENGTH * 2 * q / np.linalg.norm(q)
    
    qs = []
    for i in range(n):
        (q, p) = integrator(dhdp, dhdq, q, p, dt)
        qs.append(q.copy())
    return np.asarray(qs)

NITERS = 15
TIMESTEP = 1

plt.rcParams.update({'font.size': 22, 'font.family':'monospace'})
fig, ax = plt.subplots()

planet_leapfrog = planet(leapfroge, NITERS, TIMESTEP)
ax.plot(planet_leapfrog[:, 0], planet_leapfrog[:, 1], label='leapfrog',
        linewidth=3, color='#00ACC1')
planet_euler = planet(euler, NITERS, TIMESTEP)
ax.plot(planet_euler[:, 0], planet_euler[:, 1], label='euler',
        linewidth=3, color='#D81B60')

legend = plt.legend(frameon=False)
ax.set_title("leapfrog v/s euler: NITERS=%s dt=%s" % (NITERS, TIMESTEP))
ax.spines['top'].set_visible(False)
ax.spines['right'].set_visible(False)
ax.spines['bottom'].set_visible(False)
ax.spines['left'].set_visible(False)
plt.show()
plt.savefig("leapfrog-vs-euler.png")
```

# [Small Haskell MCMC implementation](#small-haskell-mcmc-implementation)

We create a simple monad called `PL` which allows for a single operation: sampling
from a uniform distribution. We then exploit this to implement MCMC using metropolis hastings,
which is used to sample from arbitrary distributions. Bonus is a small library to render sparklines
in the CLI.

For next time:

- Using applicative to speed up computations by exploiting parallelism
- Conditioning of a distribution wrt a variable

### Source code
```hs
{-# LANGUAGE GeneralizedNewtypeDeriving #-}
{-# LANGUAGE GADTs #-}
{-# LANGUAGE StandaloneDeriving #-}
{-# LANGUAGE FlexibleContexts #-}
{-# LANGUAGE FlexibleInstances #-}
{-# LANGUAGE UndecidableInstances #-}
{-# LANGUAGE DeriveFunctor #-}
import System.Random
import Data.List(sort, nub)
import Data.Proxy
import Control.Monad (replicateM)
import qualified Data.Map as M


-- | Loop a monadic computation.
mLoop :: Monad m =>
      (a -> m a) -- ^ loop
      -> Int -- ^ number of times to run
      -> a -- initial value
      -> m a -- final value
mLoop _ 0 a = return a
mLoop f n a = f a >>= mLoop f (n - 1)


-- | Utility library for drawing sparklines

-- | List of characters that represent sparklines
sparkchars :: String
sparkchars = "_▁▂▃▄▅▆▇█"

-- Convert an int to a sparkline character
num2spark :: RealFrac a => a -- ^ Max value
  -> a -- ^ Current value
  -> Char
num2spark maxv curv =
   sparkchars !!
     (floor $ (curv / maxv) * (fromIntegral (length sparkchars - 1)))

series2spark :: RealFrac a => [a] -> String
series2spark vs =
  let maxv = if null vs then 0 else maximum vs
  in map (num2spark maxv) vs

seriesPrintSpark :: RealFrac a => [a] -> IO ()
seriesPrintSpark = putStrLn . series2spark

-- Probabilities
-- ============
type F = Float
-- | probability density
newtype P = P { unP :: Float } deriving(Num)

-- | prob. distributions over space a
newtype D a = D { runD :: a -> P }

uniform :: Int -> D a
uniform n =
  D $ \_ -> P $ 1.0 / (fromIntegral $ n)

(>$<) :: Contravariant f => (b -> a) -> f a  -> f b
(>$<) = cofmap

instance Contravariant D where
  cofmap f (D d) = D (d . f)

-- | Normal distribution with given mean
normalD :: Float ->  D Float
normalD mu = D $ \f -> P $ exp (- ((f-mu)^2))

-- | Distribution that takes on value x^p for 1 <= x <= 2.  Is normalized
polyD :: Float -> D Float
polyD p = D $ \f -> P $ if 1 <= f && f <= 2 then (f ** p) * (p + 1) / (2 ** (p+1) - 1) else 0

class Contravariant f where
  cofmap :: (b -> a) -> f a -> f b

data PL next where
    Ret :: next -> PL next -- ^ return  a value
    Sample01 :: (Float -> PL next) -> PL next -- ^ sample uniformly from a [0, 1) distribution

instance Monad PL where
  return = Ret
  (Ret a) >>= f = f a
  (Sample01 float2plnext) >>= next2next' =
      Sample01 $ \f -> float2plnext f >>= next2next'

instance Applicative PL where
    pure = return
    ff <*> fx = do
        f <- ff
        x <- fx
        return $ f x

instance Functor PL where
    fmap f plx = do
         x <- plx
         return $ f x

-- | operation to sample from [0, 1)
sample01 :: PL Float
sample01 = Sample01 Ret


-- | Run one step of MH on a distribution to obtain a (correlated) sample
mhStep :: (a -> Float) -- ^ function to score sample with, proportional to distribution
  -> (a -> PL a) -- ^ Proposal program
  -> a -- current sample
  -> PL a
mhStep f q a = do
 	a' <- q a
 	let alpha = f a' / f a -- acceptance ratio
 	u <- sample01
 	return $ if u <= alpha then a' else a

-- Typeclass that can provide me with data to run MCMC on it
class MCMC a where
    arbitrary :: a
    uniform2val :: Float -> a

instance MCMC Float where
	arbitrary = 0
	-- map [0, 1) -> (-infty, infty)
	uniform2val v = tan (-pi/2 + pi * v)


{-
-- | Any enumerable object has a way to get me the starting point for MCMC
instance (Bounded a, Enum a) => MCMC a where
     arbitrary = toEnum 0
     uniform2val v = let
        maxf = fromIntegral . fromEnum $ maxBound
        minf = fromIntegral . fromEnum $ minBound
        in toEnum $ floor $ minf + v * (maxf - minf)
-}


-- | Run MH to sample from a distribution
mh :: (a -> Float) -- ^ function to score sample with
 -> (a -> PL a) -- ^ proposal program
 -> a -- ^ current sample
 -> PL a
mh f q a = mLoop (mhStep f q) 100  $ a

-- | Construct a program to sample from an arbitrary distribution using MCMC
mhD :: MCMC a => D a -> PL a
mhD (D d) =
    let
      scorer = (unP . d)
      proposal _ = do
        f <- sample01
        return $ uniform2val f
    in mh scorer proposal arbitrary


-- | Run the probabilistic value to get a sample
sample :: RandomGen g => g -> PL a -> (a, g)
sample g (Ret a) = (a, g)
sample g (Sample01 f2plnext) = let (f, g') = random g in sample g' (f2plnext f)


-- | Sample n values from the distribution
samples :: RandomGen g => Int -> g -> PL a -> ([a], g)
samples 0 g _ = ([], g)
samples n g pl = let (a, g') = sample g pl
                     (as, g'') = samples (n - 1) g' pl
                 in (a:as, g'')

-- | count fraction of times value occurs in list
occurFrac :: (Eq a) => [a] -> a -> Float
occurFrac as a =
    let noccur = length (filter (==a) as)
        n = length as
    in (fromIntegral noccur) / (fromIntegral n)

-- | Produce a distribution from a PL by using the sampler to sample N times
distribution :: (Eq a, Num a, RandomGen g) => Int -> g -> PL a -> (D a, g)
distribution n g pl =
    let (as, g') = samples n g pl in (D (\a -> P (occurFrac as a)), g')


-- | biased coin
coin :: Float -> PL Int -- 1 with prob. p1, 0 with prob. (1 - p1)
coin p1 = do
    Sample01 (\f -> Ret $ if f < p1 then 1 else 0)


-- | Create a histogram from values.
histogram :: Int -- ^ number of buckets
          -> [Float] -- values
          -> [Int]
histogram nbuckets as =
    let
        minv :: Float
        minv = minimum as
        maxv :: Float
        maxv = maximum as
        -- value per bucket
        perbucket :: Float
        perbucket = (maxv - minv) / (fromIntegral nbuckets)
        bucket :: Float -> Int
        bucket v = floor (v / perbucket)
        bucketed :: M.Map Int Int
        bucketed = foldl (\m v -> M.insertWith (+) (bucket v) 1 m) mempty as
     in map snd . M.toList $ bucketed


printSamples :: (Real a, Eq a, Ord a, Show a) => String -> [a] -> IO ()
printSamples s as =  do
    putStrLn $ "***" <> s
    putStrLn $ "   samples: " <> series2spark (map toRational as)

printHistogram :: [Float] -> IO ()
printHistogram samples = putStrLn $ series2spark (map fromIntegral . histogram 10 $  samples)


-- | Given a coin bias, take samples and print bias
printCoin :: Float -> IO ()
printCoin bias = do
    let g = mkStdGen 1
    let (tosses, _) = samples 100 g (coin bias)
    printSamples ("bias: " <> show bias) tosses



-- | Create normal distribution as sum of uniform distributions.
normal :: PL Float
normal =  fromIntegral . sum <$> (replicateM 5 (coin 0.5))


main :: IO ()
main = do
    printCoin 0.01
    printCoin 0.99
    printCoin 0.5
    printCoin 0.7

    putStrLn $ "normal distribution using central limit theorem: "
    let g = mkStdGen 1
    let (nsamples, _) = samples 1000 g normal
    -- printSamples "normal: " nsamples
    printHistogram nsamples


    putStrLn $ "normal distribution using MCMC: "
    let (mcmcsamples, _) = samples 1000 g (mhD $  normalD 0.5)
    printHistogram mcmcsamples

    putStrLn $ "sampling from x^4 with finite support"
    let (mcmcsamples, _) = samples 1000 g (mhD $  polyD 4)
    printHistogram mcmcsamples
```

### Output

```
***bias: 1.0e-2
   samples: ________________________________________█_█_________________________________________________________
***bias: 0.99
   samples: ████████████████████████████████████████████████████████████████████████████████████████████████████
***bias: 0.5
   samples: __█____█__███_███_█__█_█___█_█_██___████████__█_████_████_████____██_█_██_____█__██__██_██____█__█__
***bias: 0.7
   samples: __█__█_█__███_█████__███_█_█_█_██_█_████████__███████████_████_█_███_████_██__█_███__██_███_█_█__█_█
normal distribution using central limit theorem: 
_▄▇█▄_
normal distribution using MCMC: 
__▁▄█▅▂▁___
sampling from x^4 with finite support
▁▁▃▃▃▄▅▆▇█_

```
# The smallest implementation of reverse mode AD (autograd) ever:

```hs
{-# LANGUAGE GeneralizedNewtypeDeriving #-}
import qualified Data.Map.Strict as M

-- | This file can be copy-pasted and will run!

-- | Symbols
type Sym = String
-- | Environments
type E a = M.Map Sym a
-- | Newtype to represent deriative values
type F = Float
newtype Der = Der { under :: F } deriving(Show, Num)

infixl 7 !#
-- | We are indexing the map at a "hash" (Sym)
(!#) :: E a -> Sym -> a
(!#) = (M.!)

-- | A node in the computation graph
data Node = 
  Node { name :: Sym -- ^ Name of the node
       , ins :: [Node] -- ^ inputs to the node
       , out :: E F -> F -- ^ output of the node
       , der :: (E F, E (Sym -> Der)) 
                  -> Sym -> Der -- ^ derivative wrt to a name
       }

-- | @ looks like a "circle", which is a node. So we are indexing the map
-- at a node.
(!@) :: E a -> Node -> a 
(!@) e node = e M.! (name node)

-- | Given the current environments of values and derivatives, compute
-- | The new value and derivative for a node.
run_ :: (E F, E (Sym -> Der)) -> Node -> (E F, E (Sym -> Der))
run_ ein (Node name ins out der) = 
  let (e', ed') = foldl run_ ein ins -- run all the inputs
      v = out e' -- compute the output
      dv = der (e', ed') -- and the derivative
  in (M.insert name v e', M.insert name dv ed')  -- and insert them

-- | Run the program given a node 
run :: E F -> Node -> (E F, E (Sym -> Der))
run e n = run_ (e, mempty) n

-- | Let's build nodes
nconst :: Sym -> F -> Node
nconst n f = Node n [] (\_ -> f) (\_ _ -> 0)

-- | Variable
nvar :: Sym -> Node 
nvar n = Node n [] (!# n) (\_ n' -> if n == n' then 1 else 0)
  
-- | binary operation
nbinop :: (F -> F -> F)  -- ^ output computation from inputs
 -> (F -> Der -> F -> Der -> Der) -- ^ derivative computation from outputs
 -> Sym -- ^ Name
 -> (Node, Node) -- ^ input nodes
 -> Node
nbinop f df n (in1, in2) = 
  Node { name = n
       , ins = [in1, in2]
       , out = \e -> f (e !# name in1) (e !# name in2)
       , der = \(e, ed) n' -> 
                 let (name1, name2) = (name in1, name in2)
                     (v1, v2) = (e !# name1, e !# name2)
                     (dv1, dv2) = (ed !# name1 $ n', ed !# name2 $ n')
                     in df v1 dv1 v2 dv2
       }

nadd :: Sym -> (Node, Node) -> Node
nadd = nbinop (+) (\v dv v' dv' -> dv + dv')

nmul :: Sym -> (Node, Node) -> Node
nmul = nbinop (*) (\v (Der dv) v' (Der dv') -> Der $ (v*dv') + (v'*dv))

main :: IO ()
main = do
  let x = nvar "x" :: Node
  let y = nvar "y"
  let xsq = nmul "xsq" (x, x)
  let ten = nconst "10" 10
  let xsq_plus_10 = nadd "xsq_plus_10" (xsq, ten)
  let xsq_plus_10_plus_y = nadd "xsq_plus_10_plus_y"  (xsq_plus_10, y)
  let (e, de) = run (M.fromList $ [("x", 2.0), ("y", 3.0)]) xsq_plus_10_plus_y
  putStrLn $ show e
  putStrLn $ show $ de !@ xsq_plus_10_plus_y $ "x"
  putStrLn $ show $ de !@ xsq_plus_10_plus_y $ "y"
```

Yeah, in ~80 lines of code, you can basically build an autograd engine. Isn't
haskell so rad?


# Timings of passes in GHC, and low hanging fruit in the backend:

- One can use `-v3` to get pass timings.
- Apparently, GHC spends a lot of time in the simplifier, and time
  spend in the backend is peanuts in comparison to this.
- To quote `AndreasK`:
> - Register allocation, common block elimination, block layout and pretty printing are the "slow" things in the backend as far as I remember.
> - There are also a handful of TODO's in the x86 codegen which still apply. So you can try to grep for these.
> - Strength reduction for division by a constant
- [NCG generates slow loop code](https://gitlab.haskell.org/ghc/ghc/issues/9041)
# Varargs in GHC: `ghc/testsuite/tests/rts/T7160.hs`

A comment from this test case tells us why the function `debugBelch2` exists:

```hs
ghc/testsuite/tests/rts/T7160.hs
-- Don't use debugBelch() directly, because we cannot call varargs functions
-- using the FFI (doing so produces a segfault on 64-bit Linux, for example).
-- See Debug.Trace.traceIO, which also uses debugBelch2.
foreign import ccall "&debugBelch2" fun :: FunPtr (Ptr () -> Ptr () -> IO ())
```

The implementation is:

```c
ghc/libraries/base/cbits/PrelIOUtils.c

void debugBelch2(const char*s, char *t)
{
    debugBelch(s,t);
}
```

```
ghc/rts/RtsMessages.c

RtsMsgFunction *debugMsgFn  = rtsDebugMsgFn;
...

void
debugBelch(const char*s, ...)
{
  va_list ap;
  va_start(ap,s);
  (*debugMsgFn)(s,ap);
  va_end(ap);
}
```
# [Debugging debug info in GHC](#debugging-debug-info-in-GHC)


I wanted to use debug info to help build a better debugging experience
within [`tweag/asterius`](http://github.com/tweag/asterius). So, I was 
reading through the sources of `cmm/Debug.hs`.  
I'd never considered how to debug debug-info, and I found the information
tucked inside a cute note in GHC (`Note [Debugging DWARF unwinding info]`):

> This makes GDB produce a trace of its internal workings. Having gone this far,
> it's just a tiny step to run GDB in GDB. Make sure you install debugging
> symbols for gdb if you obtain it through a package manager.

- [Link to GHC sources](https://github.com/ghc/ghc/blob/535a26c90f458801aeb1e941a3f541200d171e8f/compiler/cmm/Debug.hs#L458)


# [GHC LLVM code generator: Switch to unreachable](#ghc-llvm-code-generator-switch-to-unreachable)

The [switch to out of range](https://github.com/ghc/ghc/blob/master/compiler/llvmGen/LlvmCodeGen/CodeGen.hs#L1102) 
code generator switches to the first label. It should be more profitable
to switch to a `unreachable` block. That way, LLVM can take advantage of UB.

# [Concurrency in Haskell](#concurrency-in-haskell)

Great link to the GHC wiki that describes the concurrency primitives
"bottom up": https://gitlab.haskell.org/ghc/ghc/wikis/lightweight-concurrency

# [Handy list of differential geometry definitions](#handy-list-of-differential-geometry-definitions)

There are way too many objects in diffgeo, all of them subtly connected.
Here I catalogue all of the ones I have run across:

##### Manifold

A manifold $M$ of dimension $n$ is a topological space. So, there is a
topological structure $T$ on $M$. There is also an _Atlas_, which is a family
of _Chart_s that satisfy some properties.

##### Chart

A chart is a pair $(O \in  T , cm: O -> \mathbb R^n$. The $O$ is an open set of the
manifold, and $cm$ ("chart for "m") is a continuous mapping from $O$ to $\mathbb R^n$
under the subspace topology for $U$ and the standard topology for $\mathbb R^n$.

#####  Atlas

An _Atlas_ is a collection of _Chart_s such that the charts cover the manifold,
and the charts are pairwise compatible. That is, $A = \{ (U_i, \phi_i) \}$, such
that $\cup{i} U_i = M$, and $\phi_j \circ phi_i^{-1}$ is smooth.

##### Differentiable map

$f: M \to N$ be a mapping from an $m$ dimensional manifold to an $n$ dimensional
manifold. Let $frep = cn \circ f \circ cm^{-1}: \mathbb R^m -> \mathbb R^n$ 
where $cm: M \to \mathbb R^m$ is a chart for $M$, $cn: N \to \mathbb R^n$ 
is a chart for $N$. $frep$ is $f$ represented
in local coordinates. If $frep$ is smooth for all choices of $cm, cn$,
then $f$ is a differentiable map from $M$ to $N$.

##### Curve: 

Let $I$ be an open interval of $\mathbb R$ which includes the point `0`.  A Curve is a
differentiable map $C: (a, b) \to M$ where $a < 0 < b$.

##### Function: (I hate this term, I prefer something like Valuation): 

A differentiable mapping from $M$ to $R$.


##### Directional derivative of a function `f(m): M -> R` with respect to a curve `c(t): I -> M`, denoted as `c[f]`.

Let `g(t) = (f . c)(t) :: I -c-> M -f-> R = I -> R`.
This this is the value `dg/dt(t0) = (d (f . c) / dt) (0)`.

##### Tangent vector at a point `p`:

On a `m` dimensional manifold `M`, a tangent vector at a point `p` is an
equivalence class of curves that have `c(0) = p`, such that `c1(t) ~ c2(t)` iff
:

2. For a (all) charts `(O, ch)` such that `c1(0) ∈  O`,
 `d/dt (ch . c1: R -> R^m) = d/dt (ch . c2: R -> R^m)`.

 That is, they have equal derivatives.

##### Tangent space(`TpM`):

The set of all tangent vectors at a point `p` forms a vector space `TpM`.
We prove this by creating a bijection from every curve to a vector `R^n`.

Let `(U, ch: U -> R)` be a chart around the point `p`, where `p ∈ U ⊆ M`. Now,
the bijection is defined as:

```
forward: (I -> M) -> R^n
forward(c) = d/dt (c . ch)

reverse: R^n -> (I -> M)
reverse(v)(t) = ch^-1 (tv)
```

##### Cotangent space(`TpM*`): dual space of the tangent space / Space of all linear functions from `TpM` to `R`.

- Associated to every function `f`, there is a cotangent vector, colorfully
  called `df`. The definition is `df: TpM -> R`, `df(c: I -> M) = c[f]`. That is,
  given a curve `c`, we take the directional derivative of the function `f`
  along the curve `c`. We need to prove that this is constant for all vectors
  in the equivalence class and blah.

######  Pushforward `push(f): TpM -> TpN`

Given a curve `c: I -> M`, the pushforward
is the curve `f . c : I -> N`. This extends to the equivalence classes
and provides us a way to move curves in `M` to curves in `N`, and thus
gives us a mapping from the tangent spaces.

This satisfies the identity:

```
push(f)(v)[g] === v[g . f]
```

##### Pullback `pull(f): TpN* -> TpM*`

Given a linear functional `wn : TpN -> R`, the pullback is defined as
` wn . push(f) : TpM -> R`.


This satisfies the identity:

```
(pull wn)(v) === wn (push v)
(pull (wn : TpN->R): TpM->R) (v : TpM) : R  = (wn: TpN->R) (push (v: TpM): TpN) : R
```

##### Vector field as derivation

TODO

##### Lie derivation

##### Lie derivation as lie bracket


# [Lazy programs have space leaks, Strict programs have time leaks](#lazy-programs-have-space-leaks-strict-programs-have-time-leaks)

Stumbled across this idea while reading some posts on a private discourse.
- Continually adding new thunks without forcing them can lead to a space leak,
  aka the dreaded monadic parsing backtracking problem.

- Continually _running_ new thunks can lead to a "time leak", where we spend
  far too much time running things that should not be run in the first place!

This is an interesting perspective that I've never seen articulated before, and
somehow helps make space leaks feel more... palatable? Before, I had no
analogue to a space leak in the strict world, so I saw them as a pathology. But
with this new perspective, I can see that the strict world's version of a space
leak is a time leak.

# [Presburger arithmetic can represent the Collatz Conjecture](#presburger-arithmetic-can-represent-the-collatz-conjecture)

An observation I had: the function

```
f(x) = x/2      if (x % 2 == 0)
f(x) = 3x + 1   otherwise
```

is a Presburger function, so by building better approximations to the
transitive closure of a presburger function, one could get better answers
to the Collatz conjecture. Unfortunately, ISL (the integer set library) of today
is not great against the formidable foe.

The code:

```cpp
#include <isl/set.h>
#include <isl/version.h>
#include <isl/map.h>
#include <isl/aff.h>
#include <isl/local_space.h>
#include <isl/constraint.h>
#include <isl/space.h>

int main() {
    isl_ctx *ctx = isl_ctx_alloc();
    const char *s = "{ [x] -> [x / 2] : x % 2 = 0; [x] -> [3 * x + 1] : x % 2 = 1}";

    isl_map *m = isl_map_read_from_str(ctx, s);

    isl_map_dump(m);

    isl_bool b;
    isl_map *p = isl_map_transitive_closure(m, &b);
    printf("exact: %d\n", b);
    printf("map:\n");
    isl_map_dump(p);

}
```

Produces the somewhat disappointing, and yet expected output:

```
$ clang bug.c -lisl -Lisl-0.20/.libs -o bug -I/usr/local/include/
$ ./bug
{ [x] -> [o0] : 2o0 = x or (exists (e0 = floor((1 + x)/2): o0 = 1 + 3x and 2e0 = 1 + x)) }
exact: 0
map:
{ [x] -> [o0] }
```

I find it odd that it is unable to prove _anything_ about the image, even that
it is non-negative, for example. This is an interesting direction in which
to improve the functions `isl_map_power` and `isl_map_transitive_closure`
though.


# [Using compactness to argue about covers](#using-compactness-to-argue-about-covers)

I've always seen compactness be used by _starting_ with a possibly infinite
coverm and then _filtering it_ into a finite subcover. This finite
subcover is then used for finiteness properties (like summing, min, max, etc.).

I recently ran across a use of compactness when one _starts_ with the set
of _all possible subcovers_, and then argues about why a cover cannot be built
from these subcovers if the set is compact. I found it to be a very cool
use of compactness, which I'll record below:

#### Theorem: 

If a family of compact, countably infinite sets `S_a` have all 
_finite intersections_ non-empty, then the intersection of the family `S_a`
is non-empty.

#### Proof:

Let `S = intersection of S_a`. We know that `S` must be compact since
all the `S_a` are compact, and the intersection of a countably infinite
number of compact sets is compact.

Now, let `S` be empty. Therefore, this means there must be a point `p ∈ P`
such that `p !∈ S_i` for some arbitrary `i`.


#### Cool use of theorem:

We can see that the cantor set is non-empty, since it contains a family
of closed and bounded sets `S1, S2, S3, ...` such that  `S1 ⊇ S2 ⊇ S3 ...`
where each `S_i` is one step of the cantor-ification. We can now see
that the cantor set is non-empty, since:

1. Each finite intersection is non-empty, and will be equal to the set that
   has the highest index in the finite intersection.

2. Each of the sets `Si` are compact since they are closed and bounded subsets of `R`

3. Invoke theorem.


# [Japanese Financial Counting system](#japanese-financial-counting-system)

- [Wikipedia](https://en.wikipedia.org/wiki/Japanese_numerals#Formal_numbers)

Japanese contains a separate kanji set called `daiji`, to prevent people
from adding strokes to stuff previously written.

```
#  |Common |Formal
1  |一     |壱
2  |二     |弐
3  |三     |参
```


# [Stephen wolfram's live stream](#stephen-wolframs-live-stream)

- [Twitch.tv link](https://www.twitch.tv/videos/408653972)


I've taken to watching the live stream when I have some downtime and want
some interesting content. 

The discussions of Wolfram with his group are great, and they bring up
_really_ interesting ideas (like that of cleave being very irregular).

# [`Cleave` as a word has some of the most irregular inflections](#cleave-as-a-word-has-some-of-the-most-irregular-inflections)
- cleave
- clove
- cleaved
- clave
- cleft

# [McCune's single axiom for group theory](#mccunes-single-axiom-for-group-theory)

[Single Axioms for Groups and Abelian Groups with Various
Operations](http://ftp.mcs.anl.gov/pub/tech_reports/reports/P270.pdf)
provides a single axiom for groups. This can be useful for some ideas I have
for training groups, where we can use this axiom as the loss function!

# `Word2Vec` C code implements gradient descent really weirdly
I'll be posting snippets of the original source code, along with a 
link to the Github sources. We are interested in exploring the skip-gram
implementation of Word2Vec, with negative sampling, without hierarchical
softmax. I assume basic familiarity with word embeddings and the skip-gram
model.

#### Construction of the sigmoid lookup table

```cpp
// https://github.com/tmikolov/word2vec/blob/master/word2vec.c#L708

expTable = (real *)malloc((EXP_TABLE_SIZE + 1) * sizeof(real));
for (i = 0; i < EXP_TABLE_SIZE; i++) {
  expTable[i] = exp((i / (real)EXP_TABLE_SIZE * 2 - 1) *
                    MAX_EXP);  // Precompute the exp() table
  expTable[i] =
      expTable[i] / (expTable[i] + 1);  // Precompute f(x) = x / (x + 1)
}
```
Here, the code constructs a lookup table which maps `[0...EXP_TABLE_SIZE-1]`
to `[sigmoid(-MAX_EXP)...sigmoid(MAX_EXP)]`. The index `i` first gets mapped
to `(i / EXP_TABLE_SIZE) * 2 - 1`, which sends `0` to `-1` and `EXP_TABLE_SIZE`
to `1`. This is then rescaled by `MAX_EXP`.

#### Layer initialization

- `syn0` is a global variable, initialized with random weights in the range of
`[-0.5...0.5]`. It has dimensions `VOCAB x HIDDEN`.  This layer holds the
hidden representations of word vectors.

```cpp
// https://github.com/imsky/word2vec/blob/master/word2vec.c#L341
a = posix_memalign((void **)&syn0, 128,
               (long long)vocab_size * layer1_size * sizeof(real));
...

// https://github.com/imsky/word2vec/blob/master/word2vec.c#L355
for (a = 0; a < vocab_size; a++)
        for (b = 0; b < layer1_size; b++) {
            next_random = next_random * (unsigned long long)25214903917 + 11;
            syn0[a * layer1_size + b] =
                (((next_random & 0xFFFF) / (real)65536) - 0.5) / layer1_size;
        }
```


- `syn1neg` is a global variable that is zero-initialized. It has dimensions
`VOCAB x HIDDEN`. This layer also holds hidden representations of word vectors,
_when they are used as a negative sample_.

```cpp
// https://github.com/imsky/word2vec/blob/master/word2vec.c#L350
a = posix_memalign((void **)&syn1neg, 128,
                   (long long)vocab_size * layer1_size * sizeof(real));
...
for (a = 0; a < vocab_size; a++)
    for (b = 0; b < layer1_size; b++) syn1neg[a * layer1_size + b] = 0;
```

- `neu1e` is a temporary per-thread buffer (Remember that the `word2vec` C code
use CPU threads for parallelism) which is zero initialized. It has dimensions
`1 x HIDDEN`.

```cpp
// https://github.com/imsky/word2vec/blob/master/word2vec.c#L370
real *neu1e = (real *)calloc(layer1_size, sizeof(real));
```

#### Backpropogation

Throughout `word2vec`, no 2D arrays are used. Indexing of the form
`arr[word][ix]` is manually written as `arr[word * layer1_size + ix]`. So, I
will call `word * layer1_size` as the "base address", and `ix` as the "offset
of the array index expression henceforth.

Here, `l1` is the base address of the word at the center of window (the focus
word).  `l2` is the base address of either the word that is negative sampled
from the corpus, or the word that is a positive sample from within the context
window.

`label` tells us whether the sample is a positive or a negative sample. 
`label = 1` for positive samples, and `label = 0` for negative samples.

```cpp
// zero initialize neu1e
// https://github.com/imsky/word2vec/blob/master/word2vec.c#L419
for (c = 0; c < layer1_size; c++) neu1e[c] = 0;
...
// loop through each negative sample
// https://github.com/imsky/word2vec/blob/master/word2vec.c#L508
if (negative > 0)  for (d = 0; d < negative + 1; d++) {
  ...
  // https://github.com/imsky/word2vec/blob/master/word2vec.c#L521
  // take the dot product: f=  syn0[focus] . syn1neg[context]
  for (c = 0; c < layer1_size; c++) f += syn0[c + l1] * syn1neg[c + l2];
  
  // compute: g = (label - sigmoid(2f - 1)) * alpha
  // g is computed using lookups into a lookup table and clamping for
  // efficiency.
  if (f > MAX_EXP) g = (label - 1) * alpha;
  else if (f < -MAX_EXP) g = (label - 0) * alpha;
  else
  g = (label - expTable[(int)((f + MAX_EXP) *
                              (EXP_TABLE_SIZE /
                               MAX_EXP / 2))]) * alpha;
  // Now that we have computed the gradient:
  // `g = (label - output) * learningrate`,
  // we need to perform backprop. This is where the code gets weird.

  for (c = 0; c < layer1_size; c++) neu1e[c] += g * syn1neg[c + l2];
  for (c = 0; c < layer1_size; c++) syn1neg[c + l2] += g * syn0[c + l1];
  } // end loop through negative samples
// Learn weights input -> hidden
for (c = 0; c < layer1_size; c++) syn0[c + l1] += neu1e[c];
```

- We have _two_ vectors for each word, one called `syn0[l1 + _]` and 
the other `syn1neg[l2 + _]`. The `syn1neg` word embedding is used whenever
a word is used a negative sample, and is not used anywhere else. Also,
the `syn1neg` vector is zero initialized, while the `syn0` vectors are
randomly initialized.

- The values we backprop with `g * syn1neg[l2 + _]`, `g * syn0[l1 + _]` are
  _not_ the correct gradients of the error term! The derivative of a sigmoid
  is `dsigmoid(x)/dx = sigmoid(x) [1 - sigmoid(x)]`. The `[1 - sigmoid(x)]`
  is nowhere to be seen, let alone the fact that we are using 
  `sigmoid(2x - 1)` and not regular sigmoid. Very weird.

- We hold the value of `syn0` constant throughout all the negative samples,
which was not mentioned in any tutorial I've read.

The paper does not mentioned these implementation details, and neither
does _any blog post that I've read_. I don't understand what's going on,
and I plan on updating this section when I understand this better.


# [Arthur Whitney: dense code](#arthur-whitney-dense-code)


- Guy who wrote a bunch of APL dialects, write code in an eclectic style
  that has very little whitespace and single letter variable names.
- Believes that this allows him to hold the entire program in his head.
- Seems legit from my limited experience with APL, haskell one-liners.
- [The b programming language](http://kparc.com/b/readme.txt). It's quite 
  awesome to read the sources. For example, [`a.c`](http://kparc.com/b/a.c)

- [A history of APL in 50 functions](https://www.jsoftware.com/papers/50/) ---
  A great list of APL snippets that solve classical problems.

# [How does one work with arrays in a linear language?](#how-does-one-work-with-arrays-in-a-linear-language)

Given an array of qubits `xs: Qubit[]`, I want to switch to little endian.
Due to no-cloning, I can't copy them! I suppose I can use recursion to build
up a new "list". But this is not the efficient array version we know and love
and want. 

The code that I want to work but does not:
```csharp
function switchEndian(xs: Qubit[]): Unit {
    for(i in 0..Length(xs) - 1) {
        Qubit q = xs[i]; // boom, this does not work!
        xs[i] = xs[Length(xs) - 1 - i]
        xs[Length(xs) - 1 - i] = q;
    }
}
```

On the other hand, what _does work_ is to setup a quantum circuit that
performs this flipping, since it's a permutation matrix at the end of
the day. But this is very slow, since it needs to simulate the "quantumness"
of the solution, since it takes `2^n` basis vectors for `n` qubits. 

However, the usual recursion based solution works:
```csharp
function switchEndian(xs: Qubit[]): Qubit[] {
    if(Length(xs) == 1) {
        return xs;
    } else {
        switchEndian(xs[1..(Length(xs) - 1)] + xs[0]
    }
}
```

This is of course, suboptimal.

I find it interesting that in the linear types world, often the "pure" solution
is _forced_ since mutation very often involves temporaries / copying!

(I'm solving assignments in [qsharp](https://docs.microsoft.com/en-us/quantum/)
for my course in college)

# [Linear optimisation is the same as linear feasibility checking](#linear-optimisation-is-the-same-as-linear-feasibility-checking)
Core building block of effectively using the ellipsoid algorithm.

- If we posess a way to check if a point $p \in P$ where $P$ is a polytope, we
  can use this to solve optimisation problems.
- Given the optimisation problem maximise $c^Tx$ subject to $Ax = b$, we can
  construct a new _non-emptiness_ problem. This allows us to convert optimisation
  into _feasibility_.
- The new problem is $Ax = b, A^Ty = c, c^Tx = b^T y$. Note that by duality,
  a point in this new polyhedra will _be an optimal solution to the above linear program_.
  We are forcing $c^Tx = b^Ty$, which will be the optimal solution, since the
  solution where the primal and dual agree is the optimal solution by strong
  duality.
- This way, we have converted a _linear programming_ problem into a 
  _check if this polytope is empty_ problem!

# [Quantum computation without complex numbers](#quantum-computation-without-complex-numbers)

I recently learnt that the Toeffili and Hadamard gates are universal for
quantum computation. The description of these gates involve no complex numbers.
So, we can write any quantum circuit in a "complex number free" form. The caveat
is that we may very well have _input qubits_ that require complex numbers.


Even so, a large number (all?) of the basic algorithms shown in Nielsen and
Chaung can be encoded in an entirely complex-number free fashion.

I don't really understand the ramifications of this, since I had the intuition
that the power of quantum computation comes from the ability to express
complex phases along with superposition (tensoring). However, I now have
to remove the power from going from R to C in many cases. This is definitely
something to ponder.

- [Dorit Aharonov: A Simple Proof that Toffoli and Hadamard are Quantum Universal](https://arxiv.org/pdf/quant-ph/0301040)


# [Linguistic fun fact: Comparative Illusion](#linguistic-fun-fact-comparative-illusion)

I steal from wikipedia:

> Comparative Illusion, which is a grammatical illusion where certain
> sentences seem grammatically correct when you read them, but upon further
> reflection actually make no sense. 

For example: "More people have been to Berlin than I have."

# Long-form posts:
## Reading
- [2018 reading](content/blog/stuff-i-learnt-this-year-2018.md)
- [2017 reading](content/blog/papers-I-read-and-loved-in-2017.md)

## Haskell
- [Reading the `structs` library](content/blog/reading-kmett-structs.md)
- [Reading the `machines` library (WIP)](content/blog/machines/reading-kmett-machines.md)
- [Explaining laziness (WIP)](content/blog/laziness-for-c-programmers.md)
- [Explaining STG(WIP)](stg-explained.md)

## Simplexhc (STG -> LLVM compiler) progress
- [proc points suck / making GHC an order of magnitude faster](content/blog/ghc-micro-optimisations-or-why-proc-points-suck.md)
- [dec 2017](this-month-in-simplexhc-dec-2017.md)
- [oct 29 2017](this-week-in-simpexhc-oct-29-2017.md)
- [july 2017](this-week-in-simplexhc-07-2017.md)
- [july 6th 2017](this-week-in-simplexhc-2017-07-06.md)
- [announcement](content/blog/announcing-simplexhc.md)

## GSoC (2015)
- [proposal](content/blog/gsoc-vispy.md)
- [week 1](content/blog/gsoc-vispy-week-1-and-2.md)
- [week 3 and 4](content/blog/gsoc-vispy-week-3-and-4.md)
- [week 5](content/blog/gsoc-vispy-week-5.md)
- [week 6](content/blog/gsoc-vispy-week-6.md)
- [week 7](content/blog/gsoc-vispy-week-7.md)
- [final report](content/blog/gsoc-vispy-report-6.md)

# [Distributed Systems](#distributed-systems)

## Match 10th
### 5 minute talk: P2P
#### Napster
Napster connected to a central server than was an index of all users. Users are
connected to each other to download MP3 files off of each other.

#### BitTorrent

Each data segment is encrypted. Data segment is downloaded individually by
peers. 

#### Chord protocol

Finger table: nodes are keys, contain values. A node's chord table is:
with ids `i :-> (n + 2^i)`.

#### Ho Ramamoorthy:

Each site maintains a local wait-for graph. Central site begins a check.
All of the data is pushed to central node which begins the check.

### All Pairs Shortest Path Algorthms

- Content from distributed algorithms by gerard tel: Chapter 4

When a packet is sent in a network, it should be forwarded using routing tables.
The routing table must be computed when the network is initialized, and must
be updated every time the topology of the network changes.

We assume that the network is undirected, and we have no negative weight
cycles.  Our weights are typically congestion.

- *Correctness*: Algorithm must deliver every packet to its ultimate destination.
- *Robustness*: If the topology changes, the algorithm should update its
  routing table accordingly.

#### Floyd Warshall for routing table:

Perform matrix multiplication on the `(min, +)` semiring.

```py
def floyd_warshall(V, E):
    UnseenV = set(V)

    W = np.fill("infty", shape=[len(V), len(V)]) -- distances
    B = [[None for _ in len(V)] for _ in len(V)] -- intermediate paths.
    for (u, weight, v) in E: W[u][v] = weight; B[u][v] = v;

    while UnseenV:
        w = UnseenV.randitem(); UnseenV.delete(w);
        if W[a][w] + W[w][b] < W[a][b]:
            B[a][b] = B[a][w] -- if a m
            W[a][b] = W[a][w] + W[w][b]
```

#### The simple distributed Floyd Warshall Algorithm:

```py
# nth processor  is running the code floyd_warshall(n, V, E)
def floyd_warshall(n, V, E):
    UnseenV = set(V)

    W = np.fill("infty", shape=[len(V), len(V)]) -- distances
    B = [[None for _ in len(V)] for _ in len(V)] -- intermediate paths.
    for (u, weight, v) in E: W[u][v] = weight; B[u][v] = v;

    while UnseenV:
        # the ordering by which w's will be selected is _deterministic_,
        # and is _shared across all nodes_
        w = UnseenV.smallestitem(); UnseenV.delete(w);
        assert(w is the same across all nodes)

        if w == n: # if we are the current node
            broadcast(W[w, :]) # broadcast the weights of w
        else:
            W[w, :] = receive() # receive the updated weights of w

        if W[a][w] + W[w][b] < W[a][b]:
            B[a][b] = B[a][w] -- if a m
            W[a][b] = W[a][w] + W[w][b]
```

- If `NB[][w] = u`, then is `NB[u][w] = a`? 


#### The simple distributed Floyd Warshall Algorithm, Toueg's version

Here, we are trying to define how to broadcast the table `W[w, :]`. It is
now `W`'s turn to broadcast.

Define a graph $G_w \equiv (V_w, E_w)$.

- $u \in V_w \iff D[u][w] < \infty$: if a path from $u \xrightarrow{*} w$ exists.
- $(u, x) \in E_w \iff u \neq d \land B[u][w] = x$: If a path from $u \xrightarrow{*} w$ 
  must begin with x: $u \rightarrow x \xrightarrow{*} w$.

We claim that is $G_w$ is in fact a tree. This is because every edge $(u, x)$
in fact signals a path from $u \rightarrow x \xrightarrow{*} w$. Hence,

This graph is connected since we only add vertices that are at distance
less than infinity.

Hence, $G_w$ is a connected directed acyclic graph, so a tree.

## March 13th

#### Bellman Ford  (Single source shortest path algorithm)

- We have a root node $i_0$ whose shortest path we are trying to discover.
- Each vertex $k$ decides $d(k, i_0) = \min_{n \rightarrow k} d(k, n) + d(n, i_0)$.
- This is a dataflow algorithm!
- Once we actually know the single-source shortest paths, we can form a tree
  of shortest-path edges.
- At timestep $i$, all nodes at distance $i$ in the shortest path tree will
  indeed have learnt the shortest path.
- Since it's a tree, at most $|V| - 1$ non-trivial levels (level 0 is trivial).
  Hence, time complexity is $|V| - 1$.


#### Chandy-Misra Algorithm: Similar to Bellman Ford



#### Netchange algorithm for computing min-hop routing tables

Same as chandy-misra, but we allow edges to fail.
- We assume that nodes are notified failures and repairs of their
  adjacent channels.

- If we get a packet that is addressed to someone else, and our distance to
  that node is not infinity, then we send it to our first hop.

- If we get a packet that is addressed to someone else, and our distance to
  that node is infinity, discard.


- Let shortest path from $z \rightarrow w$ be through $u$ as $z \rightarrow u \rightarrow w$.
  Suppose chanell $uw$ fails. $u$ recomputes distance to $w$ as $d(w) = 1 + d(z, w) = 1 + 2 = 3$.
  Then it sets $nb(w) = z$. Is this incorrect? 

- __ANSWER:__ No, it's not incorrect. Now $z$ will be invalidated and it'll attempt
  to recompute its distance, causing its dinstance to go higher (say 5).
  This invalidates $u$, leading to an increasing sequence of distances $3 \rightarrow 5 \rightarrow 7 \dots$.
  If we have an uppoer bound on the distance (`DIAMETER`) then we know that
  this is wrong.

# Link dump

- [ADHD: A lifelong struggle: Why organisation systems don't work](https://gekk.info/articles/adhd.html)
- [Slides for intuition on converting number systems to data structures by Ralf Hinze](http://www.cs.nott.ac.uk/~pszgmh/bctcs-slides/hinze.pdf)
- [James mickens: hilarious articles --- this one on security](https://www.usenix.org/system/files/1401_08-12_mickens.pdf)
- [ADHD: A lifelong struggle | Why organisation systems don't work](https://gekk.info/articles/adhd.html)

