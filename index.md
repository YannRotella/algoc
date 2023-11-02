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
   - Lecture codes de Keccak en [python](tds/KeccakPython.py) et en [C](tds/KeccakC.c)
   - Comparer les temps d'éxécution pour environ 10 000 éxécutions de la permutation interne de Keccak. Expliquer.
   - Faire un programme qui calcule la factorielle d'un nombre rentré en argument dans le bash.
   - Faire un programme qui calcule la factorielle et dit si un nombre est premier, en séparant les fonctions dans des fichiers séparés (3).
   - Ajouter l'exponentiation rapide à factorielle, en améliorant votre programme qui pourrait utiliser le théorème de Fermat si le modulo est premier. On utilisera la fonction est_premier utilisée précédemment.
   - Dans l'autre programme, rajouter une fonction qui calcule les coefficients binomiaux, en utilisant le programme factorielle de l'autre fichier. 
   - Utiliser la technique ifndef define pour gérer les problèmes.
   - Créez votre propore librairie (dynamique et statique) contenant l'exponentiation rapide modulaire.
   - Vérifiez que vous arrivez à les utiliser.


#### 13 décembre 

**Makefile, GMP et factorisations**
   - Reprenez le travail précédent, avec une bibliothèque contenant l'exponentiation rapide, un fichier séparé contenant le programme qui vérifie si un nombre est premier et un fichier main séparé et créez le makefile qui vous permet de créer le fichier éxécutable.
   - Installez GMP et vérifiez que vous pouvez l'utiliser.
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


  

