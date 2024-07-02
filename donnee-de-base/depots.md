# Les dépôts

## Contexte

Nous traiterons ici l'une des notions les plus importantes du processus de gestion des stocks.

### Sommaire

> * Informations générales
> * Les relations entre dépôts
> * Les options de calcul du prix de revient
> * Les créneaux horaires
> * Les autorisations d'accès

> [!NOTE]  
> En générale, l'accès à la fonctionnalité se fait en suivant le chemenin **`Données de bases > Emplacement> Dépôts`**

Les informations attendues pour paramétrer les dépôts au sein de l'application sont resumé sur la capture suivante:
[![formulaire-depots.png](https://i.postimg.cc/43wyVqQk/formulaire-depots.png)](https://postimg.cc/d7kJKWf4)

La première partie du formulaire présente les champs

### 1. Informations générales

#### **Code**

* **Description :** Code permetant d'identifier le dépôt sur dans l'application
* **exemple :** `DPT_AKWA`
* **Requis :** ✅
* **Remarque :** Ce champ est en générale autogénéré à partir des données champ abbreviation. Il est souhaitable q'uil soit unique

#### **Abbreviation**

* **Description :** Champ de saisie libre servant en générale de suffixe au code dépôt
* **exemple :** `AKWA`
* **Requis :** ✅
* **Remarque :** Il vaut mieux que la valeur soit une chaîne assez courte qui facilite l'affichage de l'information sur les autres formulaires

#### **Désignation**

* **Description :** Champ de saisie libre pour renseigner un nom long pour le dépôt
* **exemple :** `MAGASIN CENTRALE`
* **Requis :** ✅
* **Remarque :** Choisissez une désignation suffisament caractérielle de l'utilisation du dépôt

#### **Agence**

* **Description :** Selectionner l'agence à laquelle se dépôt est rattaché dans une liste proposé.
* **exemple :** `MAGASIN CENTRALE`
* **Requis :** ✅
* **Remarque :** Cette information est un prérequis à la création des dépôts

#### **Code d'accès**

* **Description :** Cette information permet de poser une restriction au dépôt et ne le rendre utilisable que par des utilisateurs possédant le même code. C'est une chaine de saisie libre, .
* **exemple :** `ACC_PRIV`
* **Requis :** 
* **Remarque :** 
  * Il est possible de réutiliser un code déjà crée
  * Le paramétrage des code d'accès utilisateur complète cette partie


### Options du dépôt

### Opérations autorisées

### Relations avec les autres dépôt

### Les créneaux horaire

### Les autorisations d'accès

* **Code**: Code d'identification du dépôt, c'est un champ de saisie libre, en générale généré automatiquement à partir du code d'abbreviation
* **Abbreviation**: champ de saisie libre, avec un code permettant d'identifier le dépôt. On préfère en générale une chaîne de caractère pas très longue qui peut s'afficher en occupant le moins de place possible.
* **Code <span color=`#FF0000`>*<span>**: Code d'identification du dépôt, c'est un champ de saisie libre
