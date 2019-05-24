page2

### FORMAT

Il existe deux syntaxes pour les titres. Le résultat sera le même quelque soit la méthode employée. Essayez simplement d'en choisir une et de vous y tenir afin de rester cohérent.


#### Les paragraphes

Pour afficher un paragraphe, sautez deux lignes et rédigez votre texte. Un seul saut de ligne correspond à un retour chariot (retour à la ligne) et non pas à un changement de paragraphe.


Pour afficher un paragraphe on utilise le balisage ```<p>```

``` <p>Un paragraphe</p>```

##### Saut de ligne simple

Effectuer un saut de ligne simple dans votre texte markdown n’aura aucun effet quand vous l'exporter en HTML.
Sauf si vous terminez votre ligne par un double espace (ou plus que ça).
Un retour chariot sera alors exporté.

Vous taper:

Ligne sans espace à la fin
Ligne avec 2 espaces à la fin 
Troisième ligne

Vous obtenez le Résultat affiché dans le navigateur comme sui:

Ligne sans espace à la fin Ligne avec 2 espaces à la fin
Troisième ligne

Terminer une ligne avec deux ou plusieurs espaces:
La première ligne se termine par trois espace après la virgule, la deuxième ligne fini par un point final.

Par exemple vous taper:

Les roses sont rouges,
les violettes sont bleues.

Vous obtenez le Résultat affiché dans le navigateur comme sui:

Les roses sont rouges,
les violettes sont bleues.

En résumer:
Pour effectuer un saut de ligne à l'intérieur d'un paragraphe il faut introduire 2 ou davantage de caractères espaces à la fin de la ligne (avant le saut à la ligne).

#### Mise en forme du text

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
* Troisième article
* Quatrième article

Liste imbriquée

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

##### Code incorporé

Voici du code incorporé.

Pour un bloc de code ; faire une tabulation ou
~~~html
<a href=“#”>Du code</a>
~~~

<a href="#">Du code</a>






