
<h1 style="color:blue">Vérification de Formulaire en JavaScript</h1>
<p align="center">
  <img width="1024" height="385" alt="capture d'écran de la liste de tâches" src="https://i.postimg.cc/zG5KB0dK/pngwing-com-1.png" style="width:50%">
</p>

<h2 style="color:blue">Aperçu du projet</h2>
Ce projet propose une solution robuste en JavaScript pour valider les formulaires côté client. Il offre une gamme de fonctionnalités visant à assurer la saisie précise et sécurisée des données dans un formulaire d'inscription. Les champs incluent le nom d'utilisateur, le nom, le prénom, l'adresse e-mail, la date de naissance, le mot de passe, sa confirmation et le sexe.

<h2 style="color:blue">Caractéristiques principales</h2>
* Validation du Formulaire: Chaque champ est soumis à une validation selon des critères prédéfinis (tel que le format de l'e-mail, la longueur du mot de passe, etc.).
* Affichage des Erreurs: Les erreurs sont signalées en rouge à côté des champs correspondants pour une meilleure identification.
* Masquage/Affichage du Mot de Passe: Possibilité de masquer ou afficher le mot de passe à l'aide d'un bouton dédié.
* Validation en Temps Réel: Utilisation de la fonction debounce pour une validation réactive des champs, offrant un feedback instantané à l'utilisateur.
<h2 style="color:blue">Structure du Code</h2>
1. Déclaration des Variables: Utilisation du DOM pour sélectionner les éléments du formulaire.
2. Gestion des Événements: Mise en place d'écouteurs d'événements pour les interactions utilisateur.
3. Fonctions de Validation: Implémentation de fonctions dédiées à la validation des différents aspects du formulaire.
4. Gestion des Messages: Fonctions showError et showSuccess pour afficher les messages d'erreur et de succès respectivement.
5. Validation Globale: Contrôle de l'ensemble des validations lors de la soumission du formulaire.
6. Validation Instantanée: Utilisation de debounce pour une validation en temps réel.

<h2 style="color:blue">Technologies Employées</h2>
HTML
CSS
Bootstrap
JavaScript

<h2 style="color:blue">Installation et Utilisation</h2>
1. Clonez le dépôt: git clone
2. Installez Bootstrap pour une meilleure présentation: npm i   bootstrap
3. Ouvrez index.html dans votre navigateur.
4. Testez les fonctionnalités de validation en remplissant le formulaire.
