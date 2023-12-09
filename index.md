---
title: Home
---

## Info pratiques

Cours & TD le mercredi de 13h50 à 17h50, salle G207 ou G203 Bâtiment Sophie Germain

**Chargés de cours et TP :** [Yann Rotella](https://rotella.fr/) et Michaël Quisquater

**Serveur pour les TPs:** [https://jupyter.ens.uvsq.fr/](https://jupyter.ens.uvsq.fr/)

## Calendrier des trois dernières séances

#### 6 décembre 

**Compilation, fichiers séparés, librairies**
   - [Document](tds/CompilationBasiqueC.pdf)
   - Lecture codes de Keccak en [python](tds/KeccakPython.py) et en [C](tds/KeccakC.c)
   - Comparer les temps d'éxécution pour environ 10 000 éxécutions de la permutation interne de Keccak. Expliquer.
   - Faire un programme qui calcule la factorielle d'un nombre rentré en argument dans le bash.
   - Faire un programme qui calcule la factorielle et dit si un nombre est premier, en séparant les fonctions dans des fichiers séparés (3).
   - Ajouter l'exponentiation rapide à factorielle, en améliorant votre programme qui pourrait utiliser le théorème de Fermat si le modulo est premier. On utilisera la fonction est_premier utilisée précédemment.
   - Dans l'autre programme, rajouter une fonction qui calcule les coefficients binomiaux, en utilisant le programme factorielle de l'autre fichier. Mettez les includes nécessaires dans les .h.
   - Utiliser la technique ifndef define pour gérer les problèmes.
   - Installez la bibliothèque GMP et lancez un programme pour vérifier que vous arrivez à l'utiliser.


#### 13 décembre 

**Makefile, GMP et factorisations**
   - Reprenez l'exponentiation rapide et transformez le programme pour que cela fonctionne sur GMP. Vérifiez avec la fonction de GMP.
   - Créez un makefile permettant de compiler votre programme avec la seule instruction make. 
   - Programmez la recherche de cycles sur la suite de Syracuse $u_0 = a$ et $u_{n+1} = \frac{u_n}{2}$ si $u_n$ est pair et $u_{n+1} = 3u_n + 1$ sinon.
   - Programmez la recherche de collisions sur Keccak en réutilisant le programme du début.
   - Programmez l'algorithme de Miller Rabin.
   - Programmez la méthode rho de pollard.

   
#### 20 décembre 

**Git et méthodes de factorisation**
   - Créez un compte Github et mettez vous en binôme/trinôme de projet.
   - Initialisez un dépôt. 
   - Mettez dans ce dépot un dossier contenant un fichier .bib et un fichier .tex avec des noms adaptés pour vos projets.
   - Mettez dans ce dépot un autre dossier contenant un fichier fact.c contenant l'ensemble des fonctions liées à la factorisation et un fichier main.c ainsi qu'un fichier makefile.
   - Faites en sorte que tout compile et produise un éxécutable.
   - Faites ensuite à plusieurs, en faisant des add, commit, pull et push, les programmes suivants (vous pouvez séparer les tâches).
   - Programmez la méthode p-1
   - Programmez la méthode p+1
   - Comparer avec les entiers suivant:
      - 1267650600228402790082356974917
      - 2177241218019392284455749961185783753335013327591
      - 199214358783833785496649131630759414803916321139456200129431155042143170897974614023327
      - 6500836418678143176619908800773996927084289993776850414594757469264912497841920022968113
   - Programmez la méthode de Pohlig Hellman sur
      - 199214358783833785496649131630759414803916321139456200129431155042143170897974614023327


  

