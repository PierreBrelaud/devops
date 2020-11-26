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
