# TD 8 Gestion mémoire

## Question 1
La taille demandée par l'appel à la fonction malloc est de 104 octets.

## Question 2
Un appel à malloc avec la valeur 80 déclenchera un appel à sbrk car la taille demandée est supérieure à la taille de la mémoire disponible. Ainsi la zone mémoire utilisée pour effectuer un malloc(80) sera la zone rendue disponible par l'appel à sbrk et non le le premier trou de mémoire libéré par le précédent appel à free qui n'est pas assez grand (48<80).

## Question 3 
La plus grande valeur pouvant être demandée est de 48 octets pour remplir le premier trou de la zone mémoire.

## 4.2.2
Nous pouvons en effet constater que l'utilisation de la fonction malloc standard ne réutilise pas les zones mémoires libérées et ajoute les nouvelles allocations tout à la fin du tas. 
