# Description de l'exercice:

Affiche les nombres de 1 à 10 en utilisant une boucle for, puis fais la même chose avec une boucle while.

## Statut: 

Reussie


# Message Correcteur IA:

Ta solution est presque correcte, mais il y a un petit problème avec \n :

Correction :
```php
<?php

    $number = 0;

    while ($number < 11) {
        echo "$number<br>"; // Utilisation de <br> pour un affichage correct en HTML
        $number++;
    }

?>
```
Explication :
✅ La boucle while est correcte : elle s'exécute tant que $number est inférieur à 11.
✅ L'incrémentation $number++ fonctionne bien.
⚠️ Problème avec \n :

\n fonctionne en ligne de commande (CLI), mais pas en HTML.
En HTML, il faut utiliser ```<br>``` pour passer à la ligne.
Alternative pour l'affichage en terminal (CLI)
Si tu exécutes ce code en ligne de commande (pas dans un navigateur), alors \n est correct, mais il doit être utilisé dans des apostrophes simples (') ou avec PHP_EOL :

```php
<?php

    $number = 0;

    while ($number < 11) {
        echo $number . PHP_EOL; // Compatible CLI
        $number++;
    }

?>
```
✅ Après correction, ton code est parfait pour le bon environnement ! 🚀