1 - generate_database

Permet de filtrer et tokeniser des textes afin de générer des listes de mots à partir de la base de données initiale

2 - generate_vectors

Permet d'assigner un vecteur de dimension 300 à chaque mot à partir d'un réseaux préentraîné sur tous les articles francophones de Wikipédia

3 - generate_clusters

Permet d'identifier, pour chaque article, les principaux clusters de mots et leurs centres avec kmeans

4 - generate_tags

À partir des principaux centres des différents articles, déterminer 400 catégories et leurs principaux centres avec kmeans

5 - test

À partir des centres des différentes catégories, assigner les catégories aux articles.
PS: certaines catégories ne sont pas significatives (ex: groupes de verbes ou de noms propres), un titre est assigné manuellement aux catégories si elles méritent d'apparaître dans la liste des catégories final de l'article que les lecteurs pourront voir.





Les bases de données d'articles étaient trop volumineuses pour joindre à la remise.
Le fichier Output.txt présente 50000 articles et les tags assignés par notre programme vs les tags initiaux présents dans la base de données
Le fichier Output_details.txt présente de l'information relative à comment les tags finaux sont obtenus par le programme.
