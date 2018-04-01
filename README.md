# Matrix_Multiplication

Dans ce projet, notre objectif est faire la multiplication de deux matrices de dimensions très grandes. Nous proposons deux algorithmes utilisans tous les deux MapReduce et Spark. 

Pour tester notre algorithmes, utiliser le générateur de matrice pour générer les matrices aléatoires.

Test de algo1 : 
Dans le terminal, saisir ' python generate.py your_filename 10 10 10 '  # generer deux matrice dans le fichier your_name.txt
Puis python mapper.py | python reducer.py

Test de algo2 : 
Dans le terminal, saisir ' python generator_algo2.py '  # Ceci genere matrice A de dimension 400x400 et matrice B de dimension  400x400. 
Puis python mapper1_algo2.py | sort | reducer1_algo2.py | sort | python reducer2_algo2.py

