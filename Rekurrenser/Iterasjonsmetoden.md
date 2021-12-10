# Iterasjonsmetoden

Metode for å løse rekurrensrelasjoner. Iterativt sett inn for T(n) helt til du finner et
mønster. Lag et generelt uttrykk, uttrykt ved i, der i er hvilken iterasjon du er på. Sett inn
så inn for grunntilfellet, og løs.

Etter å ha funnet et svar kan du dobbletsjekke det med
[[Sjekke svar med WA | WolframAlfa]]

### Eksempel
![RekurrensEksempel](bilder/RekurrensEksempel.png)

Første iterasjon
Bytt ut $T(n-1)$ på høyre siden med $T(n-2) + 1$
Etter første iterasjon ser uttrykket slik ut
$T(n) = T(n-2) + 1 + 1 = T(n-2)+2$
Etter en iterasjon til blir uttrykket
$T(n) = T(n-3) + 3$
Vi ser nå at etter iterasjon $i$ blir
$T(n) = T(n-i) + i$

For å bli kvitt $T$ på høyre siden må vi sette inn $i$ slik at vi får $T(0) = 0$. I dette tilfellet kan vi sette inn $i = n$
$T(n) = T(n-n) +n = 0 + n = n$

Vi har nå løst rekurrensen
