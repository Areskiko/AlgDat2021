# Flytproblemer
En rettet graf kan tolkes som et flytnettverk, som beskriver flyt fra kilde til sluk. Hver [[Kanter | kant]] kan sees på som en ledning som har en gitt kapasitet eller flytrate. [[Noder]] kan ses på som et kryss i ledningsnettet. Flytraten inn i noden er lik flytraten ut (flytbevaring). Maks flyt problemet er å finne den største flyten man kan få fra kilde til sluk.

## Antagelser
-	Lov til å ha [[Sykler | sykler]]
-	**IKKE** lov til å [[Antiparallelle kanter | antiparallelle kanter]] (kan løses)
-	[[Noder]] har **IKKE** lov til å kanter til seg selv (loop)
-	Kun en kilde og sluk. (Kan løses)

## Løsninger til antagelser
-	[[Antiparallelle kanter]] kan gjøres om til flere [[Noder | noder]]
	![[AntiParallellEdges.png]]
-	Flere kilder og sluk kan løses med å legge til super sluk og super kilder
	![[SuperSink.png]]


## Algoritmer
[[Ford Fulkerson]] $O(Ef)$

[[Edmonds Karp]] $O(VE^2)$
