# PowerBI-Projet-Plantation-d-arbres-a-Paris
Ce projet permet de visualiser les projets de plantation d'arbres à Paris, à partir d'une base de données publique disponible sur le site Data Paris :
https://opendata.paris.fr/explore/dataset/arbres-plantes-par-projet/information/

L'objectif de ce projet est d'identifier les éléments statistiques les plus pertinents pour analyser l'étendue de l'action de plantation à Paris selon les arrondissements et les secteurs administratifs. Plusieurs travaux ont été réalisés sur la base de données via Power Query, et différentes mesures statistiques ont été créées : densité moyenne de plantation, nombre moyen d'arbres par projet, et totaux de projets réalisés et d'arbres plantés.

Ces mesures ont également été mobilisées lors de la transformation de la base de données, notamment pour la création d'une classification de projets en fonction du nombre d'arbres plantés :

-les projets ayant moins de 50 arbres
-entre 50 et 100
-entre 100 et 300
-entre 300 et 500
-entre 500 et 700
-entre 700 et 1000
-entre 1000 et 2500
-plus de 2500

L'idée derrière cette classification est qu'un projet aboutissant à la plantation de 100 arbres n'a pas le même poids qu'un projet aboutissant à la plantation de plus de 2500 arbres.

Enfin, dans une perspective d'analyse de politique publique, un graphe final a été conçu pour illustrer les actions de chaque secteur administratif en fonction du total des arbres plantés, du total de projets réalisés et du nombre moyen d'arbres par projet. Le total de projets réalisés permet d'évaluer l'intensité de l'action de chaque secteur, le nombre moyen d'arbres par projet apporte un aperçu de la stratégie de plantation adoptée, et le total d'arbres plantés offre une vision globale des réalisations par secteur.
