# Sortering

* [Raske sorteringer](#raske-sortering)

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

## Raske sorteringer

### Counting sort
Kjøretid: O(n+k)

![CountingSort](bilder/CountingSort.PNG)

Atributter:
* Stabil
* Brukes ofte med [radix sort](#radix-sort)

### Radix sort
Kjøretid: O(d(n+k))

![Radix sort](bilder/radixsort.PNG)