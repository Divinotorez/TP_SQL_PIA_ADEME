Rapport de TP – Introduction à SQL et MySQL
Ce TP avait pour objectif de nous initier au langage SQL à travers l’étude d’une base de données
répertoriant les Programmes d’Investissement d’Avenir (PIA) de l’ADEME.
L’objectif principal était de comprendre le fonctionnement d’une base de données relationnelle
et de manipuler les données à l’aide de MySQL et MySQL Workbench.
Nous avons commencé par importer la base de données, analyser sa structure (MCD, MLD)
et créer de nouvelles tables à l’aide de l’instruction CREATE TABLE. Nous avons ensuite modifié
la structure existante avec ALTER TABLE, ajouté des clés étrangères et compris l’importance
des contraintes (PRIMARY KEY, FOREIGN KEY, NOT NULL) pour garantir l’intégrité des données.
Concernant la manipulation des données, nous avons utilisé les commandes INSERT INTO
pour ajouter des enregistrements, UPDATE pour modifier des données (notamment le coût total
des projets), ainsi que l’import de fichiers CSV pour mettre à jour plusieurs lignes efficacement.
Nous avons ensuite réalisé de nombreuses requêtes SELECT avec des conditions WHERE,
des tris ORDER BY et des opérateurs logiques (AND, OR, BETWEEN, LIKE).
Les jointures (JOIN) nous ont permis de relier plusieurs tables afin d’obtenir des informations
complètes sur les projets, les programmes et les partenaires.
Nous avons également utilisé des fonctions d’agrégation telles que SUM(), AVG() et COUNT()
associées à GROUP BY et HAVING afin d’analyser les coûts cumulés, le nombre de projets
par département et le coût moyen sur une année donnée.
Enfin, nous avons créé des vues pour simplifier certaines requêtes complexes et des
procédures stockées permettant d’automatiser des opérations comme l’affichage
d’un projet, l’insertion de données ou la modification de la durée d’un projet.
À l’issue de ce TP, je suis capable de créer, modifier et interroger une base de données
relationnelle,  et d’automatiser
des traitements grâce aux procédures stockées.
