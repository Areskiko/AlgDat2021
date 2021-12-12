En hashtabell er et dynamisk set som implementerer metodene:
INSERT, SEARCH og DELETE.

Gitt en [[Hashing | hash funksjon]] $h(x)$ kan en hash tabell der kollisjoner løses med chaining ([[Linked List | lenkede lister]]) implementeres slik.

![[HashTable.png]]

Kjøretider:
-	INSERT: $O(1)$
-	DELETE: $O(1)$ dersom listen er [[Double Linked List | doubly linked.]], $O(n)$ hvis ikke. Merk at DELETE tar inn et element, og må derfor ikke søkes etter. 
-	SEARCH: Når $n$ elementer hashes inn i $m$ båser får vi forventet antall verdier i hver bås: $\alpha = \frac{n}{m}$. SEARCH bruker i average case$\Theta(1 + \alpha)$ med antagelse om [[Enkel uniform hashing | enkel uniform hashing.]]