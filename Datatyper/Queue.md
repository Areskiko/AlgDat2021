# Queue
En liste med elementer. Veldig likt som [[Stack | stack]], men bruker FIFO istedenfor LIFO. Implementeres ofte med en [[Array | array]]. En queue har head og tail, head er indeksen til første element i køen, og tail er indeksen til der neste element legges til. En kø "wrapper" rundt et [[Array | array]]. Hvis man har et array med n > 5 elementer, tail = n og head = 5. Hvis det legges til et nytt element vil tail bli 1 (gitt 1-indekserte arrays(sigh)).

### Overflow / Underflow
Hvis det legges til et element i en full liste får vi en queue overflow, og hvis man fjerner et element fra en tom liste, får man en queue underflow.

En queue er tom dersom tail = head. Den er full dersom head = tail+1 eller head = 1 og tail = length.

### Enqueue O(1)
![[Enqueue.png]]

### Dequeue O(1)
![[Dequeue.png]]

#Datatype