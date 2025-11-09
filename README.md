# SAE_501

### Implémentation des différents codes

Le projet a été implémenté en trois modules principaux :

1. **Front-end (React)**
   - Composants : formulaires d’inscription, affichage des formations, espace utilisateur
   - Système de navigation : React Router
   - Connexion à l’API REST

2. **Back-end (Spring Boot)**
   - Structure du projet :
     - `controller/` : (ex. `/api/formations`, `/api/utilisateurs`)
     - `service/` : logique métier (gestion des paiements, absences, etc.)
     - `repository/` : accès aux données (interfaces JPA)
     - `model/` : entités Java reliées à la base MySQL

3. **Base de données (MySQL)**
   - Création via script SQL généré à partir du modèle physique
   - Données de test insérées pour validation

4. **Gestion du code source**
   - Branches dédiées par personne
   - Commits réguliers 

