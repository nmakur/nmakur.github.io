+++
title = "Did You Know?"
weight = 100
path = "fun_facts"
template = "page.html"

[extra]
in_menu = false
+++

A collection of facts that I think are cool, and links so that you can also think they're cool.

---

<color val="magenta">Garbage Collection</color>: The two main garbage collection schemes, tracing and reference counting, are <a href="https://web.eecs.umich.edu/~weimerw/2008-415/reading/bacon-garbage.pdf">algorithmic duals of each other</a>, and other garbage collection algorithms can be viewed as hybrids of the two.

---

<color val="magenta">Group Theory</color>: A group acting on a tree freely must be free. In particular, since the Cayley graph of a free group is a tree, subgroups of free groups are free. See, for instance, Chapter 3 of <a href="https://press.princeton.edu/books/paperback/9780691158662/office-hours-with-a-geometric-group-theorist?srsltid=AfmBOopiZYCCaRe6mrXLXKcrZBeYIZYPeOJdOteNsFFZDV7BrOPU3nWv">Office Hours with a Geometric Group Theorist</a> (the proof presented isn't correct, see <a href="https://margalit.droppages.net/OHGGT_Errata.pdf">the errata</a> (the proof in the errata also isn't quite correct but can easily be fixed with Zorn's lemma)).

---

<color val="magenta">Compilers</color>: Compilers can optimize code of the form
```
int sum = 0;
for (int i = 1; i <= n; i++) {
  sum += i;
}
```
into
```
sum = n * (n + 1) / 2
```
and <a href="https://kristerw.blogspot.com/2019/04/how-llvm-optimizes-geometric-sums.html?m=1">the solution doesn't involve hardcoding the pattern</a>.

---

<color val="magenta">Group Theory</color>: You can generalize Sylow's theorem when working with solvable groups: for any set &pi; of primes and finite *solvable* group *G*, we can find a subgroup *H &leq; G* such that the prime factors of *|H|* lie in &pi;, and no prime factor of *[G:H]* lies in &pi;. See section 8C of <a href="https://bookstore.ams.org/view?ProductCode=GSM/100">Algebra by Isaacs</a>.

---
<color val="magenta">Hardware</color>: <a href="https://williampan-personalwebsite.vercel.app/blog/systolic-array">How a systolic array efficiently multiplies matrices.</a>

---

<color val="magenta">Galois Theory</color>: The Galois correspondence breaks down when working with infinite field extensions, but can be salvaged by <a href="https://ctnt-summer.math.uconn.edu/wp-content/uploads/sites/1632/2020/06/CTNT-InfGaloisTheory.pdf">putting a topology on the Galois group and restricting to closed subsets</a>. Moreover, the Galois group (with this topology) is the inverse limit of the Galois groups of the *finite* subextensions with the discrete topology (while the field extension itself is the direct limit of the finite subextensions).
