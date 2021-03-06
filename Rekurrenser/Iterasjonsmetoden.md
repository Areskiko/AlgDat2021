# Iterasjonsmetoden

Metode for å løse rekurrensrelasjoner. Iterativt sett inn for T(n) helt til du finner et
mønster. Lag et generelt uttrykk, uttrykt ved i, der i er hvilken iterasjon du er på. Sett inn
så inn for grunntilfellet, og løs. Får ofte summer man må gjenkjenne, som feks. $\sum_{i=1}^{n}i$ eller $\sum_{i=0}^{n}2^i$, som har [[Kjente summer | kjente løsninger.]]

Etter å ha funnet et svar kan du dobbletsjekke det med
[[Sjekke svar med WA | WolframAlpha]]

### Eksempel 1
![RekurrensEksempel](bilder/RekurrensEksempel.png)

Første iterasjon\
Bytt ut $T(n-1)$ på høyre siden med $T(n-2) + 1$\
Etter første iterasjon ser uttrykket slik ut\
$T(n) = T(n-2) + 1 + 1 = T(n-2)+2$\
Etter en iterasjon til blir uttrykket\
$T(n) = T(n-3) + 3$\
Vi ser nå at etter iterasjon $i$ blir\
$T(n) = T(n-i) + i$

For å bli kvitt $T$ på høyre siden må vi sette inn $i$ slik at vi får $T(0) = 0$. I dette tilfellet kan vi sette inn $i = n$\
$T(n) = T(n-n) +n = 0 + n = n$

Vi har nå løst rekurrensen

### Eksempel 2
Tatt fra [Eksamen kont 2020](https://algdat.idi.ntnu.no/arkiv/2021.aug.tdt4120.oppg.no.pdf)
![RekurrenseEksempel2](bilder/RekurrensEksempel2.png)

Første iterasjon\
$T(n) = T(n-2) + (n-1) + n -1/2 -1/2 = T(n-2) + (n-1) + n + n -2/2$

Andre iterasjon\
$T(n) = T(n-3) + (n-2) + (n-1) + n - 3/2$

Generelt kan iterasjon $i$ skrives som\
$T(n) = T(n-i) + (n-i +1) + (n-i+2)+ .... + (n-2) + (n-1) + n - i/2$\
$T(n) = T(n-i) + [\sum_{k = n-i+1}^{k = n} k] - i/2$\
For å bruke $T(0)=0$ setter vi $i=n$\
$T(n) =  0 + [\sum_{k = 1}^{k = n} k] - n/2$\
Bruker at summen av de $n$ første heltallene er $\frac{n(n+1)}{2}$\
$T(n) = \frac{n(n+1)}{2} - \frac{n}{2} = \frac{n^2}{2}$

#Rekurens