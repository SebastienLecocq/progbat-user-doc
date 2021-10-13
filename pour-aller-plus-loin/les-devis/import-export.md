# Import - Export de devis / DPGF

## Import de DPGF et devis au format Excel

Le logiciel permet d'importer le contenu d'un DPGF, d'un DQE, ou d'un devis au format Excel, pour éviter des ressaisies fastidieuses et des risques d'erreur de quantités par exemple.



### :digit_one: Préparez votre fichier Excel

Le fichier Excel doit être "formaté", c'est à dire que les colonnes doivent respecter un ordre précis :

*   Ouvrez le DPGF (le DQE, le devis) dans Excel ou votre logiciel de tableur


*   **Ne conservez que les lignes du contenu**, et supprimez les entêtes (nom du chantier, références diverses, etc...), les lignes du total (THT, TVA, TTC), et lignes d'espacement superflues.:warning:Le fichier ne doit contenir aucune formule, aucun "chaînage".

    * Une ligne avec un numéro de ligne, sans quantité et sans unité sera considérée comme un titre (une tranche) ou comme un sous-titre (sous-tranche)
    * Une ligne sans numéro de ligne, sans quantité et sans unité sera considérée comme un commentaire
    * Les autres lignes seront considérées comme des lignes d'ouvrage


* Organisez les colonnes en respectant l'ordre suivant (peu importe le nom des colonnes) :

| N°  | Désignation                                  | Quantité | Unité | PUHT |
| --- | -------------------------------------------- | -------- | ----- | ---- |
| 1   | Gros oeuvre                                  |          |       |      |
| 1.1 | Gros béton XF1 C20/25 sous semelles filantes | 4        | m³    |      |

{% hint style="info" %}
* La première colonne **N°**, même vide, est obligatoire.
* La dernière colonne PUHT est facultative.
{% endhint %}



### :digit_two: Enregistrez au format .csv

* Sur Excel, cliquez en haut à gauche sur "Fichier"
* Puis sur "Exporter"
* Puis "Modifier le type de fichier"
* Puis "CSV (séparateur : point-virgule)(\*.csv)"
* Et enfin, cliquez sur "Enregistrer-sous".

![](<../../.gitbook/assets/capture (7).png>)



### :digit_three: Importez le fichier

*   Créez un [nouveau devis](nouveau-devis/), puis ouvrez l'onglet "Lignes"


*    Cliquez à droite de la page sur le bouton "Import/Export", et choisissez "Importer le contenu"


*   Sélectionnez le fichier CSV que vous venez d'enregistrer


*   Cliquez sur "Analyser"


*   Vérifiez, et éventuellement modifiez les types et les niveaux de titres et lignes


*   Supprimez les lignes inutiles que vous n'auriez pas supprimées sur Excel (sous-totaux, lignes hors contenu, ....)


*   Validez l'importation.



{% hint style="warning" %}
**Si votre devis (sous le logiciel) contient des lignes, l'import du fichier remplacera totalement le contenu du devis.**
{% endhint %}

## Export de devis au format Excel

Particulièrement pour les appels d'offre, il est généralement demandé de répondre sur le fichier Excel original du DPGF.

Le logiciel permet d'exporter le contenu d'un devis au format Excel, pour simplifier la transcription de votre chiffrage sur le DPGF original :

* Cliquez à droite de la page sur le bouton "Import/Export", et choisissez "Exporter le contenu"
* Choisissez le format d'export (Excel par défaut)
* Choisissez l'ordre des colonnes
*   Et exportez :slight_smile:



## ****:bulb: **Astuce**

#### **Récupération des données d’un ouvrage sans modifier son libellé**

![](../../.gitbook/assets/menu-ligne-lien.png)

Une fois l'import de devis ou DPGF effectué, chiffrez-le rapidement et efficacement en "liant" chaque ligne du devis à un ouvrage déjà présent en bibliothèque. Le libellé importé ou saisi sera conservé, mais il récupérera les données de chiffrage et comptables de l'ouvrage "lié".

