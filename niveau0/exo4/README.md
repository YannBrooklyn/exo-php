# Description de l'exercice:

Écris un script qui prend un âge en variable et affiche :
"Vous êtes mineur." si l’âge est inférieur à 18.
"Vous êtes majeur." sinon.

## Statut: 

Validé

-------------------------

# Message Correcteur IA:

Ta solution est presque parfaite, mais il y a une petite faute dans "Vous etes majeur." où "êtes" devrait être écrit avec un accent.

Correction :
```php
<?php

    $age = 10;

    if ($age < 18) {
        echo "Vous êtes mineur.";
    } else {
        echo "Vous êtes majeur.";
    }

?>
```

Explication :
✅ La condition if ($age < 18) est correcte.
✅ L'affichage est bien structuré avec echo.
✅ Il ne manque aucun point-virgule.
⚠️ Juste une petite correction orthographique.

Bonus (Amélioration) :
Si tu veux gérer aussi le cas où age == 18, tu peux le préciser :

```php
<?php

    $age = 18;

    if ($age < 18) {
        echo "Vous êtes mineur.";
    } elseif ($age == 18) {
        echo "Vous venez d'atteindre la majorité.";
    } else {
        echo "Vous êtes majeur.";
    }

?>
```
💯 Après correction, ton code est parfait ! 🚀