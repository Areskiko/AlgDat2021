### Bucket Sort
Kjøretid: 
- Average case $O(n)$
- Worst Case $O(n^2)$
	
Sorterer elementer som ligger i intervallet \[0,1).

Average case oppnåes under antagelsen at tallene er uniformt distribuert.
Det fører til at hver 'bøtte' har få elementer, som gjør at [[Insertion Sort | insertion sort]] kjører i lineær tid

![[BucketSort.png]]


Grunnen til å ikke bruke en $O(nlg(n))$ sortering internt er for å beholde linearitet. 
Implementasjoner av f.eks. [[Merge Sort | merge sort]] og [[Quicksort | quicksort]] kan dra nytte av dette ved å bruke insertion sort når delinstansene blir små. 

Stabilitet er avhengig av sorterings-implementasjonen.

#Algoritme/Sortering 
#Stabil 