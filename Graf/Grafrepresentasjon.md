# Grafrepresentasjon
To hovedmåter å representere [[Graf | grafer]] på.
## Nabolister
Hver [[Noder | node]] har en liste over hvilke andre noder den har [[Kanter | kanter]] til. Kan være enten binært eller med vekter.

Egnet for spinkle grafer, og for traversering. Bruker mindre plass enn nabomatriser, gitt at den er spinkel.

## Nabomatriser
En binærmatrise $A$ der $a_{ij}$ angir om det går en kant fra $i$ til $j$. Kan også bruke en [[Vekt | vektmatrise]] $W$ der $w_{ij} < \infty$ hvis det går en kant fra $i$ til $j$. 

Egnet for tette grafer, og for rask lookup. Bruker mye plass, uansett om den har få kanter. Må alltid ha $n^2$ elementer.