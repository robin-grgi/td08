# TD 8 Gestion mémoire

## Question 1
La taille demandée par l'appel à la fonction malloc est de 104 octets.

## Question 2
Un appel à malloc avec la valeur 80 déclenchera un appel à sbrk car la taille demandée est supérieure à la taille de la mémoire disponible.

## Question 3 
La plus grande valeur pouvant être demandée est de 48 octets.

## 4.2.2
Nous pouvons en effet constater que l'utilisation de la fonction malloc standard ne réutilise pas les zones mémoires libérées et ajoute les nouvelles allocations tout à la fin du tas. 