# DREAM_TEAM
Portfolio HTML & CSS
Préparation du Projet
Créer un compte sur GitHub

GitHub
Installer Git sur votre machine locale

Suivez les instructions pour installer Git : Installation de Git
Initialisation du Dépôt Git
Créer un nouveau dépôt sur GitHub

Allez sur votre page GitHub, cliquez sur "New" pour créer un nouveau dépôt.
Nommez le dépôt portfolio-html-css.
Cloner le dépôt sur votre machine locale

bash
Copier le code
git clone https://github.com/khalil97ba/DREAM_TEAM.git
Initialiser Git dans le dossier du projet portfolio

bash
Copier le code
cd portfolio-html-css
git init
Ajout des Fichiers au Dépôt
Ajouter les fichiers index.html et styles.css au dépôt local

bash
Copier le code
git add index.html styles.css
Committer les changements avec un message approprié

bash
Copier le code
git commit -m "Premier sauvegarge"
Travail Collaboratif
Inviter des collaborateurs à rejoindre votre dépôt

Allez sur votre dépôt GitHub, cliquez sur "Settings" > "Manage access" > "Invite a collaborator".
Créer une branche pour une nouvelle fonctionnalité

bash
Copier le code
git checkout -b nouvelle-fonctionnalité
Faire des commits réguliers pour documenter la progression

bash
Copier le code
git add .
git commit -m "premiercommit"
Fusion de Branches
Créer une pull request pour fusionner la branche avec main

Sur GitHub, allez sur votre dépôt, cliquez sur "Pull requests" > "New pull request".
Demander une révision et approbation de la pull request par vos collaborateurs

Assigning reviewers dans la pull request.
Fusionner la branche une fois approuvée

Cliquez sur "Merge pull request" puis "Confirm merge".
Résolution de Conflits
En cas de conflits lors de la fusion, travaillez avec vos collaborateurs pour les résoudre

Utilisez les commandes Git pour gérer les conflits, par exemple :
bash
Copier le code
git merge main
Committer les résolutions de conflits et compléter la fusion

bash
Copier le code
git add .
git commit -m "Résolution des conflits"
git push origin nouvelle-fonctionnalité
Gestion des Versions
Utiliser des tags pour marquer des versions spécifiques de votre projet

bash
Copier le code
git tag -a v1.0 -m "Version 1.0"
Pousser les tags vers le dépôt distant

bash
Copier le code
git push origin v1.0
