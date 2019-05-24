| [Table des matières](tableMatieres.md) | [Historique](page1.md#petite-histoire-de-markdown) | [Cas d'utilisation](page1.md#utilisation) | [Syntaxe](page2.md#Syntaxe) | [Format](page2#Format) | [Listes](page2.md#Listes) | [Titres](page3.md#Titres) | [Tableaux](page3.md#Tableaux) | [Liens](page4.md#Liens) | [Images](page4.md#Images) |

### FORMAT

Il existe deux syntaxes pour les titres. Le résultat sera le même quelque soit la méthode employée. Essayez simplement d'en choisir une et de vous y tenir afin de rester cohérent.


#### Les paragraphes

Pour afficher un paragraphe, sautez deux lignes et rédigez votre texte. Un seul saut de ligne correspond à un retour chariot (retour à la ligne) et non pas à un changement de paragraphe.



#### Mise en forme du texte

Pour mettre en évidence un texte ou l'entoure de *, ~, ou _ selon le changement que l'on souhaite apporter.


    italique = *italique*
    gras = **gras**
    italique gras = ***italique gras***
    b̶a̶r̶r̶é̶ = ~~barré~~
    s͟o͟u͟l͟i͟g͟n͟é͟ = __souligné__
    italique souligné = __*italique souligné*__
    gras souligné = __**gras souligné**__


##### Blocs de citation

Tapez un chevron fermant > ensuite une espace et le texte du paragraphe.

Voici un exemple de texte normal.

> Voici un exemple de texte en bloc de citation et en paragraphe avec indentation. Le décalage à gauche persiste tant qu'on fait des retours chariot.

    > Voici un exemple de texte en bloc de citation et second paragraphe avec indentation. Le décalage à gauche persiste tant qu'on fait des retours chariot.

Voici un exemple de retour en texte normal.

##### Code incorporé

Voici du code incorporé.

Pour afficher du code en tant que tel, voici deux solutions :
* Quatre espaces avant le code 
* Trois tildes (~) avant et après + le mot clé html avant le code
~~~html
<a href=“#”>Du code</a>
~~~
donne : 

<a href="#">Du code</a>


#### Des listes

Vous pouvez organiser les éléments en listes ordonnées et non ordonnées.

##### Listes Ordonnées

Pour créer une liste ordonnée, ajoutez des éléments de ligne avec des nombres suivis de points. Les numéros ne doivent pas nécessairement être dans l’ordre numérique, mais la liste doit commencer par le numéro un.

1. Premier article
2. Deuxième élément
3. Troisième article
4. Quatrième point

##### Listes non ordonnées

Pour créer une liste non ordonnée, ajoutez des tirets (-), des astérisques (*) ou des signes plus (+) devant les éléments de campagne. Indenter un ou plusieurs éléments pour créer une liste imbriquée

```
- Premier article	
- Deuxième article
- Troisième article
- Quatrième article
```
```
* Premier article
* Deuxième article
* Troisième article
* Quatrième article
```
```
* Premier article
- Deuxième article
+ Troisième article
* Quatrième article
```
* Premier article
* Deuxième article


##### Liste imbriquée

* Premier niveau de cette liste.
     * Pour créer un second niveau, ajoutez deux espaces avant l’astérisque ou le numéro.

- Premier article
- Deuxième article
- Troisième article
    - Article en retrait
    - Article en retrait
- Quatrième article

- Premier article
- Deuxième article
- Troisième article
    - Article en retrait
    - Article en retrait
- Quatrième article


##### Checkbox
Pour créer une liste des tâches, il faut insérer un espace et le faire suivre de [ ] , pour cocher une case il faite faire espace [x]


- [x] Format titre
- [ ] Push un commit à GitHub
- [ ] pull request
