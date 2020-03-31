DAMASCENO Thomas
BURNO Loic

#manuel

###la commande WHICH

which retourne le chemin des fichiers qui seraient exécutés dans l'environnement courant si ses arguments avaient été donnés comme commandes dans un interpréteur de commandes strictement conforme à POSIX.
Pour ce faire, which cherche dans la variable PATH les fichiers exécutables correspondants aux noms des arguments. 

###Chercher dans le fichier
il faut utiliser les touches /x ou ?x où x est le mot à rechercher
puis on peut utiliser les touches b et n pour naviguer entre les éléments trouvés.

###quitter le manuel 
il suffit d'appuyer sur la touche q

###man 6 intro
cette commande affiche la page d'introduction de la section 6 du manuel

#Navigation

* cd /var/log/ 	pour accèder au dossier log du dossier var
* cd .. 	revenir en arrière dans l'arborescence
* cd 		revient au dossier personnel
* cd - 		pour revenir au dossier précédent

#Supression de fichiers et dossiers :
* rm 		pour supprimer les fichiers
* rmdir		pour supprimer les dossiers
* rm -r		supprimer les dossiers

#Affichage de l'heure
* date 		Affiche la date actuelle, peut être formatée avec +"X" ou X est la chaine de charactère de formattage

#Où se situe les programmes de commande
les programmes de commande comme ls se situent dans le répertoire /bin/

#la commande ls
la commande ls x affiche le contenu du repertoire (x étant le nom du répertoire, si x est null, le répertoire courant sera afficher)
la commande la est similaire mais affiche les dossiers et fichiers cachés
ll est un alias pour l -alF qui affiche le contenu du répertoire plus en détail

#path du dossier courant
* pwd		affiche le chemin du dossier courant

#echo et >
* echo 'yop' > plop écrit yop dans le fichier plop
* file 		affiche le type du fichier
* ln		duplique un fichier
* ln -s 	crée un lien symbolique vers un fichier, si l'original est détruit le lien est brisé

#les commandes head et tail
* head -n x	permet d'afficher les x premières lignes d'un fichier texte
* tail -n x	permet d'afficher les x dernières lignes d'un fichier texte
avec l'opérateur | on peut appliquer les fonctions head et tail sur le résultat

#more or less
* more 		permet de faire défiler du texte petit à petit
* less		more en mieux, permet de scroll 

#le fichier /etc/passwd
ce fichier contient la liste de tout les utilisateurs, réels et virtuels
cut -d: -f1 /etc/passwd affiche seulement les noms d'utilisateurs 
sort permet de trier alphabétiquement

#utilisateurs
* users		affiche la liste des utilisateurs connectés







