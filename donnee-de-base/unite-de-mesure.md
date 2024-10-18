# Les unités de mesure

## Contexte

L'unité de mesure ou encore unité de conditionnement est un élément essentiel pour la gestion des stocks. Cette notion donne la possibilité de gérer le stock d'une référence d'article en restant au plus proche de la pratique physique (unité, paquet de 10, cartons, etc.)
</br>

### Prérequis

- [Créer les niveaux d'accès](niveau-d-acces.md)

> [!NOTE]  
> En générale, l'accès à la fonctionnalité se fait en suivant le chemenin **`Données de bases > Général > unités de mesure`**

### 1. Formulaire générale

![formulaire-unite-mesure.png](https://i.postimg.cc/dtCqPdYg/formulaire-unite-mesure.png)

#### **Définir comme unité par défaut**

- **Description :** Permet de fixer l'unité en cours comme unité par défaut lors du paramétrage des articles.
- **Requis :**:no_entry_sign:
  > ![NOTE] Une unité par defaut et toute fois requise lorsque vous souhaitez importer votre catalogue à partir d'une source externe (fichier .csv par exemple)

#### **Référence**

- **Description :** Indiquez la référence ou l'abreviation de l'unité
- **exemple :** `Kg`
- **Requis :** ✅

#### **Libellé**

- **Libellé :** Indiquez un nom long pour l'unité
- **exemple :** `Kilogramme`
- **Requis :** ✅

#### **Type**

- **Description :** Le type d'unité est important. Il permet de grouper les unités quantitative, temporalle, etc.
- **exemple :** `Temps`
- **Requis :** ✅

#### **Description**

- **Description :** Entrez une description supplémentaire, si l'unité que vous créée n'est pas connu de tout le monde
- **exemple :**
- **Requis :** :no_entry_sign:
- **Remarque :** Le code d'affichage peux être nécessaire lorsqu'on veut que le code utilisateur qui apparait sur les rapports imprimé soit différent du nom

#### **Conversion d'unités**

Il est possible de paramétrer le coeficient de conversion entre deux unités d"une même référence comme le montre la capture ci-dessous.
![formulaire-conversion-unite.png](https://i.postimg.cc/W4gWsN3N/formulaire-conversion-unite.png)<br/>

Pour définir un nouveau coéficient de conversion entre deux référence, vous pouvez procéder comme suit:

##### 1. Selectionner l'unité depuis la vue liste

![liste-unite-mesure.png](https://i.postimg.cc/6pwhJDSR/liste-unite-mesure.png)

##### 2. Selectionner l'unité cible

![formulaire-unite-cible.png](https://i.postimg.cc/DfLsvx1c/formulaire-unite-cible.png)

##### 3. Entrer le coefficient de conversion

> ![NOTE]
> Vous pouvez directement définir l'unité équivalente en cliquant sur **Inserer l'équivalence** comme sur la capture ci-dessous
> ![fomulaire-unite-equivalente.png](https://i.postimg.cc/G2NZXcXv/fomulaire-unite-equivalente.png)
