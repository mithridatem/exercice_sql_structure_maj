**Exercice 1 SQL requêtes de mise à jour INSERT SQL** :
Depuis la base de données des livres, nous avons besoin
de remplir celle-ci avec des données de test.
Pour cela vous allez créer les enregistrements suivants :
- 1 Créer 5 **categories** de **book**,
- 2 Créer 3 **accounts**,
- 3 Créer 5 **authors**,
- 3 Créer 15 **books** (*les books sont associés à des authors*),
- 4 Associer les 15 **books** à des **categories**(*existantes*),
- 5 Associer 3 **books** à chaques **account** (*book_account*),
- 6 Ajouter 2 **commentaries** (*liés aux books*) pour chaque **account**.
**NB** : Utiliser des valeurs qui ressemblent à de vrais données (**book, category, author, account, commentary**)

**Exercice 2 SQL requêtes de mise à jour UPDATE SQL** :
Depuis la base de données des livres, nous avons besoin
de mettre à jour des enregistrements :
- 1 Passer le **status** de tous les **accouts** à true,
- 2 Modifier le **password** de tous les **accounts** -> hash en md5,
- 3 Modifier le pseudo de tous les authors -> il sera composé de la 1 lettre du firstname suivi du lastname:
**ex : Victor Hugo -> vhugo**,
- 4 Modifier la date de création de tous les **accounts** (*created_at*) ajouter un an à la date :
**ex : 2020-10-01 -> 2021-10-01**,
- 5 Modifier la **cover** de tous les **books** dont le **title** commence par des lettres comprises entre a et m,
la nouvelle **cover** sera -> update_cover,
- 6 Modifier le **lastname** des **authors** -> passer le **lastname** en Majuscule.

**Exercice 3 SQL requêtes de mise à jour DELETE SQL** :
Depuis la base de données des livres, nous avons besoin
de supprimer des enregistrements :
- 1 Supprimer tous les **commentaries** des **accounts** dont l'**id_account** est compris entre 1 et 2,
- 2 Supprimer les **categories** dont le **category_name** est compris entre a et p,
- 3 Supprimer tous les **books** dont la **publication_date** est inférieure à 1900,
- 4 Supprimer l'**account** dont l'**id_account** est 1,
**NB** : Vous devez gérer les suppressions dans les tables qui dépendent des enregistrements
si la suppression en cascade n'est pas mise en place. Pour s'assurer qu'il ne reste pas
des liaisons invalides.

**Exercice BONUS** (**facultatif, pour les plus rapides**).

**Exercice 4 SQL requêtes de mise à jour UPDATE BONUS SQL** :
Depuis la base de données du Quizz, nous avons besoin
de remplir celle-ci avec des données de test.
- 1 Créer 4 **users**,
- 2 Créer 6 **categories**,
- 3 Créer 3 **quizz**,
- 4 Associer 2 **categories** à chaque **quizz**,
- 5 Créer 15 **questions**,
- 6 Créer et associer 4 **answers** à chaque **question**(*quesion_id ->answer*),
- 7 Associer à chaque **quizz** 5 **questions**(*quizz_question*).

**NB** : Utiliser des valeurs qui ressemblent à de vrais données (**quizz, question, answer, category, users**)