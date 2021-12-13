# Minimalt spenn tre
Defenisjon: [[Begreper/Minimalt Spenn Tre]]

## Algoritmer
Begge er grådige
### MST-Kruskal
Kjøretid: $O(E\lg V)$

![[MSTKruskal.PNG]]

Kruskal bruker metodene MAKE-SET, FIND-SET og UNION fra [[Skog | skog]] implementasjonen av [[Disjunkte set datastruktur | disjunkte set]].

### Prim's algorithm / MST-Prim
Kjøretid: $O(E\lg V)$

Kan forbedres til $O(E+V\lg V)$ med fibonacci heap.
$v.key = w(u, v)$ kjører en implisitt [[Heap | decrease key]] for å oppretholde min-haugen.

![[Prim.PNG]]

#Graf 
#Algoritme 
