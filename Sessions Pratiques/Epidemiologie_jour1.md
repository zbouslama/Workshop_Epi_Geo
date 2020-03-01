# Workshop “Introduction à l’épidémiologie spatiale”
## Session Pratique 1 - Bases de l’épidémiologie

### Télécharger les données 

Les données sont disponibles sur le lien suivant:
http://www.rage.tn/Fr/situation-en-tunisie_11_269

Commencer par les données 2012 sous le lien suivant:
http://www.rage.tn/upload/1453203233.pdf



### Transformation des tableaux PDF en tableau Excel


* Sélectionner les données contenues dans le tableau (ne pas inclure les titres des colonnes)
* Copier
* Ouvrir un Editeur de Texte (WordPad / Bloc Notes)
* Coller
* Enregistrer Sous Rage_année.csv
* Sélectionner le codage **unicode** : car les caractères arabes ne sont pas pris en compte pas avec codage ANSI
* Dans  Excel: Fichier - Ouvrir
* Ouvrir le fichier ### rage_année.csv
* Sélectionner **délimiteur**
* Sélectionner le délimiteur **tab + espace**
* Corriger le décalage dans les gouvernorats contenant un espace dans leur nom (ben arous, sidi bouzid ) ainsi que dans la dernière ligne (total)
* Réécrire les noms des gouvernorats en Français dans une nouvelle colonne
* Ajouter une colonne (primary key) pour permettre la jointure avec la table attributaire de la carte .shp
* Répéter pour toutes les années 2010 - 2016



