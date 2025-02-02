# Description de l'exercice :

Crée deux variables $prenom et $nom, assigne-leur des valeurs, puis affiche "Bonjour, [Prénom] [Nom] !" en les concaténant.

## Statut : 

Validé

--------------------------

# Message Correcteur IA:

Ta solution est presque parfaite, mais il manque un point-virgule (;) à la fin de l'instruction echo.

Correction :

```php
<?php
    $prenom = "Foo";
    $nom = "Bar";

    echo "Bonjour, $prenom $nom !";
?>
```

Explication :

En PHP, chaque instruction doit se terminer par un ;.
Tu as bien utilisé les doubles guillemets (""), ce qui permet d'interpréter directement les variables dans la chaîne.
✅ Correct après ajout du point-virgule ! 🎉