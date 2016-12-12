# IC06

## Procédure de modification du projet

- S'assurer que le repository est bien cloné
- _Pull_ pour récupérer les dernières modifications
- Ouvrir Twine 2.x puis dans le menu sélectionner **"Importer depuis un Fichier"**
- Sélectionner le fichier .html du _repository_
- Éventuellement supprimer les doublons plus anciens
- Effectuer les modifications nécessaires
- Une fois ces dernières accomplies, dans le menu de l'histoire, sélectionner **"Publier vers un Fichier"**
- Écraser le fichier .html du _repository_
- _Commit_ les modifications régulièrement
- _Push_ pour mettre à jour le projet à distance

**ATTENTION : Twine crée une copie de l'histoire lorsque l'on importe à partir d'un fichier,
c'est pourquoi seule la copie locale sera modifiée dynamiquement au fur et à mesure des
changements faits dans l'interface du logiciel. Il est donc nécessaire de systématiquement
exporter l'histoire vers le _repository_.**

_Note : pour tester l'histoire avec les médias importés, il faut lancer le fichier .html du
repository (~~je ne sais pas encore comment faire en local...~~ impossible : <https://twinery.org/wiki/twine2:add_an_image_movie_sound_effect_or_music>)._

## Procédure d'installation de SugarCube 2.x pour Twine 2.x

- Mettre à jour le _local repository_ pour avoir le fichier source du format ;
- Suivre les instructions sur le site <http://www.motoslave.net/sugarcube/2/docs/twine-2.html>.

## Todos et notes

- "Finaliser" la mise en place des _timers_ de la phase 1, cf. ci-dessous
- Corriger le saut de ligne dans le passage du réveil
- Corriger le bug visuel de la texture qui "bave"
- Ajouter le mécanisme de jet aléatoire pour le choix forcé d'un ingrédient

## Question du timer

- visuel du chaudron en plusieurs étapes :
    - immobile
    - bout
    - bouillonne
    - explose
- positionnement des images du chaudron (sorcier ?) :
    - zone fixe hors cadre textuel
    - intercalé au texte
- selon les étapes du chaudron, timer enclenché ; il pourrait être déclenché seulement au niveau de l'étape 3 du chaudron. On peut également considérer que l'étape 2 déclenche elle-même l'étape suivante, etc.
- quand on arrive sur la page, on dispose inconsciemment de x s pour que chaudron arrive à l'état "bout", puis y s à l'état "bouillonne", etc.
- le joueur sait qu'il doit se presser si le visuel évolue alors qu'il est retard sur le texte !
- la musique peut donc être composée de manière fixe et évoluer graduellement pour accentuer la sensation de stress

- insertion d'une image dans "groupe scout" selon récit (pomme) où il faudra cliquer dessus
- intéraction image (gelée) et clique nécessaire à ne pas mourrir gelé ("passer au travers de la glace)

Reste à faire Phase 2 :

Phase 2 : flash back (image)
Rivière : images (gelée et non)
Passer au travers de la glace : intéraction avec image pour se sortir de l'eau (ou bad end)
Porter le sac : RAS
porter le bâton : RAS
bruit : bruit à incorporer
Clairière : images (animaux pas/ fantômes/ rien) et texte en accord avec image + ortho
Retour discret : ortho
Retour fuite : lancé dés
Manifestation : RAS
Discussion : image lapin + ortho
Groupe scouts : image et ortho
Embranchement : image + ortho
Chemin Sombre : RAS
Piece or : RAS
antre dragon : images (dragon/moto) et blabla de rencontre
porte secrete : image?
lieu secret : niveau bonus à réaliser
raccourci : RAS
Cabane : image nains de jardin + texte à réaliser
Procès : ?

Badend : relier à qqch
Scout perdu : l'implanter dans le scénario