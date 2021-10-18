# 📎 Avoir

Il y a 2 types d'avoir :

* Les [avoirs d'annulation](realiser-un-avoir.md#avoir-dannulation-dune-facture) de facture
* Les [avoirs "simples"](realiser-un-avoir.md#avoir-simple).

## Avoir d'annulation d'une facture.

Il n'est pas possible de supprimer une facture validée, pour des raisons légales et fiscales.

Si une facture doit être supprimée, il faudra donc l'annuler par un avoir, comme expliqué [dans cet article](les-factures-en-detail/modifier-supprimer-ou-annuler-une-facture.md#annulation).

## Avoir "simple".

Il peut vous arriver de devoir réaliser un avoir pour des travaux non réalisés, ou non acceptés, ou pour une remise exceptionnelle, etc.

### Réaliser un avoir direct

* Ouvrez la liste des factures,
* Cliquez sur "Nouvelle facture", puis choisissez "Facture d'avoir".
* Lisez le petit texte d'information qui résume le contenu de cet article, et cliquez sur "Créer un avoir direct":
* Une fois la facture créée :
  * Créez un titre avec une quantité -1, et saisissez vos lignes d'avoir normalement dans ce titre,\
    **ou**
  * Saisissez vos lignes d'avoir en mettant les quantités en négatif,\
    **ou**
  * Saisissez vos lignes d'avoir en mettant les prix en négatif.\

* Une facture dont le total hors taxe est négatif est considéré comme un avoir par le logiciel.

### Réaliser un avoir à partir d'une facture

#### En copiant la facture de travaux

Si vous avez de nombreuses lignes à déduire, copiez la facture, supprimez les lignes qui ne sont pas  modifiées, et saisissez des quantités ou des prix négatifs sur les lignes à modifier. 

Cela vous évitera de ressaisir de nombreuses lignes de facture.

#### En créant une situation de travaux.

Une autre méthode est de créer une situation de travaux. Cette méthode sera très appréciée des architectes et maîtres d'oeuvre, car elle donne une vision plus précise des travaux modifiés :

* Ouvrez la facture,
* A droite de la page, cliquez sur "Nouvelle situation".
* Une nouvelle facture est créée, et son montant est à 0 euros.
* Créez un nouveau titre, par exemple "Travaux non effectués".
* Sélectionnez une ligne de la facture, et dupliquez-la.
* Déplacez-la nouvelle ligne dans le titre "Travaux non effectués".
  * Si la ligne doit être totalement annulée (pas exécutée du tout), passez simplement sa quantité en négatif.
  * Si la ligne a été réalisée partiellement, annulez-la en passant sa quantité en négatif, dupliquez-la , et mettez la quantité réellement exécutée (ou un autre prix unitaire).

