# Config projet

Le code source de projet Achat en ligne. 

0. BackEnd: créer la bdd egameproject via MySQLWorkBench, cherset est utf8, collation est utf8_general_ci.
            0bis. lancer le server spring boot (apres Maven install): click droite sur le nom de projet dans eclipse, run as => Spring               Boot App.
            
   Frontend: ouvrir le projet (-ciyashop) et lancer npm install avec node puis npm start. 


1. lancer http://localhost:8080/initusers
En lancant cette url : /initusers, Le systeme ajoute maintenant 3 roles (ROLE_ADMIN client seller) et 3 users avec chacun un role different. Lors de votre prochain pull, avant de lancer l'app spring, droper la BD ou les tables "users" "roles" et "users_roles" puis relancer le /initusers qui va ajouter les users avec leur roles
2. lancer http://localhost:8080/initArticles
Pour créer les articles, les insérer dans la base de données



Si vous avez des problemes de constructeurs non définie ou getter et setters c'est proablement que vous navez pas installer lombok.
Voici la manip :
-Aller dans C:/Users/User/.m2/repository/org/projectlombok/lombok/1.18.4
-Faire double clic sur lombok-1.18.4 et d´emarrer l’installation (c¸a peut prendre plusieurs minutes)
-Red´emarrer Eclipse
