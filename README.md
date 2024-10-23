# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

# My Proof

### Part 1: A and B having Equal Number of Nodes

Since it is stated graphs A and B have an equal number of nodes, this means that **it is possible** that A and B are isomorphic, but this does not directly prove it. Since they are the same size, it means there could be a bijection, but we must look at more details to confirm this.


### Part 2: Showing that a Bijection Exists

Assume $A = (V_A,\ E_A)$ and $B = (V_B,\ E_B)$ and that\
$(v_{a1},\ v_{a2},\ v_{a3},\ \dots,\ v_{an}) \in V_A$ and $(v_{b1},\ v_{b2},\ v_{b3},\ \dots,\ v_{bn}) \in V_B$

A completely connected graph can be defined as a graph with a nodes having an edge leading to every other node in the graph. Because of this, we can arbitrarily assign all elements in $V_A$ to $V_B$ (or $f: V_A \to V_B$) because all elements resemble each other and can be mapped successfully. This also preserves edge relationships since E is dependant on V in both graphs.

This shows a bijection and that the two graphs, A and B, are isomorphic.


# Sources

- TA Ali: For reviewing my assignment and making sure things looked good - he suggested no changes for any of this.

# Plagiarism Acknowledgement

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.