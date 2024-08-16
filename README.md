
<h1 align="center" color="blue">Vérification de Formulaire en JavaScript</h1>
<p align="center">
  <img width="800" height="285" alt="mot validé écrit en orange et entouré" src="https://i.postimg.cc/zG5KB0dK/pngwing-com-1.png" style="width:50%">
</p>

<h2 color="blue">Aperçu du projet</h2>
Ce projet propose une solution robuste en JavaScript pour valider les formulaires côté client. Il offre une gamme de fonctionnalités visant à assurer la saisie précise et sécurisée des données dans un formulaire d'inscription. Les champs incluent le nom d'utilisateur, le nom, le prénom, l'adresse e-mail, la date de naissance, le mot de passe, sa confirmation et le sexe.<br>

<h2 color="blue">Caractéristiques principales</h2>
* Validation du formulaire: chaque champ est soumis à une validation selon des critères prédéfinis (tel que le format de l'e-mail, la longueur du mot de passe, etc.).<br>
* Affichage des erreurs: les erreurs sont signalées en rouge sous les champs correspondants pour une meilleure identification.<br>
* Masquage/Affichage du mot de passe: possibilité de masquer ou afficher le mot de passe à l'aide d'un bouton dédié.<br>
* Validation en temps réel: Utilisation de la fonction debounce pour une validation réactive des champs, offrant un feedback instantané à l'utilisateur.<br>

<h2 color="blue">Structure du Code</h2>
1. Déclaration des Variables: utilisation du DOM pour sélectionner les éléments du formulaire.<br>
2. Gestion des Événements: mise en place d'écouteurs d'événements pour les interactions utilisateur.<br>
3. Fonctions de Validation: implémentation de fonctions dédiées à la validation des différents aspects du formulaire.<br>
4. Gestion des Messages: fonctions showError et showSuccess pour afficher les messages d'erreur et de succès respectivement.<br>
5. Validation Globale: contrôle de l'ensemble des validations lors de la soumission du formulaire.<br>
6. Validation Instantanée: utilisation de debounce pour une validation en temps réel.<br>

<h2 color="blue">Technologies Employées</h2>
HTML<br>
CSS<br>
Bootstrap<br>
JavaScript<br>

<h2 color="blue">Installation et Utilisation</h2>
1. Clonez le dépôt: git clone <br>
2. Installez Bootstrap pour une meilleure présentation: npm i   bootstrap<br>
3. Ouvrez index.html dans votre navigateur<br>
4. Testez les fonctionnalités de validation en remplissant le formulaire.<br>
