La vidéo Exapunks 1 est accessible par Youtube :
https://www.youtube.com/channel/UCIrWHCZhoqje6zHwDjEJVcw

# Tutorial 1

LINK 800
GRAB 200
LINK 800
DROP
HALT

**LINK**
*syntaxe : LINK <nom du link>*
L'Exa se déplace dans la zone de l'autre côté de <nom du link>
example : LINK 800

**GRAB**
*syntaxe : GRAB <nom du fichier>*
L'Exa ramasse un fichier appelé <nom du fichier>
exemple : GRAB 200

**DROP**
*syntaxe : DROP*
L'Exa lâche ce qu'il tenait

**HALT**
*syntaxe : HALT*
L'Exa est détruit

# Tutorial 2
LINK 800
GRAB 200
COPY F X
ADDI X F X
MULI X F X
SUBI X F X
COPY X F
LINK 800
DROP
HALT

**COPY**
*syntaxe : COPY <registre1> <registre2>*
L'Exa copie le contenu du <registre 1> dans le registre <registre 2>
exemple : COPY F X
copie la valeur en cours dans le fichier F dans le registre X

**ADDI**
*syntaxe : ADDI <registre 1> <registre 2> <registre 3>
L'Exa additionne les valeurs contenues dans <registre 1> et <registre 2> et place le résultat dans <registre 3>
exemple : ADDI X F X
place X + F dans X

**MULI**
*syntaxe : MULI <registre 1> <registre 2> <registre 3>
L'Exa multiplie les valeurs contenues dans <registre 1> et <registre 2> et place le résultat dans <registre 3>
exemple : MULI X F X
place X * F dans X

**SUBI**
*syntaxe : SUBI <registre 1> <registre 2> <registre 3>
L'Exa soustrait la valeur du <registre 2> à la valeur du <registre 1> et place le résultat dans <registre 3>
exemple : SUBI X F X
place X - F dans X
