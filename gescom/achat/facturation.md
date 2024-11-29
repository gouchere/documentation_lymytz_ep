# Les factures d'achats

# Les entrées en stocks

## Contexte

Le but de cet article est de décrire comment matérialiser dans la solution `lymytz` les opérations d'achat, la mise en stock des produits achetés, la comptabilisation de la facture d'achat. Nous aborderons aussi les Etats de validation d'une facture, l'enregistrement des coûts supplémetaires et le règlement de la facture d'achat

> ### Sommaire
>
> - L'en-tête de la facture
> - Enregistrer/Modifier du contenu
> - Valider la facture
> - Comptabiliser une facture
> - Gérer le document de mise en stock du contenu
> - Enregistrer un règlement de la facture
> - Explorer les autres fonctionnalités de la facture
>   - Annuler l'écriture comptable
>   - Vérouiler
>   - Lettrer
> - Liste des factures
> - Rechercher une facture

> ##### <u>Prérequis</u>
>
> - [Catégories comptables](./../../donnee-de-base/com/categories-comptable.md)
> - [Fournisseurs](./../../donnee-de-base/fournisseur.md)
> - [Articles & conditionnements](./../../donnee-de-base/articles.md)

> [!NOTE]  
> En générale, l'accès à la fonctionnalité se fait en suivant le chemenin **`Commercial > Achats > Factures d'achat`**

![formulaire-facture-achat.png](https://i.postimg.cc/v8jyd8Ks/formulaire-facture-achat.png)

### 1. Formulaire générale

#### L'en-tête du document

#### Eregistrer/Modifier le contenu

#### **Désignation**

- **Description :** C'est un champ de saisie libre pour renseigner la disignation de votre article
- **exemple :** `DICLOFENAC 75MG/3ML`
- **Requis :** ✅
- **Remarque :** choisissez des dignation aussi significative que possible

> ##### Voir Aussi
>
> - [Les mouvements de stock](./../stocks/mouvement-de-stocks.md)
> - [Consulter le stock](./../stocks/consulter-les-stocks.md)
