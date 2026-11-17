# CMPS 2200 Recitation 09

## Answers

**Name:** Chuong Hoang Pham
_________________________


Place all written answers from `recitation-09.md` here for easier grading.



- **2) (2 pts)** What is the worst-case work of your algorithm, assuming $G$ has $k$ connected components?

    The worst-case of the algorithm is $O(|E|\log |V|)$

- **4) (2 pts)** What is the work of your full algorithm in the previous answer?

    With $n$ cities, the fully-connected graph has $|V| = n$ and $|E| = \binom{n}{2} = O(n^2)$ edges. Building the graph takes $O(n^2)$ work, and Prim's algorithm then takes $O(|E|\log |V|) = O(n^2 \log n)$ work. The total work is $O(n^2 \log n)$.
