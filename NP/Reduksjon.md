### Reduksjon
Gitt problem A og problem B.

Hvis du reduserer A til B så betyr det at B er minst like vanskelig som A. 
->$A \leq B$

Kanskje lettere å tenke på denne ligningen
$A.difficulty \leq B.difficulty$

Når vi snakker om reduksjon så mener vi reduksjon i polynomisk tid. (Tror jeg)

#### Eksempel

Hvis du ønsker å vise at et problem X er (mest sannsynlig) umulig å løse i
polynomisk tid er det lurt å vise at X er [[NP-Hard|NP-hardt]].

For å vise at X er NP hardt så kan vi ta et kjent NP-hardt problem F.eks.
[[3SAT]]

Hvis vi klarer å redusere 3SAT til X i polynomisk tid. Da er X like vanskelig
eller vanskeligere enn 3SAT. Det impliserer at X er NP hardt.

Et annet eksempel på dette finner du i forklaringen hvorfor [[3SAT]] er [[NP-Hard|NP-hardt]].

Et annet eksempel på dette finner du i forklaringen hvorfor [[3SAT]] er [[NP-Hard|NP-hardt]].


#### Fun fact
Super Mario Bros er NP hardt da du kan lage en $n*n$  bane på en sær form som gjør det enkelt å redusere 3SAT til den banen.

Okei, Super Mario slik som du og jeg kjenner det er kanskje ikke NP hardt.

Men! Følgende problem **er** NP-hardt:

Gitt en nxn bane fra NES Super Mario Bros, kan mario nå målet fra start dersom vi antar at personen som kontrollerer mario er en pro gamer?

Def: Pro Gamer

En person som alltid tar de riktige valgene utifra informasjonen den har fått.

The proof is left as an exercise to the reader.

Eller spør Jonah
