# Description de l'exercice:

Écris une fonction carre($nombre) qui prend un nombre en argument et retourne son carré.


## Statut: 

Échoué

# Message Correcteur IA:

Ta solution contient une erreur ! ❌

Problème :
La fonction carre($nombre) est censée retourner le carré du nombre, mais tu fais une division par 2 ($nombre / 2) au lieu de l'élever au carré ($nombre * $nombre).

Correction :
```php
<?php

    $nombre = 10;
    
    function carre($nombre) {
        return $nombre * $nombre; // Correction : multiplication pour obtenir le carré
    }

    echo carre($nombre);

?>
```

Explication :
✅ La fonction carre($nombre) prend un nombre en paramètre.
✅ Elle retourne le carré du nombre en le multipliant par lui-même ($nombre * $nombre).
✅ L'affichage fonctionne correctement avec echo carre($nombre);.

Résultat attendu pour $nombre = 10
👉 Le script affichera :

```
100
```

💯 Après correction, c'est parfait ! 🚀

# Message Utilisateur : 

Je me suis tromper dans la formule.