# TypeScript (.ts)

## Qu'est-ce que c'est ?
TypeScript est un sur-ensemble de JavaScript qui ajoute des types statiques. Cela aide à détecter les erreurs lors de la compilation.

## Exemple de code TypeScript

```typescript
// Définition d'une interface
interface Person {
    nom: string;
    age: number;
}

// Fonction utilisant l'interface
function greet(person: Person): string {
    return `Bonjour, ${person.nom}!`;
}

let user: Person = { nom: "John Doe", age: 21 };
console.log(greet(user));
