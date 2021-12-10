# Stack

Datatype som inneholder en liste med elementer. En stack er LIFO, last in, first out. En n-elementers stack kan implementeres med et n-elementers [[Array]]. S[1,...,n], der S[1] er det nederste elementet i stacken, og S.top er elementet ved toppen. Hvis S.top = n vil stacken være full, og hvis S.top = 0, er stacken tom. 

## Metoder

### Empty
Checks if stack is empty
![stack_empty](bilder/StackEmpty.png)

### Push
Adds element to the top of the stack
![stack_push](/bilder/StackPush.png)

### Pop
Removes element from the top of the stack
![stack_push](bilder/StackPop.png)