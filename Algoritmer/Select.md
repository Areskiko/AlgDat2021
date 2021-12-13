Finner det $i$-te største elementet i en tabell med $n$ elementer. 

Kjøretid: $O(n)$ (wow!)

Selve algortimen er ikke beskrevet i pensum. Men går i korte trekk ut på å:

1. Dele opp tabellen i $\lfloor\frac{n}{5}\rfloor$ grupper på fem elementer, (og muligens en mindre gruppe). 
2. Finne medianen til gruppene med insettion sort (som har lineær kjøretid på små tabeller).
3. Kjør SELECT rekursivt for å finne medianen av disse $\lceil\frac{n}{5}\rceil$ medianene. 
4. Partisjoner rundt median-medianen (ved bruk av en modifisert [[Partition | partition]]), denne får indeks $k$. 
5. Dersom $i = k$ returner median-medianen. Ellers kjør SELECT rekursivt på den øvre eller nedre tabellen avhengig av $k < i < k$. 

#Algoritme 