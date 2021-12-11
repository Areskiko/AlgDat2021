### 3SAT (Boolean satisfiability problem)

Se for deg et logisk uttrykk som på formen POS

$[(x_1 \vee x_2 \vee y_1) \wedge ( \neg y_1 \vee \neg x_4 \vee \neg x_5) \wedge (\neg x_1 \vee x_4 \vee y_2) \wedge ( \neg y_2 \vee x_5 \vee \neg x_6)]$

Dvs paranteser som består at 3 boolske variabler som er enten negert eller
ikke. Disse n parantesene (clauses på engelsk) er 'and'-et sammen.

### Problemet:
Kan du gi verdier til alle variablene slik at det logiske utrykket blir sant?


Dette problemet er åpenbart i NP da det kan verifiseres i konstant tid gitt et
sertifikat (med serifikat menes her en kombinasjonav verdier for alle boolske
variablene). For å verfiserer at sertifikatet gir true så er det bare å sette inn verdiene i en implentasjona av uttrykket og se om det gir true.

#### Hvorfor er 3SAT i NP
Dette problemet er åpenbart i NP da det kan verifiseres i konstant tid gitt et sertifikat (med serifikat menes her en kombinasjon av verdier for alle boolske variablene). For å verfiserer at sertifikatet gir true så er det bare å sette inn verdiene i en implentasjona av uttrykket og se om det gir true.

#### Hvorfor er 3SAT NP-hardt?
3SAT er sett på som det første [[NP-Hard|NP-harde]] problemet bevist av Cook-Levin.

Som sagt i [[NP-Hard]], så må en kunne redusere alle problemer i NP til problem X for at X skal være [[NP-Hard|NP-hardt.]]

###### Grunnen til at du "lett" kan redusere et problem til 3SAT
Enkelt forklart:

Se for deg at du har et problem A. Du kan implementere A med en algoritme på en datamaskin. Det kan du igjen konkretisere til en krets som har input og output. En krets er bare boolsk algebra. Boolsk algebra (logiske uttrykk) kan du skrive om til POS (Product of Sums) og dermed oppnå et logisk uttrykk på formen til 3SAT.

$problem A -> algoritme -> krets -> logisk.uttrykk -> 3SAT$

Da 3SAT er både [[NP-Hard|NP-hardt]] og i [[NP]] så er det [[NP-Komplett]]