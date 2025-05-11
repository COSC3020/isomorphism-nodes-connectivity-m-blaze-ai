# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


(Using the formal definition from above) 

Let \( A = (V_A, E_A) \) and \( B = (V_B, E_B) \) be two graphs such that:
- Both have the same number of nodes (n),  \( |V_A| = |V_B| \) and
- \( A \) and \( B \) are complete graphs (each distinct pair of nodes is connected by an edge)

To Prove: if two graphs are both complete and have the same number of nodes, then they are isomorphic.

Proof:
In a complete graph with \( n \) nodes, every pair of distinct nodes is connected by one edge.
So:
- \( E_A = \{ (u,v) \mid u, v \in V_A,\ u \ne v \} \)
- \( E_B = \{ (u,v) \mid x, y \in V_B,\ x \ne y \} \)
- Therefore,  \( |E_A| = |E_B| = \binom{n}{2} \)

Since \( |V_A| = |V_B| \), there exists a **bijection** \( f: V_A \rightarrow V_B \).

To show isomorphism, we must show that for every edge \( (u, v) \in E_A \), there exists a corresponding edge \( (f(u), f(v)) \in E_B \), and vice versa.
Since both \( A \) and \( B \) are complete graphs, each pair of distinct nodes is connected by an edge in both graphs.

So, for all \( u, v \in V_A \) with \( u \ne v \):
- \( (u,v) \in E_A \iff (f(u), f(v)) \in E_B \)
  
Thus, this satisfies the definition of isomorphism, making \( A \) and \( B \) isomorphic.


“I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.”

For this assignment, I asked Chat GPT for help in adjusting the formatting of my reasoning for better clarity and readability.

