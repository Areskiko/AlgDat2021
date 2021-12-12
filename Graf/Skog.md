Er en [[Disjunkte set datastruktur | disjunkte set]] implementasjon, hvor hvert set er et [[Tre | tre]] rotet til representanten. Roten har seg selv som foreldrenode. 

En god implementasjon bruker union-by-rank heuristikk. Der ranken til hver [[Noder | node]] er en øvre grense på [[Nodehøyde |høyden]] til noden.

Med union by rank implementeres datatypen slik, der hver node $x$ har et felt $x.rank$ :

![[MakeSet.png]]

![[Union.PNG]]

![[Find set.PNG]]

Merk! Find set implementerer path-compression. Ettersom den setter alle foreldrenodene rekursivt til representanten. 

![[Path-compression.png]]