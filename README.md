# Algebraic Geometry — Perugia 2026

Course material for the **Algebraic Geometry** course taught by Daniele Faenzi in Perugia in 2026.

## Announcements / communications

#### 22/07

Have you tried to prove that integral elements form a subring? One hint, if you know what that is, to the resultant.

#### 22/07

In the exercice about Nakayama's lemma, a hypothesis was missing! Check the notes for the correct statement (and the solution).

#### 24/07

There was a question about proving that $(xy)$ is a radical ideal of $k[x,y]$.

Can we apply the Chinese remainder theorem? The answer is no: this would require the ideals $(x)$ and $(y)$ to be comaximal, that is, $(x)+(y)=k[x,y].$
Equivalently, there would have to exist $f\in(x)$ and $g\in(y)$ such that $f+g=1,$ which is not possible.

We can instead use the fact that $k[x,y]$ is a unique factorisation domain. Let $f\in\sqrt{(xy)}.$ Then, for some integer $m\geq 1$, $f^m\in(xy),$ or equivalently, $xy\mid f^m.$

Write the factorisation of $f$ into irreducible elements as

$f=u p_1^{a_1}\cdots p_s^{a_s},$

where $u$ is a unit. Then $f^m=u^m p_1^{ma_1}\cdots p_s^{ma_s}.$

Since $x$ and $y$ are irreducible and not associated, the divisibility $xy\mid f^m$ and uniqueness of factorisation imply that there are (distinct) integers
$i,j$, with $1 \le i,j \le s$ such that $x = v p _{i}$ and $y = w p _{j}$, with $v,w \in A$ invertible. Therefore, $xy\mid f,$ so $f\in(xy)$. We have proved that $\sqrt{(xy)}\subseteq(xy).$

The reverse inclusion always holds, and hence $\sqrt{(xy)}=(xy).$

#### 26/07

There was a question about whether $\mathbf{V}(\mathfrak{a}) \subset k^n$ and $\mathbb{V}(\mathfrak{a}) \subset \mathbb{A} _{k}^n$ are the same. I erronously claimed that one example where they are different is for $n=1$ and $\mathfrak{a}=(x-a)$. Actually in this case both consist of a single point, it is not true that $(0)$ belongs to one of them. But a simpler example is: take $\mathfrak{a}=(0)$ in $\mathbb{C}[x]$. Then $\mathbb{V}(0)=\mathbb{A}^1 _{\mathbb{C}}$ contains all points of the form $(x-a)$ and $(0)$, while $\mathbf{V}(0)= \mathbb{C}$. The map sending $\mathbb{C}$ to $\mathbb{A}^1 _{\mathbb{C}}$ by $a \mapsto (x-a)$ hits all points except $(0)$.

## Assessment

The final grade will be based primarily on the written examination. Active participation during the exercise sessions—in particular, presenting solutions at the board and answering follow-up questions—may improve the final grade by up to one third of a grade. Participation is voluntary, and not participating will not lower the grade.

## Final exam

The final exam will last **1 hour 30 minutes**.

Definitions introduced during the course are part of the syllabus: students should be able to state them precisely and use them in examples and proofs.

The exam will contain one theoretical question, worth about **25% of the total mark**. It will be chosen from the following four topics.

1. **Hilbert’s Nullstellensatz.**
   Proof of the Nullstellensatz, including the Rabinowitsch trick. Zariski’s lemma may be used without proof.

2. **Morphisms to an affine scheme.**
   Construction of the bijection, in both directions

$\mathrm{Hom}_{\mathrm{(Sch)}}(X,\mathrm{Spec}(A)) \leftrightarrow$


3. **Gluing two schemes.**
   Construction of the underlying topological space and of the structure sheaf, using compatible pairs of sections. 

   The verification of the sheaf axioms and the general gluing lemma for an arbitrary family of schemes are not required.

4. **Reduction of a scheme.**
   Construction of $(X_{\mathrm{red}})$ and proof of its universal property with respect to morphisms from reduced schemes.

The remaining questions will consist of exercises based on the definitions, examples and techniques studied during the course.

## Office hours

Monday — 10:40 ~ 11:40

Wednesday 22/07 and 5/08 — 9:30 ~ 10:30

Wednesday 29/07 and 12/08 — 11:30 ~ 12:30

My office is number 607, at the 6th floor



## Lecture notes

- [Lecture notes (PDF)](lecture-notes.pdf)

## Exercise sheets

Here are the exercice sheets that we will use during the problem sessions.

You will find "plain" and "hinted" versions.

I suggest that you first try to read and solve some exercice and that, at a second stage, you look at the "hinted version" if you feel the need of some help. The idea is: read one hint, try to finish the exerice with that hint only, then read the next hint if you'd like to have more help, and so on.

I expect that you take quite some time to solve each exercice. Please, don't attempt at solving all of them; rather, try to have a very precise write-up of your favorite ones & have at least some understanding of most of them.

When you present some solution, please try to emphasize what you think is crucial, rather than presenting lengthy computations. Please try to keep your presentation within 5-8 minutes -- this timing is meant for the presenting your solution, not for elaborating / finding it :-)

- [All exercise sheets in one file (PDF)](exercise-sheets/all-weeks.pdf)
- Background exercices (modules over a ring etc)
  - [Background (PDF)](exercise-sheets/background.pdf)
  - [Background -- Hinted (PDF)](exercise-sheets/background-hints.pdf)
- Week 1
  - [Week 1 (PDF)](exercise-sheets/week1.pdf)
  - [Week 1 -- Hinted (PDF)](exercise-sheets/week1-hints.pdf)
- Week 2
  - [Week 2 (PDF)](exercise-sheets/week2.pdf)
  - [Week 2 -- Hinted (PDF)](exercise-sheets/week2-hints.pdf)
- Week 3
  - [Week 3 (PDF)](exercise-sheets/week3.pdf)
  - [Week 3 -- Hinted (PDF)](exercise-sheets/week3-hints.pdf)
- Week 4
  - [Week 4 (PDF)](exercise-sheets/week4.pdf)
  - [Week 4 -- Hinted (PDF)](exercise-sheets/week4-hints.pdf)

The files on this page may be updated during the course. Students can use the same links throughout.