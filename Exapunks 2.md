La vidéo Exapunks 2 est accessible par Youtube :

https://github.com/titimoby/Exapunks/blob/master/Exapunks%202.md

#Tutorial 3
```
XA:
LINK 800
LINK 799
GRAB 199
COPY F M
COPY F M
WIPE
HALT

XB:
LINK 800
LINK 800
MAKE
COPY M X
COPY M F
COPY X F
DROP
HALT
```
**WIPE**

*syntaxe : WIPE*

L'Exa efface le fichier qu'il porte

**MAKE**

*syntaxe : MAKE*

L'Exa crée un fichier et le porte

#Tutorial 4
```
LINK 800
GRAB 200
COPY F X
WIPE
LINK 800
MAKE
MARK LOOP
COPY X F
SUBI X 1 X
TEST X = -1
FJMP LOOP
DROP
HALT
```
**MARK**

*syntaxe : MARK <label>*

Inscrit un label à cet endroit pour un usage ultérieur avec les commandes de sauts

**TEST**

*syntaxe : TEST <condition>*

Teste la condition indiquée et stocke :
- 0 dans le registre T si elle est fausse
- 1 dans le registre T si elle est vraie

example : TEXT X == 12

teste si le registre X est égal à 0.

**JUMP**

*syntaxe : JUMP <label>*

Saute dans le code à l'emplacement du <label> et poursuis l'exécution à partir ce point.

**TJMP**

*syntaxe : TJMP <label>*

Saute dans le code comme JUMP mais uniquement si le registre T contient une valeur différente de 0 (la plupart du temps 1 si cela provient d'une instruction TEST)

**FJMP**

*syntaxe : FJMP <label>*

Saute dans le code comme JUMP mais uniquement si le registre T contient la valeur 0
