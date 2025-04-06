# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Ill proove by counter example:

$G_1 = [
    [0,0,0],
    [0,1,0],
    [0,0,1]
]$

$G_2 = [
    [1,0,0],
    [0,0,0],
    [0,0,1]
]$

These graphs are isomorphic because
$V_1 \rightarrow V_2$:
$f(1) = 2$,
$f(2) = 1$,
$f(3) = 3$,
each node as a one-to-one mapping of Verticies from $G_1$ to Vertices from $G_2$ obiously this works in both directions ($G_2$ to $G_1$)

Then $(2,2) \in E_1$ and $f(2) = 1$ so $(1,1) \in E_2$,

also $(3,3) \in E_1$ and $f(3) = 3$ so $(3,3) \in E_2$. 

So $G_1$ and $G_2$ are isomorphic but they arnt connected because $v_1$ in $G_1$ and $v_2$ in $G_2$ dont have any connections at all.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.