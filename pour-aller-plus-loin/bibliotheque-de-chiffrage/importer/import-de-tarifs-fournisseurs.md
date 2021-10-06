# Import de tarifs fournisseurs

Le logiciel permet d’importer vos tarifs fournisseurs, et économiser de longues heures de saisies.

{% hint style="info" %}
**Importez de préférence uniquement le tarif de votre fournisseur principal**

* Imaginez que vous importiez le tarif de “Point P” et de “Matériaux Réunis”.
* Il est très probable que ces deux distributeurs proposent exactement les mêmes produits, par exemple la plaque de BA13 Placo, ou le sac de ciment Lafarge.
* Mais ces produits n'ayant pas la même référence, ni exactement le même libellé chez chaque fournisseur, vous aurez des doublons dans votre base articles. Vous aurez dans ce cas 2 fois la plaque de plâtre et 2 fois le sac de ciment.
* Importez donc uniquement le tarif de votre fournisseur principal, et saisissez les autres tarifs manuellement dans chaque fiche article.
{% endhint %}

## **Préparez votre fichier**

* Le fichier doit être au format Excel \(.xlsx\), ou csv \(.csv\).
* Ouvrez le fichier dans votre tableur. 
* Vérifiez les points suivants :
  * La première ligne du fichier doit contenir le nom des colonnes. \(recommandé mais pas obligatoire\)
  * Chaque ligne du fichier doit contenir un article.
  * Aucune ligne ne doit être vide.
  * Il ne doit pas y avoir 2 \(ou plusieurs\) fois la même référence article dans le fichier.
  * Les colonnes contenant des valeurs \(prix\) doivent être au format nombre, et ne contenir aucun symbole monétaire :
    * 1234.56  - OK
    * 1234,56  - OK
    * 1234.567  - OK
    * 1 234.56  - OK
    * **1 234.56 €  - NON**
    * **€ 1234.56  - NON** 
  * Si la colonne "Prix de vente" est absente ou vide, un prix sera calculé en appliquant la marge que vous avez définie dans vos paramètres "Entreprise".
  * Si la colonne "Taux de TVA" est absente ou vide, c'est le taux de TVA sur achats par défaut qui sera appliqué \(20% pour la France\).  _Le taux de TVA n'est pas appliqué aux ouvrages, car il est défini au niveau du devis._
* Après avoir vérifié votre fichier, enregistrez-le.

## Importez votre fichier

* Ouvrez la fiche de votre fournisseur dans le logiciel.
* En haut à droite de la page, cliquez sur "Importer un tarif".

![](../../../.gitbook/assets/capture%20%282%29.png)

* Recherchez le fichier que vous avez vérifié.
* Précisez si la première ligne de votre fichier contient des titres \(conseillé\)
* Généralement, vous n'avez pas à modifier le séparateur et l'encodage du fichier, sauf éventuellement si le fichier est issu d'un logiciel américain.
* Cliquez sur "Analyser le fichier".
* Faites correspondre les colonnes disponibles \(colonne de gauche\) avec les colonnes de votre fichier.

![](../../../.gitbook/assets/capture%20%283%29.png)

* Cliquez sur suivant.
* Après vérification des données, Importez le fichier.

## Mise à jour d'un tarif fournisseur

Lorsque vous recevrez le nouveau tarif de votre fournisseur, répétez exactement la même procédure.

* Tous les prix des références existantes seront mis à jour. 
* Toutes les nouvelles références seront ajoutées.

## Recommandations

* Prenez le temps nécessaire à parfaitement vérifier votre fichier, et surtout les données numériques. La moindre erreur rejettera l’importation.
* Certaines erreurs pourraient ne pas être détectées, et endommager votre fichier fourniture avec des données erronées. Soyez attentifs et vigilants…
* **Importez de préférence uniquement le tarif de votre fournisseur principal .**
  * Imaginez que vous importiez le tarif de “Point P” et de “Matériaux Réunis”.
  * Il est très probable que ces deux distributeurs proposent exactement les mêmes produits, par exemple la plaque de BA13 Placo, ou le sac de ciment Lafarge.
  * Mais ces produits n'ayant pas la même référence, ni exactement le même libellé chez chaque fournisseur, vous aurez des doublons dans votre base articles. Vous aurez dans ce cas 2 fois la plaque de plâtre et 2 fois le sac de ciment.
  * Importez donc uniquement le tarif de votre fournisseur principal, et saisissez les autres tarifs manuellement dans chaque fiche article.

## En cas de doute

Vous n’avez pas les compétences pour formater vos fichiers, ou vous avez peur de faire une mauvaise manipulation ?

* Contactez votre hotline pour faire réaliser l'import de votre tarif fournisseur \(sur devis\).



