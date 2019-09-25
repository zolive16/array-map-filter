# Exercices sur map et filter

## Installation

* **D'abord** forker, **puis** cloner ce repo (indispensable pour Travis, sinon ça marche quand même sans Travis)
* **Si** tu as cloné d'abord sans forker, pas de panique, voir à la fin !
* Une fois le repo cloné, se placer dans le répertoire `array-map-filter`, puis lancer `npm install`

## Usage

**Absolument lire** la partie sur "réactiver les tests", ci-dessous !

* Il y a deux séries d'exercices, situées dans `map` et `filter`.
* L'ordre importe peu entre `map` et `filter`.
* Pour lancer les tests: `npm test`
* Tous les tests sont désactivés au début (`SKIP` en bleu clair si vous faites `npm test`), pour ne pas "polluer" le terminal avec des pages d'erreurs.
* **Les tests se réactivent 1 par 1**:

    * soit en remplaçant `xdescribe` par `describe`, dans le fichier de test correspondant à l'exercice sur lequel on travaille (par exemple, `tests/filter1.js` si on travaille sur `filter/ex1.js`).
    * soit plus simplement en lançant, depuis la racine du repo `array-map-filter`, `./enable SERIE NUMERO`, en remplaçant `SERIE` par `map` ou `filter` et `NUMERO` par le n° de l'exercice. Par exemple, `./enable map 2` pour activer les tests du 2ème exercice de la série `map`.
* On peut également les activer / désactiver tous d'un coup, via `./enableAll` et `./disableAll`

## HELP! J'ai cloné sans forker !

* Pas de panique: tu peux maintenant forker le dépôt
* Pour lier ton dépôt à ton fork, au lieu du dépôt initial, il faut éditer le fichier `.git/config`.
* Dans ce fichier, sous la ligne `[remote "origin"]`, remplacer `bhubr` par ton pseudo GitHub dans l'URL `https://github.com/bhubr/array-map-filter`.
