# Exercice Git 

  * Aller dans le projet de l' exercice précèdant (dossier crée avec exercice 3)
  * Effacer la branche "menu".
  * Créer une branche appelée "section" 
  * Aller dedans
  * Modifier index.html
	* Ajouter une section (`<section> </section>`)
	* Dans la section, Ajouter un titre de niveau 2 (`<h2> Votre titre</h2>`)
	* Aprés le titre, ajouter un paragraphe (`<p> votre paragraphe </p>`)
  * Commiter vos changement
  * Modifier style.css
	* Ajouter du style à la section deux fois
	  * exemple: `section {background-color: blue;}`
	  * exemple: `section { color: green;}`
	  
  > Attention: l erreur du message du commit de la question suivante est fais exprés!! 
  
  * Commiter les changement avec le message "index.html: modification du style dans section" (mauvais message)
  * le message du commit n 'est pas bon, en effet on a modifié le fichier style.css et non pas index.html
	* Annuler le dernier **message** du commit (et non pas le commit lui meme ---> aller voir git commit --amend) et mettre le bon message "style.css: modification du style dans section
  * Créer un repot sur github pour ce projet
  * créer une remote en ssh entre le repot sur github et votre travail en local
  * Merger la branche section sur la branche master
  * pusher le travail sur github
  * effacer votre branche section
  * Bravo !!!! ou pas
