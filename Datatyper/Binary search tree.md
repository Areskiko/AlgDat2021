# Binært søketre
Grunnleggende operasjoner på et binært søketre har kjøretid proporsjonal
med høyden på treet.
For et [[Komplett Tree]] er dette $\theta(lg\cdot n)$, om treet derrimot 
er en lang rekke vil den samme operasjonen ta $\theta(n)$.
Forventet høyde av et tilfeldig bygget tre er $O(lg\cdot n)$




## Metoder
- [[#Search]]
- [[#Minimum]]
- [[#Maximum]]
- [[#Predecessor]] 
- [[#Successor]]
- [[#Insert]]
- [[#Delete]] 

### Search
![Search pseudocode](bilder/bintreesearch.png)

### Minimum
![Minimum pseudocode](bilder/bintreemin.png)

### Maximum
![Maximum pseudocode](bilder/bintreemax.png)

### Successor
![Successor pseudocode](bilder/bintreesucc.png)

### Predecessor
Virker identisk til [[#Successor]] men bruker left istedenfor right

### Insert
![Insert pseudocode](bilder/bintreeinsert.png)

### Delete
![Delete pseudocode](bilder/bintreetrans.png)

![Delete pseudocode](bilder/bintreedelete.png)

#Datatype 