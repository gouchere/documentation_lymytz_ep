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

* **Description :** Cette information permet de poser une restriction au dépôt et ne le rendre utilisable que par des utilisateurs possédant le même code. C'est une chaine de saisie libre.
* **exemple :** `ACC_PRIV`
* **Requis :** 
* **Remarque :** 
  * Il est possible de réutiliser un code déjà crée
  * Le paramétrage des code d'accès utilisateur complète cette partie


#### **Actif**

* **Description :** Permet d'indiquer si le dépôt est actif ou non
* **exemple :** `OUI` ou `NON`
* **Requis :** 
* **Remarque :** Les dépôt non actif ne seront pas visible sur les autres formulaires.

#### **Rappel Appro**

* **Description :** Permet d'indiquer si le dépôt est actif ou non
* **exemple :** `OUI` ou `NON`
* **Requis :** 
* **Remarque :** Les dépôt non actif ne seront pas visible sur les autres formulaires.

#### **Dépôt multi tranche**

* **Description :** La notion de tranche hororaire est importante et permet d'affiner le calcul de stocks dans des tranche spécifique, en particulier lorsqu'on est dans un environnement **non temps réel**
* **exemple :** `OUI` ou `NON`
* **Requis :** 
* **Remarque :** 

#### **Activer la gestion par lot**

* **Description :** Lorsque ce champ est actif, il devient possible de prendre en charge la gestion des lots pour les articles s'y trouvant.
* **exemple :** `OUI` ou `NON`
* **Requis :** 
* **Remarque :** La même option doit être activé au moment de lier l'article à ce dépôt.


### Options du dépôt

### Opérations autorisées

### Relations avec les autres dépôt

### Les créneaux horaire

### Les autorisations d'accès