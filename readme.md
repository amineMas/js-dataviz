Voici des projets de datavizualisation, cela consiste à récupérer des données et de les retranscrire sous forme d'un graphique quel que soit le type.
Dans ces deux projets je récupère des fichiers CSV que je manipule en javascript pour récupérer les données qui m'intéressent puis je les affiche en faisant appel à la librairie Chart.js.

h1 Le premier projet: 
J'ai récupérer un fichier CSV sur le site de la NASA qui présente la moyenne annuelle de la témpérature mondiale. J'ai extrait les températures et les années correspondantes et j'ai utilisé Chart.js pour afficher un graphique à ligne.

Le deuxième projet: 
J'ai cherché sur le site https://www.data.gouv.fr/fr/ un jeu de donnée qui pourrait m'intéresser pour faire de la dataviz. J'ai trouvé un jeu de données intitulé objectif zéro pesticide en Ile de france que j'ai choisi étant sensible aux problématiques écologiques et environnementales. Voici le lien vers le fichier: https://www.data.gouv.fr/fr/datasets/objectif-zero-pesticide-en-ile-de-france-idf/

Il s'agit d'identifier pour chaque commune son utilisation ou non de pesticides, le but étant d'arriver à un objectif zéro pesticides.

Quatre niveaux de pratiques sont identifiés, grâce à un questionnaire
renseigné par les collectivités :

Zéro pesticide total (catégorie 1)

Zéro pesticide sauf sur les espaces à contraintes (catégorie 2,
usage sur terrains de sports et/ou cimetières)

Réduction engagée (catégorie 3, usage sur voirie et/ou espaces verts
et fleurissement)

Usage habituel (catégorie 4, pas de démarche de réduction engagée)

Non renseignée (catégorie 5)

Pour l'instant j'affiche seulement une partie des communes de manière statique, plus tard je souhaite rajouter un bouton pour pouvoir afficher le reste des données de manière dynamique.



Ce que j'ai appris:
Utilisation de l'API fetch
utilisation des promesses, d'async et await (ES7)
Manipuler un fichier type CSV
Utilisation de la librairie Chart.js
