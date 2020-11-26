# Lead tech - TP2

## Convention de coding

* **Nommage**

Utilisation du **camel case** pour le nommage des variables et fonctions
```
myVariableName, myFunctionName
```
Avoir des noms de variable/fonctions explicites
```
❌ let s = 0;
✔️ let score = 0;
```

Ne pas avoir des noms de variable/fonctions trop longs

Définir un ordre dans le nommage de la fonction que l'on duplique. ex : 
```
❌ userGetName, getUserId, userBirthdayGet
✔️ getPersonName, getPersonId, getPersonBirthday
```



* **Fonctions**

Une fonction = une fonctionnalité

Ne pas avoir de fonction trop longue, préférer séparer en plusieurs fonctions

* **Commentaire**

Commenter dès que la logique du code peut être un peu complexe.

Documenter chaque fonction en précisant ce que fait la fonction, les paramètres et retour attendu ex:  
```js
/**
 * Returns x raised to the n-th power.
 *
 * @param {number} x The number to raise.
 * @param {number} n The power, must be a natural number.
 * @return {number} x raised to the n-th power.
 */
function pow(x, n) {
  ...
}
``` 

* **Code**
Tabulation commune.
Commentaires et variables en anglais.

* **Structures conditionnelles / fonctions**

Format à respecter : 

```js
❌ if(user.isAdmin()) return true;

❌ if(user.isAdmin()) { return true; }

❌
if(user.isAdmin())
    return true;

✔️ 
if(user.isAdmin()) {
    return true;
}


```








## Choix d'infrastructure




Entrez ici les instructions pour bien débuter avec votre projet...

### Pré-requis

Ce qu'il est requis pour commencer avec votre projet...

- Programme 1
- Programme 2
- etc...

### Installation

Les étapes pour installer votre programme....

Dites ce qu'il faut faire...

_exemple_: Executez la commande ``telnet mapscii.me`` pour commencer ensuite [...]


Ensuite vous pouvez montrer ce que vous obtenez au final...

## Démarrage

Dites comment faire pour lancer votre projet

## Fabriqué avec

Entrez les programmes/logiciels/ressources que vous avez utilisé pour développer votre projet

_exemples :_
* [Materialize.css](http://materializecss.com) - Framework CSS (front-end)
* [Atom](https://atom.io/) - Editeur de textes

## Contributing

Si vous souhaitez contribuer, lisez le fichier [CONTRIBUTING.md](https://example.org) pour savoir comment le faire.

## Versions
Listez les versions ici 
_exemple :_
**Dernière version stable :** 5.0
**Dernière version :** 5.1
Liste des versions : [Cliquer pour afficher](https://github.com/your/project-name/tags)
_(pour le lien mettez simplement l'URL de votre projets suivi de ``/tags``)_

## Auteurs
Listez le(s) auteur(s) du projet ici !
* **Jhon doe** _alias_ [@outout14](https://github.com/outout14)

Lisez la liste des [contributeurs](https://github.com/your/project/contributors) pour voir qui à aidé au projet !

_(pour le lien mettez simplement l'URL de votre projet suivi de ``/contirubors``)_

## License

Ce projet est sous licence ``exemple: WTFTPL`` - voir le fichier [LICENSE.md](LICENSE.md) pour plus d'informations