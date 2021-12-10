# Sortering

* [[#Raske sorteringer | Raske sorteringer]]

## Viktige huskerregler

En sammenlikningsbasert kan IKKE kjøre raskere enn O(n lg n).

Bevis:
```
En liste med n elementer kan permuteres på n! måter.
Dermed må antall sammenlikninger m være 2^m>=n!.
Da får du m = n lg n - n.
Asymtotisk m = theta n lg n
```



## Tabell
![sorteringstabell](bilder/SorteringsKjøreTid.PNG)

## Sammenliknbare sorteringer
-	[[Merge Sort]]
-	[[Quicksor | Quicksort]]
-	[[Heap#HEAPSORT | Heapsort]]

## Raske sorteringer
- [[Radix Sort]]
- [[Counting Sort]]
