[Table des matières](tableMatières.md)|[Historique](page1.md#Petite Histoire de Markdown)|[Cas d'utilisation](page1.md#Utilisation)|[Syntaxe](page2.md)|[Format](page2.md#FORMAT)|[Listes](page2.md#Des listes)|[Titres](page3.md#Les titres)|[Tableaux](page3.md#Les tableaux)|[Liens](page4.md#Liens)|[Images](page4.md#Images)|    
### Les titres
Il existe deux syntaxes différentes pour les titres :
* La méthode par **soulignement**
* La méthode par **dièses** (#)

La méthode par soulignement ne permet que **deux niveaux de titre**. Le titre doit être souligné par deux caractères (= ou -) ou plus.     
Le = équivaut au titre 1 alors que le - équivaut au titre 2.


    Titre 1
    ==

    Titre 2
    --


 La méthode par dièses est très simple, il suffit d'ajouter des # en début de titre sans limitation du nombre (il ne faut cependant pas dépasser les 7 #).       
 Un seul # pour le titre 1 (h1), deux # pour le titre 2 (h2) et ainsi de suite.       
 On peut également fermer les titres par un ou deux # mais c'est purement esthétique.


    # Titre 1
    ## Titre 2


### Les tableaux
Pour créer un tableau, il faut dessiner des colonnes en les entourant par des |.        
Le nombre de colonnes est défini dans la première ligne du tableau et il faut avoir le même nombre de colonnes pour chaque ligne, même si elles sont vides !     
La première ligne sera l'en-tête.     
La seconde va séparer l'en-tête du reste du tableau ainsi que définir l'alignement du texte dans les colonnes. Elle ne contient que des tirets - et des deux points : utilisés pour définir cet alignement.     
S'il n'y a pas de deux points ou juste un à gauche signifie que le texte s'alignera à gauche.     
Si la ligne - est entourée par deux :, le texte sera aligné au centre.   
Si un seul : est présent sur la droite, le texte s'alignera à droite.   


    | En-tête 1            | En-tête 2             | En-tête 3           |
    |:---------------------|:---------------------:|--------------------:|
    |Texte aligné          |Texte                  |Texte                |
    |à gauche              |      au centre        |             à droite|


| En-tête 1            | En-tête 2             | En-tête 3           |
|:---------------------|:---------------------:|--------------------:|
|Texte aligné          |Texte                  |Texte                |
|à gauche              |      au centre        |             à droite|


Cependant, bien que cette manière de faire soit plus lisible en mode édition, les | en début et en fin de ligne sont optionnels.   
Il est également possible d'imbriquer des éléments d'emphases ou de code dans les tableaux.   
Ensuite, il n'y a besoin que d'un seul - pour séparer l'en-tête du corps du tableau.    


    En-tête 1 | En-tête 2 | En-tête 3
    -|:-: |-:
    Texte| Texte| Texte à
    à gauche|**gras et centré** |*droite et italique*


En-tête 1 | En-tête 2 | En-tête 3
-|:-: |-:
Texte| Texte| Texte à
à gauche|**gras et centré** |*droite et italique*
