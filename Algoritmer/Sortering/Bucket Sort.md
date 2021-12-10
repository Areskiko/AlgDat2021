### Bucket Sort
Kjøretid: 
	Average case O(n)
	Worst Case O(n^2)
	
Sorterer elementer som ligger i intervallet \[0,1).
Average case oppnåes ved antagelsen at tallene er uniformt distribuert.
Det fører til at hver 'bøtte' har få elementer, som gjør at insertion sort kjører i lineær tid.
Grunnen til å ikke bruke en O(nlgn) sortering internt er for å beholde linearitet. 
Implementasjoner av f.eks. [[Merge Sort | merge sort]] og [[Quicksort | quicksort]] kan dra nytte av dette ved å bruke insertion sort når delinstansene blir små. 

Pseudokode: 
