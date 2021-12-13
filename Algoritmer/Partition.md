Partition:

Kjøretid: $\Theta(n)$

Partition tar inn et [[Array | array]] $A$ og sorterer det slik at $p = A[r]$ plasseres på indeks $i$. \
Der $\forall_{e \in A}((e \in [0..i - 1] \text{ if } e \le p) \ \land \ (e \in [i + 1..A.length] \text{ if } e > p )$. \
Til slutt returneres indeksen til $p$. 

![[Partition.PNG]]

Partition kan gardere seg mot ondsinnet input. Ved å stokke om på input med [[Randomized-partition | randomized partition.]]

#Algoritme 