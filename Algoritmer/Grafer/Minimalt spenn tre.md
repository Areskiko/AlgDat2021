# Minimalt spenn tre
Defenisjon: [[Begreper/Minimalt Spenn Tre]]

## Algoritmer
Begge er grådige
### MST-Kruskal
Kjøretid: $O(E\lg V)$

![[MSTKruskal.PNG]]

Kruskal bruker metodene MAKE-SET, FIND-SET og UNION fra [[Skog | skog]] implementasjonen av [[Disjunkte set datastruktur | disjunkte set]].

### Prim's algorithm
Kjøretid: $O(E\lg V)$

Kan forbedres til $O(E+V\lg V)$ med fibonacci heap

![[Prim.PNG]]

#Graf 
#Algoritme 
