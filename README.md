# JavaScript – Premiers apprentissages

## Présentation

Ce projet correspond à ma première prise en main de JavaScript.
L’objectif était de comprendre les bases du langage et de commencer à interagir avec une page web.
Je suis française, mais j’ai suivi cette formation en anglais, ce qui ne m’a pas posé de difficulté particulière.

## Ce que j’ai appris

### Bases du langage

* Déclarer des variables avec `let` et `const`
* Manipuler des nombres et des chaînes de caractères
* Utiliser `console.log()` pour tester et comprendre le code

### Fonctions

* Créer des fonctions simples
* Structurer un minimum le code

### Le DOM (Document Object Model)

* Comprendre que JavaScript peut modifier une page HTML

Méthodes et propriétés utilisées :

* `document.getElementById()`
* `.innerText`
* `.textContent`

## Exemple

```javascript id="p4k2x9"
let count = 0

function increment() {
    count += 1
    document.getElementById("counter").innerText = count
}
```

## Lancer le projet ou site web

- lien : https://compteur-scrimba.netlify.app

```bash id="l8m3q1"
npm install
npm start
```

## Objectif

Pour l’instant, je me concentre sur les bases.
La suite sera d’aller vers :

* les événements (click, input, etc.)
* les interactions utilisateur
* et progressivement des projets plus complets

## Remarque

Ce projet me sert surtout de support pour pratiquer.
Il ne montre pas encore un projet complet, mais plutôt une progression dans l’apprentissage.
