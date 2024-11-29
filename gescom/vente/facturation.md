# Les factures de ventes

## Contexte

Le but de cet article est de décrire comment matérialiser dans la solution `lymytz` les opérations de ventes, la livraison des stocks de produits vendus, la comptabilisation de la facture de vente. Nous aborderons aussi les Etats de validation d'une facture, l'enregistrement des coûts supplémetaires et le règlement de la facture de vente

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
>   - Modifier l'en-tête de la facure
>   - Les commissions
> - Liste des factures
> - Rechercher une facture

> ##### <u>Prérequis</u>
>
> - [Les catégories comptables](./../../donnee-de-base/com/categories-comptable.md)
> - [Les clients](./../../donnee-de-base/client.md)
> - [Les points de vente](./../../donnee-de-base/com/points-de-vente.md)
> - [Créneaux horaires](./../../donnee-de-base/com/creneaux.md)
> - [Les modes de règlement](./../../donnee-de-base/compta/mode-de-paiement.md)
> - [Articles & conditionnements](./../../donnee-de-base/articles.md)

> [!NOTE]  
>  En générale, l'accès à la fonctionnalité se fait en suivant le chemenin **`Commercial > Achats > Factures de vente`**

### 1. Formulaire générale

![formulaire-facture-vente.png](https://i.postimg.cc/ZKw4DFhw/formulaire-facture-vente.png)

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
> - Consulter le listing de vente
> - Consulter les journaux de vente
> - La synthèse des vente + marges
> - Le bon de livraison
> - Les pièces de règlements
> - Règlements par acomptes
> - Les autres rapports de ventes
> - Classements par vendeur
> - Classement par client
> - classement par articles
