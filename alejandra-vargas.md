## Diferencia entre git merge y gir merge --no--ff

La diferencia mas importante radica en que al momento de usar git merge  
se combinan dos ramas posicionando al HEAD de la rama primaria  
en el ultimo commit entrante de la rama secundaria (fast forward).  
En cambio, si se usa git merge --no--ff, se evita que se realice un fast  
forward y se genera un nuevo commit para documentar la fusion de dichas ramas,  
constatando de esta manera la existencia de aquella rama ajena a la principal.
