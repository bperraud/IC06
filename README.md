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


### 1ers feedbacks

- c'est dommage de se presser, plaisir de lecture
- image qui détourne l'attention parce qu'elle change ->> prendre en compte ce délai pour le timer ?
- musique qui dérange la lecture, après difficile à statuer du fait de l'ambiance sonore (pas de mise en condition efficace)

### Feedback Agathe

- quelques fautes d'ortho à corriger :-)
- apparition du texte en dessous de l'image au réveil doit être plus fluide sinon bancal
- nécessité d'avoir un background musical dès le début sinon les bruitages tombent comme un cheveu dans la soupe
- concernant le timer :
    - musique qui met dans l'ambiance mais qui ne stresse pas nécessairement
    - si en pleine lecture, on ne voit pas que l'image change ->> ajouter davantage de frames à défaut d'animer ?
    - plus approprié de balancer le timer en fonction du niveau de scroll, à voir si on peut le faire facilement
    - sinon, faire en deux temps, où l'on indique dans le premier temps après X s. au joueur qu'il est indécis mais que le chaudron n'attend pas
    - de manière générale, une stratégie serait de mettre l'accent sur le texte-même pour que le joueur comprenne que la situation est stressante...
    
## Reste à faire Phase 2

- Phase 2 : flash back (image)
- Rivière : images (gelée et non)
- Passer au travers de la glace : intéraction avec image pour se sortir de l'eau (ou bad end)
- Porter le sac : RAS
- porter le bâton : RAS
- bruit : bruit à incorporer
- Clairière : images (animaux pas/ fantômes/ rien) et texte en accord avec image
- Retour discret : RAS
- Retour fuite : RAS
- Manifestation : RAS
- Discussion : image lapin
- Groupe scouts : image et texte de discussion à meubler
- Embranchement : image
- Chemin Sombre : RAS
- Piece or : RAS
- antre dragon : images (dragon/moto) et blabla de rencontre
- porte secrete : image?
- lieu secret : niveau bonus à modifier (ou laisser "en chantier")
- raccourci : RAS
- Cabane : image nains de jardin + texte à réaliser
- Procès : ?

- Badend : relier à qqch
- Scout perdu : l'implanter dans le scénario

## Notes techniques

- Passage des variables Twine/JS : <http://docs.textadventures.co.uk/ifanswers/ifanswers.com/471/how-do-i-pass-variables-between-twine-and-javascript.html>
