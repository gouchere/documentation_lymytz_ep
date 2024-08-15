# Gestion des utilisateurs

## Contexte

Le paramétrage des utilisateurs est une étape importante de la prise en main de la solution et de l'ensemble de ses fonctionnalités. En effet, toutes les fonctionnalités disponible dans la solution sont contrôlé par des **rôles** ou **autorisation**; aussi lorsqu'on créée un utilisateur, il peut être important de se poser des questions comme par exemple

- Peut-il oui ou non valider des documents (d'achat, de vente, etc.)?
- Aura-t-il la possibilité de valider ou d'afficher des document de transferts?
- Sera-t-il en mesure de d'enregistrer un virement d'une caisse à une autre?
- etc. </br>

> [!TIP]
> Il est important dès le départ de constituer des groupes d'utilisateurs

### Prérequis

- [Créer les niveaux d'accès](niveau-d-acces.md)

> [!NOTE]  
> En générale, l'accès à la fonctionnalité se fait en suivant le chemenin **`Données de bases > Utilisateurs > utilisateurs`**

### 1. Formulaire générale

![formulaire-utilisateurs.png](https://i.postimg.cc/14xjSPMX/formulaire-utilisateurs.png)

#### **Civilités**

- **Description :** Choisir la civilité parmi les options
- **exemple :** `M.`
- **Requis :** ✅

#### **Nom & prénom**

- **Description :** Vous pouvez entrer le nom entier de l'utilisateur. s
- **exemple :** `Paul Lontsi`
- **Requis :** ✅

#### **Actif**

- **Description :** Permet d'indiquer si l'utilisateur est ou non actif
- **Remarque :** Les utilisateurs non actif ne peuvent pas se connecter au logiciel

#### **Login**

- **Description :** Le login est une chaine de caratère courte qui sera utilisé pour se connecter à l'application
- **exemple :** `LONP`
- **Requis :** ✅
- **Remarque :** On choisit souvent les initiales de la personne.

#### **Code d'affichage**

- **Description :** Le code d'affichage est un
- **exemple :** `DICLOFENAC 75MG/3ML`
- **Requis :**
- **Remarque :** Le code d'affichage peux être nécessaire lorsqu'on veut que le code utilisateur qui apparait sur les rapports imprimé soit différent du nom

#### **Niveau d'accès**

- **Description :** C'est cette information qui indique à quel groupe de rôles appartient l'utilisateur et donc les fonctionnalités auxquelles il a ou non accès.
- **Requis :** ✅
- **Remarque :** Les niveaux d'accès sont propre aux agences. Il est important de choisir au préalable l'agence avant.

#### **Groupe**

- **Description :** Groupe d'appartenance de l'utilisateur
- **Requis :**

#### **Se connecter avec un planning**

- **Description :** Si cette option est activée, alors l'utilisateur ne poura se connecter que s'il a été au préalable planifié dans un [créneau](com/creneaux.md)
- **Requis :**
- **Remarque :** choisissez des dignation aussi significative que possible

#### **Accès multi agence**

- **Description :** C'est un champ de saisie libre pour renseigner la disignation de votre article
- **exemple :** `DICLOFENAC 75MG/3ML`
- **Requis :** ✅
- **Remarque :** choisissez des dignation aussi significative que possible

#### **Accès multi société**

- **Description :** C'est un champ de saisie libre pour renseigner la disignation de votre article
- **exemple :** `DICLOFENAC 75MG/3ML`
- **Requis :** ✅
- **Remarque :** choisissez des dignation aussi significative que possible

#### **Compte temporaire**

- **Description :** C'est un champ de saisie libre pour renseigner la disignation de votre article
- **exemple :** `DICLOFENAC 75MG/3ML`
- **Requis :** ✅
- **Remarque :** choisissez des dignation aussi significative que possible
