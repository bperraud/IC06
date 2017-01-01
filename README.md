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

### Global

- Enrichir les interactions possibles dans certains passages dans la mesure du possible.
- Accentuer la difficulté au niveau des jets de dés cachés.
- Accentuer la rupture entre les deux phases (effets visuels + texte), voir comment mieux faire sentir au joueur en phase 2 que ce qui lui arrive dépend de la phase 1 (sûrement avec le texte).
- Compléter l’aspect esthétique du jeu : images, bruitages, musique.
- Si le temps, adapter le jeu sur supports mobiles (smartphones et tablettes).
- Compresser les images pour réduire leur temps de chargement.
- Réduire le texte de certains passages, notamment au niveau des timers de la 1re phase.

### Divers

- Transition phase 1/2 : marquer visuellement la transition
- bruit : bruit à incorporer
- Clairière : images (animaux pas/ fantômes/ rien) et texte en accord avec image
- Groupe scouts : texte de discussion à meubler
- antre dragon : images (dragon/moto) et blabla de rencontre
- porte secrete : image?
- lieu secret : niveau bonus à modifier (ou laisser "en chantier")
- Scout perdu : l'implanter dans le scénario

## Notes techniques

- Passage des variables Twine/JS : <http://docs.textadventures.co.uk/ifanswers/ifanswers.com/471/how-do-i-pass-variables-between-twine-and-javascript.html>
