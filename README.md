# Homework 13

## Groups

- 第二組
- 第三組
- 第八組
- 第九組
- 第十二組
- 第十三組
- 第十七組

## Problems

1. Exercises 34.1-5<br>
Show that if an algorithm makes at most a constant number of calls to polynomial-time subroutines and performs an additional amount of work that also takes polynomial time, then it runs in polynomial time. Also show that a polynomial number of calls to polynomial-time subroutines may result in an exponential-time algorithm.

2. Exercises 34.1-6<br>
Show that the class P, viewed as a set of languages, is closed under union, intersection, concatenation, complement, and Kleene star. That is, if L<sub>1</sub>, L<sub>2</sub> ∈ P, then L<sub>1</sub> ∪ L<sub>2</sub> ∈ P, L<sub>1</sub> ∩ L<sub>2</sub> ∈ P, L<sub>1</sub>L<sub>2</sub> ∈ P, L<sub>1</sub><sup>c</sup> ∈ P, and L<sub>1</sub><sup>\*</sup> ∈ P.


3. Exercises 34.2-3<br>
Show that if HAM-CYCLE ∈ P, then the problem of listing the vertices of a Hamiltonian cycle, in order, is polynomial-time solvable.<br>
(Note 1: HAM-CYCLE is defined as "Does a graph G have a Hamiltonian cycle?")<br>
(Note 2: "HAM-CYCLE ∈ P" means that HAM-CYCLE is polynomial-time solvable.)

4. Exercises 34.2-7<br>
Show that the Hamiltonian-path problem can be solved in polynomial time on directed acyclic graphs. Give an efficient algorithm for the problem.

5. Exercises 34.4-7<br>
Let 2-CNF-SAT be the set of satisfiable Boolean formula in CNF with exactly 2 literals per clause. Show that 2-CNF-SAT ∈ P. Make your algorithm as efficient as possible. (Hint: Observe that x ∨ y is equivalent to ¬x → y. Reduce 2-CNF-SAT to an efficiently solvable problem on a directed graph.)

6. Exercises 34.2-6<br>
A Hamiltonian path in a graph is a simple path that visits every vertex exactly once.
    1. Show that the language HAM-PATH = { (G, u, v): there is a Hamiltonian path from u to v in graph G } belongs to NP.
    2. Show that the Hamiltonian path problem is NP-complete. (Hint: Reduce from HAM-CYCLE.) 

7. Exercises 34.3-6<br>
A language L is **complete** for a language class C with respect to polynomial-time reductions if L ∈ C and L' ≤<sub>P</sub> L for all L' ∈ C. Show that ∅ and {0, 1}<sup>\*</sup> are the only languages in P that are not complete for P with respect to polynomial-time reductions.
