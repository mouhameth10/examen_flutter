Documentation des Étapes de Développement
Étape 1 : Planification et Conception
Objectif : Créer une application de commerce électronique permettant aux utilisateurs de naviguer, de s'inscrire, de se connecter, et de gérer leurs profils.
Maquettes : Conception de wireframes pour définir l'interface utilisateur, le flux de navigation et l'expérience utilisateur globale.
Étape 2 : Configuration de l'Environnement
Installation de Flutter : Télécharger et installer Flutter SDK.
Configuration de l'IDE : Utiliser Android Studio ou Visual Studio Code pour le développement Flutter.
Création d'un Nouveau Projet : Utiliser la commande flutter create nom_du_projet pour initier un nouveau projet.
Étape 3 : Développement des Fonctionnalités
3.1. Page d'Accueil
Structure de la Page :
AppBar : Inclut le titre de l'application et un bouton de panier.
Drawer : Menu de navigation latéral avec des liens vers différentes sections (Accueil, Favoris, Recherche, Panier, Mon Compte, À Propos, Déconnexion).
Affichage des Produits : Section principale qui affiche les produits disponibles, généralement sous forme de grille ou de liste.
Navigation : Utilisation de Navigator pour gérer les transitions entre les pages.
3.2. Inscription des Utilisateurs
Création de la Page d'Inscription :
Champs pour le nom, prénom, email, mot de passe, et confirmation du mot de passe.
Validation : Vérification que tous les champs sont remplis et que les mots de passe correspondent.
Gestion des Erreurs : Affichage de messages d'erreur en cas d'entrée invalide.
Étape 4 : Gestion de l'État
Utilisation de setState : Mettre à jour l'interface utilisateur en réponse aux actions des utilisateurs, comme la saisie de texte ou la navigation.
Gestion des Favoris : Stocker les produits favoris dans une liste et permettre leur suppression.
Étape 5 : UI/UX Design
Utilisation des Widgets Flutter :
TextField pour la saisie des informations utilisateur.
Card pour afficher les produits.
Drawer pour la navigation.
Thème et Couleurs : Application d'un thème cohérent avec des couleurs appropriées, principalement le vert pour correspondre à l'identité visuelle de l'application.
Étape 6 : Tests
Tests Manuels : Vérification du bon fonctionnement de chaque fonctionnalité via des tests utilisateurs.
Tests d'Intégration : S'assurer que les différentes pages de l'application se connectent correctement et que les données circulent comme prévu.
Présentation des Fonctionnalités
Diapositive 1 : Titre
Darou Mouhty Computer.
Nom de l'Auteur : Mouhameth wade.
Date : 14/12/2024.
Diapositive 2 : Objectifs de l'Application
Fonctionnalités Clés :
Inscription et connexion des utilisateurs.
Navigation dans les produits et gestion des favoris.
Interface utilisateur intuitive et attrayante.
Diapositive 3 : Architecture de l'Application
Structure de l'Application :
Pages Principales : Accueil, Inscription, Connexion, Profil, Favoris, Panier.
Navigation : Diagramme montrant comment les pages se connectent entre elles.
Diapositive 4 : Page d'Accueil
Capture d'Écran : Image de l'écran d'accueil.
Fonctionnalités :
Affichage des produits en vedette.
Menu de navigation latéral pour accéder rapidement aux autres sections.
Diapositive 5 : Page d'Inscription
Capture d'Écran : Image de la page d'inscription.
Fonctionnalités :
Saisie des informations utilisateur avec validation en temps réel.
Messages d'erreur affichés pour les champs invalides.
Diapositive 6 : Techniques Utilisées
Technologies :
Langage : Dart avec Flutter pour le développement.
Gestion de l'État : Utilisation de setState pour la gestion des états.
Stockage : Utilisation de SharedPreferences pour stocker les informations de l'utilisateur localement.
