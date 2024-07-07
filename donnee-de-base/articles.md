# Gestion des articles

## Contexte

La gestion des articles est le point d’entrée de la plupart des fonctionnalité de l’ERP, en de manière plus générale, de la plupart des systèmes de gestion.
Bien réussir le paramétrage de ses articles peut réellement accroitre de manière positive votre expérience de travail. Nous verrons ici selon l’objectif visé, les informations clés à paramétrer pour un fonctionnement optimale
Les points que nous évoquerons dans ce document visera à faciliter la prise en main des objectifs suivants:

> ### Sommaire

> - Informations générales
> - Rechercher un article
> - Gérer les unités de stockage
> - Paramétrage des points de stockage
> - Les prix
> - Paramétrage comptable
> - Paramétrer les taxes
> - Le prix de revient

> [!NOTE]  
> En générale, l'accès à la fonctionnalité se fait en suivant le chemenin **`Données de bases > Article > Articles`**

![formulaire-main-article.png](https://i.postimg.cc/FHbndQ18/formulaire-main-article.png)

### 1. Formulaire générales

#### **Désignation**

- **Description :** C'est un champ de saisie libre pour renseigner la disignation de votre article
- **exemple :** `DICLOFENAC 75MG/3ML`
- **Requis :** ✅
- **Remarque :** choisissez des dignation aussi significative que possible

#### **Référence article**

- **Description :** Champ de saisie libre
- **exemple :** `AIN0013`
- **Requis :** ✅
- **Remarque :** En générale, on choisit un code court et unique

#### **Référence article**

- **Description :** Champ de saisie libre
- **exemple :** `AIN0013`
- **Requis :** ✅
- **Remarque :** En générale, on choisit un code court et unique

#### **Référence**

- **Description :** Champ de saisie libre
- **exemple :** `AIN0013`
- **Requis :** ✅
- **Remarque :** En générale, on choisit un code court et unique

#### **Modèle**

- **Description :**La notion de modèle ou encore template de saisie permet de rattacher l'article à un modèle de saisie et donner ainsi la possibilité d'effectuer des modification groupé sur tous les articles du même modèle
- **exemple :** `MEDICAMENTS`
- **Requis :** _Non requis_
- **Note :** [gérer les modèles d'articles](modele_article?path=donnee-de-base/modele_article.md)

#### **Catégorie**

- **Description :** Choisir la catégorie la plus pertinente pour l'article. Le choix de la catégories d'articles peut derteminer les opérations possible dessus
- **exemple :** `MARCHANDISE`, `PRODUIT FINI`, `PRODUIT SEMI FINI`, `MATIERE PREMIERE`, `SERVICE`
- **Requis :**✅
- **Note :**

#### **Famille**

- **Description :** C'est l'élément de groupage de premier niveau des articles,
- **exemple :** _au choix_
- **Requis :**✅
- **Note :** La création des [familles d'aticles](famille_article?path=donnee-de-base/famille-d-article.md) est un prérequis à la création des articles

#### **Type de service**

- **Description :** Cette information permet de préciser le type de service auquel est rattaché l'article, il vient en compléter la catégorie précédement choisi. Par exemple un article de la catégorie `SERVICE`
- **Requis :**
- **Remarque :**

#### **P.U.A TTC**

- **Description :** Si vous cochez cette case, vous indiquez par là que le prix unitaire d'achat fourni à l'opération d'achat est un prix incluant déjà les taxes, la conséquence est que sur la future facture d'achat de cet article, la taxe sera indiqué, mais n'affectera pas le montant ttc.

#### **P.U.V TTC**

- **Description :** Si vous cochez cette case, vous indiquez par là que le prix unitaire de vente fourni à l'opération de vente est un prix incluant déjà les taxes, la conséquence est que sur la future facture de vente de cet article, la taxe sera indiqué, mais n'affectera pas le montant ttc.

#### **Suivi du prix de revient**

- **Description :** Vous devez activer ce paramètre si vous souhaitez surveiller les variations importante du prix de revient de l'article
- **Note :** vous devez en complément préciser à partir de quelle différence il y a inquiétude potentielle

#### **Ecart PR**

- **Description :** Si l'option précédente a été coché, on indique ici la différence entre deux valeurs calculées du prix de revient qui peut poser problème.
- **Requis :**

#### **P.U.V variable**

- **Description :** Cette option vous permet d'indiquer que le prix à la vente de l'article peux être modifié.
- **Requis :**
- **Remarque :** Ce paramétrage est pratique pour les contextes où c'est le commerciale au moment de la vente qui négocie le prix.

#### **Valorisation PR**

- **Description :** On indique ici comment souhaite valoriser le prix de revient de l'article
- **exemple :** `Cout moyen pondere`, `FIFO`

#### **Classe**

- **Description :** Les classes statistiques sont un autres critères de groupage des articles. Ils sont en particulier utilisé pour les journaux de vente ou pour d'autres rapports de production
- **Requis :** _Non requis_
- **Remarque :**

#### **Description**

- **Description :** Champ de saisie libre, utilisé si vous voulez apporter d'avantages d'informations sur l'article.
- **Requis :** _Non requis_

### 2. Conditionnements

![formulaire-conditionnement.png](https://i.postimg.cc/zX6V5rpZ/formulaire-conditionnement.png)

### 3. Stockages

![ksnip-20240707-145511.png](https://i.postimg.cc/HsM9Ht56/ksnip-20240707-145511.png)

### 4. Catégorie tarifaire

![article-cat-tarif.png](https://i.postimg.cc/CMXdj08P/article-cat-tarif.png)

### 5. Comptabilité

![article-compta.png](https://i.postimg.cc/G2LkYCZg/article-compta.png)

#### Référence avec

> - Les familles d'articles
> - Les codes barres
> - Les templates d'articles
> - Les unités de mesures
> - Les classes statistiques
