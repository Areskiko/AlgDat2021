# Heaps
En heap er et [[Array | array]] objekt som kan ses på som et nesten komplett
binærtre.
Viktig med et heap er at A[parent(i)] >= A[i].
Dette kan sikres med med [[#MAX HEAPIFY | MAX HEAPIFY]] som sørger for
at at noden den kjøres på blir på riktig sted.
Skal en vilkårlig liste gjøres til en heap brukes [[Heap#BUILD MAX HEAP | BUILD MAX HEAP]].
Sortering i heap er [HEAPSORT](#heapsort).

[[#HEAP INCREASE KEY | INCREASE KEY]]

[[#MAX HEAP INSERT | MAX HEAP INSERT]]

Implementasjonen av disse funksjonene forutsetter at heapen representeres med et array i minnet: ![Array representation](bilder/HeapRepresentation.png)

![Relationship functions](bilder/HeapRelationships.png)


## MAX HEAPIFY
Kjøretid: O(lg n)

![max_heapify](bilder/MaxHeapify.PNG)

## BUILD MAX HEAP
Kjøretid: O(n)

![build_max_heap](bilder/buildMaxHeap.PNG)

Bevis:

![build_max_heap_proof](bilder/BevisBuildHeap.PNG)

## HEAPSORT
Kjøretid: O(n lg n)

![heapsort](bilder/heapsort.PNG)

## HEAP INCREASE KEY
Kjøretid: O(lg n)

![heap increase key](bilder/heapIncreaseKey.PNG)

## MAX HEAP INSERT
Kjøretid: O(lg n)

![max heap insert](bilder/maxHeapInsert.PNG)

#Datatype
#Sammenlign 