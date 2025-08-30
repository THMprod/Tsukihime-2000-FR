# Dossier où seront répartie les chapitres traduis.

## Pourquoi Github ?

La raison de ce choix est simple, je souhaite que tout le monde est accès en temps réel à la traduction et puissent avoir une visibilité sur cette dernière.

Si le projet venait à échouer et/ou être abandonné, n'importe qui pourrait reprendre la traduction du jeu depuis là où cela c'est arrété.

Le seul mot d'ordre de ce projet est "Nous voulons un patch FR pour Tsukihime !", c'est une phrase mais c'est l'objectif.

De plus, avec une traduction transparente, n'importe qui peut être relecteur, traducteur et/ou correcteur.

Pas besoin d'entrer en contact avec quiconque, une correction sur une coquille depuis un merge request où dans une ouverture d'"issue" sur Github peut être faite par n'importe qui.

## Méthode de traduction

Si un volontaire souhaite aider à la traduction, il aura besoin de récupérer un des chapitres tels que décris dans le flowchart et le traduire (merci [Mirror-moon](http://mirrormoon.org/) pour ce document).

Si vous traduisez depuis l'anglais, télécharger le [0.txt](EN/0.txt) et depuis votre logiciel de traitement de texte, faite la recherche "*sXX" XX étant le numéro de chapitre tels que décrit dans le flowchart.

Si vous voulez traduire depuis le japonais, étant donné qu'il y a 10 fichiers textes, c'est la même méthode mais il faudra chercher entre les fichiers 1 à 9 (0.txt n'étant qu'un fichier de configuration).

Un guide pour les fichiers japonais sera donné plus tard.

## J'ai traduis un chapitre, comment le mettre dans le patch ?

L'optimale serait que le chapitre soit entièrement traduit, puis le chapitre pourra être envoyé sous forme de Merge Request sur Github dans le dossier Patch FR.

Je cherche aussi une autre méthode pour la proposition de patch par les traducteurs et traductrices qui ne veulent pas s'embêter avec Github, si vous avez des propositions de choses en plus, je suis à l'écoute.

Un traducteur n'a pas besoin de se prendre la tête avec la mise en page, c'est un plus, mais sinon, je le ferais après pour le 0.utf à la racine du projet qui est voué à être le patch de test pour quiconque veut rapidement essayer le patch.

Pour le coup, si vous souhaitez traduire des parties graphiques du jeux (AKA les menus), n'ayant aucune compétence pour, c'est avec un grand plaisir que j'accepterais toutes aides.

Si vous ne savez pas comment récupérer les fichiers graphiques, un tutoriel sera donné plus tard. Le projet est très jeune et les bases peu solide, les pierres seront posé petit à petit.

Il faut que les choses aillent doucement mais sûrement.

## Comment essayer le patch rapidement ?

Comme évoqué plus tôt, le patch définitif sera le 0.utf à la racine du projet qui sera mis à jour aussi rapidement que possible après proposition de patch de traducteur.

Il vous suffit de récupérer les fichiers de Tsukihime suivant :

- Arc.sar (pas les .nsa(X) si vous venez de la traduction anglaise)

- le dossier CD/

Et c'est tout, le moteur de Tsukihime n'est pas bien compliqué et assez simple de conception.

Après les avoirs récupéré, vous pourrez les mettres dans la racine du projet et lancer le jeu :

- Windows : "onscripter-en.exe"

- Linux : "onscripter-en" (vérifier que le launcher soit exécutable si le jeu ne se lance pas)