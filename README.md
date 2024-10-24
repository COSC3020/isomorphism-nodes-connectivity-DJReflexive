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

A completely connected graph can be defined as a graph with all nodes having an edge leading to every other node in the graph. Any pair of nodes has an edge between them. 

Assume $A = (V_A,\ E_A)$ and $B = (V_B,\ E_B)$ and that\
$v_{a1},\ v_{a2} \in V_A$ and $v_{b1},\ v_{b2}, \in V_B$

Since these are pairs of nodes in their respective graphs, there is an edge between them. $(v_{a1},\ v_{a2})$ and $(v_{b1},\ v_{b2})$. 

Mapping $V_A$ to $V_B$ with $f: V_A \to V_B$:\
$(f(v_{a1}),\ f(v_{a2})) = (v_{b1},\ v_{b2})$

This shows a bijection and that the two graphs, A and B, are isomorphic. This process is true for all nodes and edges within the two graphs.


# Sources

- TA Ali: For reviewing my assignment and making sure things looked good - he suggested no changes for any of this.

# Plagiarism Acknowledgement

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.