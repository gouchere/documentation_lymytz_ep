# Gestion des niveaux d'accès

## Contexte

Le paramétrage des niveaux d'accès est essentielle pour commencer l'exploitation de l'application. C'est ici qu'on définira les groupes de rôles et les fonctionnalités aux quelles chaque groupe aura accès. Ensuite il ne suffira d'affecter chaque [utilisateur](utilisateurs.md) à un niveau d'accès pour déterminer l'ensemble de ses privillèges dans l'application

### 1. Créer les niveaux d'accès

> [!NOTE]  
> En générale, l'accès à la fonctionnalité se fait en suivant le chemenin **`Données de bases > Utilisateurs > Niveau d'acces`**

![formulaire-niveau-acces.png](https://i.postimg.cc/WzWv7pBd/formulaire-niveau-acces.png)

Lorsque vous êtes sur la page des niveaux d'accès, il faut se placer sur le champs **Niveau** et selectionner l'option _**Plus de choix**_ comme sur la capture.
Lorsque vous selectionnez cette option, une modale s'ouvre et vous permet de voir la liste des niveaux d'accès déjà créée et également d'ouvrir le formulaire de création de nouveaux niveaux

#### **Désignation**

- **Description :** Champ libre de saisie de la désignation du niveau
- **Requis :** ✅
- **Remarque :** choisissez une expression suffisament représentattive du groupe d'utilisateurs devant porter ce rôle
- **exemple :** `ADMIN`, `VENDEURS`, `MAGASINIERS`

#### **Grade**

- **Description :** Choisissez un grade dans la liste de selection
- **Requis :**

#### **Faire hériter des droits du niveau**

- **Description :** Pour simplifier la paramétrage des privillège d'un groupe/niveau d'accès, vous pouvez les faires hériter d'un autre. Lorsque vous faites hériter un niveau d'un autre, l'ensemble des privillèges du groupe selectionné sont attribués au nouveau niveau
- **Requis :**

> [!IMPORTANT] . Cette copie ne se fait qu'à la création. Si plus tard vous faites évoluer un niveau, celà ne modifie pas les privillèges du niveau hérité

#### **Description**

- **Description :** Décrivez si possible le groupe
- **Requis :**

### Ajouter des utilisateurs au niveau d'accès
