# exercice Git 

> A chaque étape, afficher le status (git status) 

  * 1\. Aller dans sites/lab/exerciceGit
  * 2\. Créer un nouveau dossier "exercice2"
  * 3\. L'initialiser avec Git
  * 4\. Créer 5 fichier, de Fichier1 à Fichier5
  * 5\. Faire un commit avec le message "création de fichiers"
  * 6\. Modifier le Fichier1 du contenu pris où vous voulez (voir lorem ipsum)
	* A. regarder la difference entre la modification et le dernier commit (voir git diff)
  * 7\. Faire un commit
  * 8\. Faire pareil pour tout les fichiers (etape 6 et 7)
  * 9\. Aficher les commits
  * 10\. Créer un branche appelée "undo"
    * Aller sur cette branche
    * Annuler le dernier commit (voir git reset)
    * afficher le status (=etat revenu avant le commit!, paragraphe toujour présent)
    * re-commiter le fichier5 avec un autre message
    * Annuler le dernier commit et les changement sur le fichier( voir git reset --hard, paragraphe absent)
    * git log
    * Rajouter un pargraphe à Ficher1
    * afficher le status et la diff
    * commiter 
  * 11\. Créer un repository sur github
	* créer une remote entre git local et github
	* pusher votre travail sur github "master et undo"
	* modifier sur github le fichier 5 avec un paragraphe sur branche undo
	* modifier fichier2 sur votre ordinateur en local
	* commiter
	* pusher votre travail 
	* merger votre travail sur la branche master
	* supprimer branch undo
