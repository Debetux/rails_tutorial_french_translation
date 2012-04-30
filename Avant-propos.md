Avant-propos 

Ma précédente compagnie (CD Baby) fut une des premières à basculer intégralement vers Ruby on Rails, et à rebasculer aussi intégralement vers PHP (googlez-moi si vous voulez prendre la mesure du drame). On m'a tellement recommandé ce livre Michael Hartl que je n'ai pu faire autrement que de le lire. C'est ainsi que le Tutoriel Ruby on Rails m'a fait revenir à nouveau à Rails.

Bien qu'ayant parcouru de nombreux livres sur Rails, c'est ce tutoriel-là qui m'a véritablement « mis en possession » de Rails. Tout est fait ici « à la manière de Rails » — une manière qui ne m'avait jamais semblé naturelle avant que je ne lise ce livre. C'est aussi le seul ouvrage sur Rails qui met en place, d'un bout à l'autre, un Développement Dirigé par les Tests (Test-Driven Development), une approche que je savais hautement recommandée par les experts mais dont je n'avais jamais compris aussi bien la pertinence que dans ce livre. Enfin, en incluant Git, GitHub et Heroku dans les exemples de la démonstration, l'auteur vous donne vraiment le goût de ce qu'est le développement d'un projet dans la vie réelle. Et le exemples de code ne sont pas en reste.

La narration linéaire adoptée par ce tutoriel est vraiment un bon format. Personnellement, j'ai étudié Le Tutoriel Rails en trois longues journées, en faisant tous les exemples et les exercices proposés à la fin de chaque chapitre. C'est en lisant ce livre du début à la fin, sans sauter la moindre partie, qu'on en tire tout le bénéfice.

Régalez-vous !

Derek Sivers (sivers.org) 
Précédemment : Fondateur de CD Baby 
Actuellement : Fondateur de Thoughts Ltd. 

Remerciements 

Ce Tutoriel Ruby on Rails doit beaucoup à mon livre précédent sur Rails, RailsSpace, et donc à mon co-auteur Aurelius Prochazka. J'aimerais remercier Aure à la fois pour le travail qu'il a accompli sur ce précédent livre et pour son soutien pour le présent ouvrage. J'aimerais aussi remercier Debra Williams Cauley, mon éditeur pour les deux ouvrages ; aussi longtemps qu'elle jouera avec moi au baseball, je continuerai d'écrire des livres pour elle.

J'aimerais remercier une longue liste de Rubyistes qui m'ont parlé et inspiré au cours des années : David Heinemeier Hansson, Yehuda Katz, Carl Lerche, Jeremy Kemper, Xavier Noria, Ryan Bates, Geoffrey Grosenbach, Peter Cooper, Matt Aimonetti, Gregg Pollack, Wayne E. Seguin, Amy Hoy, Dave Chelimsky, Pat Maddox, Tom Preston-Werner, Chris Wanstrath, Chad Fowler, Josh Susser, Obie Fernandez, Ian McFarland, Steven Bristol, Giles Bowkett, Evan Dorn, Long Nguyen, James Lindenbaum, Adam Wiggins, Tikhon Bernstam, Ron Evans, Wyatt Greene, Miles Forrest, les gens bien de Pivotal Labs, le gang Heroku, les mecs de thoughtbot et l'équipe de GitHub. Enfin, tellement, tellement, tellement de lecteurs — beaucoup trop pour les citer tous — qui ont contribué par leur rapport de bogues et leurs suggestions durant l'écriture de ce livre, et je tiens à saluer leur aide sans laquelle ce livre ne serait pas ce qu'il est. 

À propos de l'auteur 

Michael Hartl est programmeur, éducateur et entrepreneur. Il est le co-auteur de RailsSpace, un tutoriel Rails publié en 2007, et a été co-fondateur et développeur en chef de Insoshi, une plateforme de réseau social populaire en Ruby on Rails. Précédement, il a enseigné la théorie et la physique informatique au California Institute of Technology (Caltech), où il a reçu le Lifetime Achievement Award for Excellence en enseignement. Michael est diplômé du Harvard College, a un Ph.D. en physique (un doctorat. NdT) de Caltech, et il est ancien élève du programme des entrepreneurs Y Combinator. 

Copyright et license 

Le Tutoriel Ruby on Rails : apprendre Rails par l'exemple. Copyright © 2010 par Michael Hartl. Tout le code source du Tutoriel Ruby on Rails est disponible sous la license MIT License et la licence Beerware License.

   Copyright (c) 2010 Michael Hartl

      Permission est accordée, à titre gratuit, à toute personne obtenant
         une copie de ce logiciel et la documentation associée, pour faire des 
	    modification dans le logiciel sans restriction et sans limitation des
	       droits d’utiliser, copier, modifier, fusionner, publier, distribuer,
	          concéder sous licence, et / ou de vendre les copies du Logiciel, et à
		     autoriser les personnes auxquelles le Logiciel est meublé de le faire, 
		        sous réserve des conditions suivantes:

			   L’avis de copyright ci-dessus et cette autorisation doit être inclus
			      dans toutes les copies ou parties substantielles du Logiciel.

			         LE LOGICIEL EST FOURNI «TEL QUEL», SANS GARANTIE D’AUCUNE SORTE, 
				    EXPLICITE OU IMPLICITE, Y COMPRIS, MAIS SANS S’Y LIMITER, LES 
				       GARANTIES DE QUALITÉ MARCHANDE, ADAPTATION À UN USAGE PARTICULIER ET
				          D’ABSENCE DE CONTREFAÇON. EN AUCUN CAS LES AUTEURS OU TITULAIRES DU
					     ETRE TENU RESPONSABLE DE TOUT DOMMAGE, RÉCLAMATION OU AUTRES
					        RESPONSABILITÉ, SOIT DANS UNE ACTION DE CONTRAT, UN TORT OU AUTRE,
						   PROVENANT DE, DE OU EN RELATION AVEC LE LOGICIEL OU L’UTILISATION OU
						      DE TRANSACTIONS AUTRES LE LOGICIEL.
						      	
							/*
							 * ------------------------------------------------------------
							  * "LA LICENCE BEERWARE" (Révision 42) :
							   * Michael Hartl a écrit ce code. Aussi longtemps que vous
							    * conservez cette note, vous pouvez faire ce que vous voulez
							     * de ce travail. Si nous nous rencontrons un jour, et que vous
							      * pensez que ce travail en vaut la peine, vous pourrez me
							       * payer une bière en retour.
							        * ------------------------------------------------------------
								 */

