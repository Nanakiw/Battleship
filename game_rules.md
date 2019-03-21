déroulement d'une partie :

-initialisation des grilles de jeu
	
-chaque joueur place ses bateaux 
	
-les joueurs tirent à tour de rôle :
	
*joueur attaquant choisit une case 

*il envoie cette info à l'autre joueur

*l'autre joueur check le statut de la case (touché ? vide ?) 

*il renvoie l'info au joueur attaquant 

*le joueur attaquant change le status de la case attaqué

*les joueurs changent de rôle (attaquant = attaqué && attaqué devient attaquant)
