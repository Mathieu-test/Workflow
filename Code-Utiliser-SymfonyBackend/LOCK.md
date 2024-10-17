# Lock (.lock)

## Qu'est-ce que c'est ?
Les fichiers `.lock` sont utilisés pour gérer les dépendances dans des projets, assurant que les mêmes versions des bibliothèques sont installées à chaque fois.

## Exemple de contenu

```json
{
    "dependencies": {
        "package-name": {
            "version": "1.0.0",
            "resolved": "https://registry.npmjs.org/package-name/-/package-name-1.0.0.tgz",
            "integrity": "sha512-abc123"
        }
    }
}
