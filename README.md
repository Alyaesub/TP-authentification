Projet TP-GestionBDD :

Modalités / Restrictions :

Écriture des différents scripts SQL de création sécurisée de base de données/de ses tables ainsi que des relations et contraintes entre elles
Remplissage des tables avec de fausses données (toujours à l’aide de commandes SQL)
Explication dans la description du projet d’un processus de sauvegarde de la BDD complète
/////////////////////Notes /////////////// j'ai reflachis a quel étais les utilisateur

puis j'ai créé mon diagramme et mes classe avec...

j'ai crée un administrateur pour gére les bdd :

-- Création de l’utilisateur
-- CREATE USER 'user_php'@'localhost' IDENTIFIED BY '3f7zhhRn4NH69R';
-- GRANT SELECT, INSERT, UPDATE, DELETE ON tp_authentification.users TO 'user_php'@'localhost';

pour windows :
$username = 'user_php';
$password = '3f7zhhRn4NH69R';
$port = 3306;

pour mac je suis rester avec root :
$host = 'localhost'; // Ou l'adresse de ton serveur MySQL
$dbname = 'tp_authentification';
$username = 'root';
$password = 'root';
$port = 8889;

puis coder mes classe et tabe avec sql
