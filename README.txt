Projet : MystikJumping3D
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
                                                             !!! Bienvenue dans MystikJumping3D !!!
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Vous incanez un aventurier assoiffé de sensations et de parcours toujours plus risqués !

A vous d'enchaîner les sauts afin de parcourir le fameux "Sentier Perdu des Iles Volantes"...

Le but du projet est de faire un jeu style parcours saut d'obstacle avec un joueur evoluant dans un decor.
Il y a un menu principal dans une scene menu qui ouvre la fenetre de jeu avec un bouton Start et un bouton pour quitter
Il y a aussi un menu pause en appuyant sur echap avec un bouton pour reprendre le jeu, un pour retourner au menu principal 
et un pour quitter. La création des menus a nécessité l'utilisation de Raycasts.
les plateformes et les objets ont été créées à l'aide d'un asset low poly appelé WoodLand de même que le feu de camp.
le feu de camp utilise plusieurs set de particule effects pour rendre un feu de camp réaliste avec de la fumée et des flammes,
sa création à nécessité plus de 5h de development.
La création des menus a nécessité l'utilisation de Raycasts.
l'une de nos difficultés a été de faire un player fonctionnant parfaitement avec le decor qui puisse sauter et courir,
dont les paramètres peuvent êtres modifiés facilement. Après 4 essais le player était prêt.
La dispostion des îles a été conçu en fonction des parametre du player pour avoir une difficulté modéré/difficile.
Des rondins ont été disposés en tant qu'obstacle sur tout le parcours, ils peuvent être ecartés en les poussants.
Un système pour respawn a aussi été ajouter avec un trigger qui s'active quand le player traverse un large box invisble sous la map en tombant.
Au début nous étions partis sur un systeme qui ramene le player a la position initiale mais les elements du decors comme les rondins 
ne revenaient pas a leur position d'origine.
On a donc opter pour reload de la scene pour chaque respawn.
Les boutons Exit sont fait pour fonctionner seulement dans le .exe sinon un message dans la console apparaît.
On a choisi de faire un arrière plan avec une image 360 converti en skybox puis en material en s'inspirant de certains pack de texture
de minecraft.
des PointLight ont été rajouter sur le totem de runes a la fin du parcours pour rajouter un effet mystique.
Le jeu est entièrement fonctionnel sans aucun message dans la console ou bug.

Réalisé par Audric, Coco et Sam

           ------------------------
          |  COMMANDES :           |
          | -----------------------|
          |  w,a,s,d : se deplacer |       Note : Utiliser un clavier qwerty ou changer la langue du clavier.
          |  shift : accelerer     |
          |  espace : sauter       |
          |  echap : pause (menu)  |
           ------------------------

Features :
 - Menu permettant de mettre pause, fermer le jeu et reprendre la partie.
 - respawn en tombant.
 - Particle systems, Raycast, Trigger, box/mesh collider, rigidbody, skybox.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
