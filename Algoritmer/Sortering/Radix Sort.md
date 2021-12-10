### Radix sort
Kjøretid: O(d(n+k)), der d er lengden på elementene, n er antall elementer og k er størrelsen på hvert 'del-element'.

Radix sort er en logisk utvidelse av [[Counting Sort | counting sort]] for å kunne hanskes med store tall i lineær tid.

![Radix sort](bilder/radixsort.PNG)

Attributter:
- Underliggende sortering **må** være stabil
- Brukes til å sortere strenger
- Brukes til å sortere integer fra 0 til $n^k-1$ i O(n) tid
	- Konverter alle til base n og radix sorter listen


#Algoritme
#Sortering 