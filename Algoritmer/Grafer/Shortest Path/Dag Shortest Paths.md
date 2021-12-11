# Dag Shortest Path

## Algoritme

Kjøretid: $\Theta$(V + E)

![[DagShortestPath.PNG]]


## Begrensninger
-	Kan ikke håndtere sykler
-	Grafen må være rettet

## Sammenheng med [[Dynamisk Programmering | dynamisk programmering]]
DAG shortest path bruker tabulering.
Siden kantene avhenger av korteste vei til den før, er det en fordel at den forrige er regnet ut på forhånd. Korteste vei til node n med foreldre k, og j vil være $min(k+vekt(k,n),j + vekt(j,n))$




#Graf 
#Algoritme/Graf

