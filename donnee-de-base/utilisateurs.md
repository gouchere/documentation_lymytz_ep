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

- **Description :** Si cette option est activée, alors l'utilisateur ne pourra se connecter que s'il a été au préalable planifié dans un [créneau](com/creneaux.md)
- **Requis :**
- **Remarque :** Utilisez cette option si vous souhaitez limiter les accès de l'utilisateur à l'applications uniquement à des créneaux horiares spécifique

#### **Accès multi agence**

- **Description :** Si votre entreprise a plusieurs agences, activer cette option pour l'utilisateur lui permet de choisir au moment où il se connecte l'agence dans laquelle il veux travailler. Ainsi, l'utilisateur a accès aux données de toutes les agences
- **Requis :**
  > [!NOTE]
  > Il est possible de limiter les accès de l'utilisateur aux agences choisit uniquement à partir de l'onglet **Accès aux agences**. </br> > [!NOTE]
  > L'onglet Accès aux agences n'est visible qu'après avoir coché l'option accès multi agences

#### **Accès multi société**

- **Description :** De même que l'option précédente, cette option permet à l'utilisateur d'accéder aux différentes sociétés du groupe.
- **Requis :**

#### **Compte temporaire**

- **Description :** Si vous coché cette option, il est demandé de renseigner une date qui représente la date à partir de laquelle le compte de l'utilisateur ne pourra plus se connecter à l'application
- **Requis :**
- **Remarque :** Lorque l'echéance de connexion est atteint, le compte utilisateur ne peut simplement plus se connecter à l'application.

### 2. Modifier un utilisateur

### 3. Gérer les codes d'accès de l'utilisateur
