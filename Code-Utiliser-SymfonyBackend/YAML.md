# YAML (.yaml)

## Qu'est-ce que c'est ?
YAML (YAML Ain't Markup Language) est un format de données lisible par l'homme, souvent utilisé pour la configuration et le stockage de données.

## Exemple de configuration

```yaml
# Configuration d'un serveur
serveur:
  nom: mon_serveur
  port: 8080
  ssl: true
  utilisateurs:
    - nom: user1
      role: admin
    - nom: user2
      role: guest
