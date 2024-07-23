# Identifier et supprimer les opérations mal lettrées

## Contexte

Lors de l'opération de lettrage automatique des comptes, il arrive pour des raisons non encore totalement identifiées que les lettres afffecté à des lige d'écriture ne se soldent pas. En d'autres termes, l'ensemble des opérations **débits-crédits** du compte **4010111** portant la lettre **A** a un solde différent de **0**. <br />
L'une des conséquence immédiate constaté est que celà fausse l'intéprétation des résultats de la **balance** du compte en question et celle du **grand livre lorsqu'on filtre sur les opérations non lettrées**. Les solde sont différents.

## Identifier les opérations

Il faut tout d'abord se rendre sur la page de lettrage des comptes

> **Comptabilité & Finance > Comptabilité Générale > Lettrage des comptes** <br/>

![ecran-lettrage.png](https://i.postimg.cc/C5kjPQH7/ecran-lettrage.png)

Comme indiqué sur la capture ci-dessus,

> 1. Selectionnez le compte à vérifier
> 2. Ensuite l'exercice
> 3. Filtrez les opération déjà lettrées

A partir de là, vous comme sur la capture ci-dessous, déroulez les autres options et choisissez (**Filtrer les op. mal lettrées**)<br />
![lettrage-selection-op-mal-lettree.png](https://i.postimg.cc/9FThbY3f/lettrage-selection-op-mal-lettree.png) <br/>

Une modale s'affichera pour vous montrer les opéraion dont le solde par lettre est différent de 0.
![lettrage-modale-op-mal-lettre.png](https://i.postimg.cc/8zSV0fDm/lettrage-modale-op-mal-lettre.png) </br>
Il ne vous reste plus qu'à cliquer sur le bouton **Annuler les lettres** pour **délettrer** ces opérations

> [!IMPORTANT]
> Il sera peut-être nécessaire de repéter l'opération de la capture d'écran numéro 2 plusieurs fois. Car le nombre d'éléments sur la fenêtre modale dépend de la pagination
