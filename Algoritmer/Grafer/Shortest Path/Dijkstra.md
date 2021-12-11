# Djikstra Algoritme

## Egenskaper
-	Funker ikke med [[Negative Kanter | negative kantvekter]]
-	Alle til alle med tabell kjøretid: $O(V^3+VE)$
-	Alle til alle med binærhaug kjøretid: $O(VE\lg V)$
-	Alle til alle med Fibonacci-haug: $O(V^2\lg V+VE)$
-	[[Negative Kanter | Negative kanter]] er en
[[Diskriminerende Faktorer | Diskriminerende faktor]]


## Algoritme
Kjøretid: O(E lg V) hvis alle noder kan nås fra rot

![[Djiksrta.PNG]]

Extract min:

Kjøretid: $\Theta$(lg n)

#Graf
#Algoritme/Graf