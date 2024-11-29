# Les modèles d'articles

## Contexte

Les modèles d'articles ou templates d'articles sont un moyen simple de définir des paramètres qu'on pourra appliquer à un groupe d'articles; il s'agit entre autre de la **catégorie**, **Paramètres comptable** , **catégorie de prix/remises**

**Exemple :** **_FV00001_** pour une facture de vente
</br>

> [!NOTE]  
> En générale, l'accès à la fonctionnalité se fait en suivant le chemenin **`Données de bases > Général > Templates Article`**

### 1. Formulaire générale

![formulaire-template-article.png](https://i.postimg.cc/vm8cY5NJ/formulaire-template-article.png)

#### **Désignation**

- **Description :** Choisir un nom significatif pour désigner le modèle/template
- **exemple :** `ANTIBIOTIQUE`
- **Requis :** ✅

#### **Catgorie**

- **Description :** Choisir la catégorie qui sera appliqué à tous les articles héritant de ce modèle
- **exemple :** `MARCHANDISES`
- **Requis :** ✅

#### **Suivi du stock**

- **Description :** Cocher cette case ou pas si les articles heritant du modèle seront suivi en stock ou pas.
- **exemple :**
- **Requis :**

#### **PUV variable**

- **Description :** Cette case à cocher permet d'indiquer si les articles auront un prix de vente variable au moment de la facturation
- **exemple :**
- **Requis :**

### 2. Catégorie comptable

![form-template-art-compta.png](https://i.postimg.cc/TYRH5VmJ/form-template-art-compta.png)

#### Initialiser les comptes

Lorsque vous créée pour la première fois un template, vous avez la possibilité de l'associer à toutes les catégories comptables
disponible afin de définir pour chacune d'elles quelle est le compte du plan comptable et éventuellement les taxes applicable
Il suffit de cliquer sur le bouton **1** **`Associer aux catégories comptables`**

#### Editer le compte pour une catégorie comptable

Cliquez sur le pinceau d'edition (**2**) pour ouvrir accéder au champ d'édition du numéro de compte. Editez et valider votre modification; sa prise d'effet est immédiate.

#### Editer les taxes pour une catégorie comptable

A partir de l'icone contextuelle (**3**), ouvrez le menu et Choissez **`Gérer les taxes`**
![tab-taxe-template-art.png](https://i.postimg.cc/02P26BcX/tab-taxe-template-art.png)
Un tableau avec la liste des taxes applicable s'affiche, il ne vous reste plus qu'à cliquer sur le bouton `➕`pour associer
ou `➖` pour enlever une taxe

### 3. Catégorie tarifaire

![template-art-tarif.png](https://i.postimg.cc/xdKD4Z5Y/template-art-tarif.png)
Comme on l'a dit plus haut, il peut ếtre nécessaire de construire un modèle d'articles npour généraliser le paramétrage des remises.
Il suffi comme sur la capture ci-dessus, de remplir le formulaire et de cliquer sur le bouton `Enregistrer & Propager`

### 4. Associer un template à un article
