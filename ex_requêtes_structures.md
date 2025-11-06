**Exercice 3 SQL requêtes de structure SQL** :
Nous souhaitons développer une application de quizz.
Elle doit permettre de créer des quizz, de gérer les utilisateurs, 
de pouvoir jouer les quizz et afficher les résultats.  
Nous avons besoin de mettre en place la base de données.

Depuis le **MCD - MLD** ci-dessous, réaliser le code de **structure SQL**.  
Avec les **tables**, les **contraintes** de clé étrangères.


**Exercice 4 SQL requêtes de structure SQL** :

Nous souhaitons développer une application pour gérer des collections de livres.
Elle doit permettre de gérer des collections de livre, gérer les utilisateurs et
de permettre aux utilisateurs de laisser des commentaires sur les livres. 
Nous avons besoin de mettre en place la base de données.

Depuis le **MCD - MLD** ci-dessous, réaliser le code de **structure SQL**.  
Avec les **tables**, les **contraintes** de clé étrangères.

**Exercice 5 SQL requêtes de structure SQL** :
Pour améliorer la base de données de gestion des livres, nous avons besoin
de réaliser les modifications suivantes :
- 1 Ajouter un attribut dans la table **account** :
**account_img** de type **VARCHAR(255)** **NOT NULL** avec la valeur par
default "default.png",
- 2 Ajouter un attribut dans la table **book** :
**back_cover** de type **VARCHAR(255)** **NULL**,
- 3 Ajouter un attribut dans la table **commentary** :
**note** de type **INT** **NOT NULL** avec la valeur par default **0**,
- 4 Editer un attribut dans la table **book** :
passer l'attribut **publication_date** en **DATETIME** avec la valeur par
default **CURRENT_TIMESTAMP** et **NOT NULL**.