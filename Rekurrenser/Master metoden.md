Master metoden er en metode for å løse [[rekurenser]].
Den fungerer for rekurenser med formen
$T(n)=a\cdot T(n/b)+f(n)$, hvor $a\geq 1$, $b>1$ og $f(n)$ er kjent.

Det er tre løsninger basert på noen kriterier:

## Case 1
Om $f(n)=O(n^{log_{b}\ a-\epsilon})$ så
$T(n)=\theta (n^{log_{b}\ a})$

## Case 2
Om $f(n)=O(n^{log_{b}\ a})$ så
$T(n)=\theta (n^{log_{b}\ a}\cdot lg(n))$

## Case 3
Om $f(n)=O(n^{log_{b}\ a+\epsilon})$ for $\epsilon > 0$ og $a\cdot f(n/b)\leq c\cdot f(n)$ for $c<1$ vil, med stor nok $n$,
$T(n)=\theta (n^{log_{b}\ a}\cdot lg(n))$
