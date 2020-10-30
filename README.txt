1 - generate_database

Permet de filtrer et tokeniser des textes afin de g�n�rer des listes de mots � partir de la base de donn�es initiale

2 - generate_vectors

Permet d'assigner un vecteur de dimension 300 � chaque mot � partir d'un r�seaux pr�entra�n� sur tous les articles francophones de Wikip�dia

3 - generate_clusters

Permet d'identifier, pour chaque article, les principaux clusters de mots et leurs centres avec kmeans

4 - generate_tags

� partir des principaux centres des diff�rents articles, d�terminer 400 cat�gories et leurs principaux centres avec kmeans

5 - test

� partir des centres des diff�rentes cat�gories, assigner les cat�gories aux articles.
PS: certaines cat�gories ne sont pas significatives (ex: groupes de verbes ou de noms propres), un titre est assign� manuellement aux cat�gories si elles m�ritent d'appara�tre dans la liste des cat�gories final de l'article que les lecteurs pourront voir.





Les bases de donn�es d'articles �taient trop volumineuses pour joindre � la remise.
Le fichier Output.txt pr�sente 50000 articles et les tags assign�s par notre programme vs les tags initiaux pr�sents dans la base de donn�es
Le fichier Output_details.txt pr�sente de l'information relative � comment les tags finaux sont obtenus par le programme.
