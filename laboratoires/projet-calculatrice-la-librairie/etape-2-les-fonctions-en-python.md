# Etape 2 - Les fonctions en python

Source :&#x20;

* [Standford university - Les fonctions en python](https://cs.stanford.edu/people/nick/py/python-function.html)
* [Convention commits - Les préfixes de commit](https://www.conventionalcommits.org/en/v1.0.0/)

## Intention pédagogique

Lors de ce laboratoire, nous allons étudier l'implémentation des fonctions. Cela vous permettra de maîtriser la déclaration des fonctions, le passage de paramètres ainsi que la gestion des retours.

C'est également une belle occasion d'entraîner l'utilisation des commandes git de bases ainsi que la pratique des préfixes de commit.

## Objectifs opérationnels

Chaque développeur junior doit atteindre les compétences suivantes:

* [ ] Déclarer une fonction en soignant la signature.
* [ ] Définir des paramètres de fonction.
* [ ] Définir le retour de fonction.
* [ ] Modifier l'architecture d'un programme "spaghetti" et tendre à une approche orientée objet.
* [ ] Appliquer une convention de commits.
* [ ] Etre capable de lire un diagramme de classe simplifié.

## Point de départ

Il s'agit de partir du code livré à l'étape précédente.

Après avoir supprimé le premier fork réalisé ainsi que votre dépôt en local, initialisé la librairie "git flow" comme suit:

```
git flow init
```

Vous devrez obtenir l'affichage suivant:



### Validation

Pour vérifier que les deux branches attendues sont là, utilisez la commande git suivant:

```
git branch
```

```
//Expected result
* develop
  main
```

Pour vérifier que vous êtes prêt à livrer ensuite du code sur votre propre dépôt forké

```
git remote -v
```

```
//Expected result
origin  https://github.com/<yourGithubAccountName>/python-setup-check.git (fetch)
origin  https://github.com/<yourGithubAccountName>/python-setup-check.git (push)
```

{% embed url="https://github.com/CPNV-CFC-I319/python-setup-check" %}

## Résultat à obtenir

Voici les différents appels aux fonctions auxquelles votre "main" sous-traite les actions spécifiques de notre programme:

```python
def main():    
    ask_user_input();
    result = calculate(operand1, operator, operand2);
    display_result(operand1, operator, operand2, result);
```

Et voilà la représentation de l'architecture dans un sytle _s'approchant_ d'un diagramme de classes:

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

## TODO

### Tâche 01

Refactor : externaliser la fonction demandant à l'utilisateur de saisir le calcul à l'aide de la fonction "ask\_user\_input()"

* [ ] Aide:&#x20;
  * [ ] [les fonctions en python](https://cs.stanford.edu/people/nick/py/python-function.html)
  * [ ] [initialiser une variable "vide"](https://realpython.com/null-in-python/#declaring-null-variables-in-python)

{% embed url="https://github.com/NicolasGlassey/python-setup-check/commit/38df230ad85ae2d6368ad20c9f4d7efc39f4367b" %}
Solution
{% endembed %}

### Tâche 02

Refactor : réécrire la structure conditionnelle "if / else" pour la détection de l'opérateur en un "match case":

* [ ] Aide:
  * [ ] [match case en python](https://www.geeksforgeeks.org/python-match-case-statement/)

{% embed url="https://github.com/NicolasGlassey/python-setup-check/commit/ed6266ac2b3dc93a57fda5bd93626529ab8591bb" %}
Solution
{% endembed %}

### Tâche 03

Refactor: externaliser la fonction qui réalise le calcul.

{% embed url="https://github.com/NicolasGlassey/python-setup-check" %}
Solution
{% endembed %}

### Tâche 04

Refactor : externaliser la fonction en charge de l'affichage du résultat

{% embed url="https://github.com/NicolasGlassey/python-setup-check/commit/f140bc0fc074e0a819ff7d930b20e3e60fd22d28" %}

### Tâche 05

Fix: la fonction "calculate" n'exploite pas correctement les variables locales.&#x20;

{% embed url="https://github.com/NicolasGlassey/python-setup-check/commit/cf1b5b4121c21f233a200aca9b85088269c9de68" %}
