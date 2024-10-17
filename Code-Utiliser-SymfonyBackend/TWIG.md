# Twig (.twig)

## Qu'est-ce que c'est ?
Twig est un moteur de templates pour PHP, utilisé pour séparer la logique de présentation dans les applications web.

## Exemple de template

```twig
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>{{ title }}</title>
</head>
<body>
    <h1>{{ header }}</h1>
    <p>{{ content }}</p>
</body>
</html>
