# PHP (.php)

## Qu'est-ce que c'est ?
PHP (Hypertext Preprocessor) est un langage de script côté serveur utilisé principalement pour le développement web.

## Exemple de code

```php
<?php
// Fonction pour saluer un utilisateur
function greet($user) {
    return "Bonjour, " . $user . "!";
}

$user = "John Doe";
echo greet($user);
?>
