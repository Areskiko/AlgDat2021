En disjunkt set datatype oppretholder en samling $S =\{s_1,s_2,..,s_k\}$ disjunkte dynamiske set. Hvert set $s$ har en representant som representerer settet. 

Et disjunkt set støtter metodene:

MAKE-SET$(x)$ lager et nytt set med $x$ som eneste medlem. Det kreves at $x$ ikke er del av et annet set.

UNION$(x, y)$ slår sammen de to settene $s_x$ og $s_y$ til ett set med representant fra $s_x \cup s_y$

FIND-SET$(x)$ returnerer en peker til representanten til settet $x$ er en del av.