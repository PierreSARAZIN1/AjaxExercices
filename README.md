<div align="center">

#  🔥⎾ _**AJAX - Exercices**_ ⏋🔥

</div>


<div align="center">
<img src ="https://media2.giphy.com/media/l41JMXnXn4E7WQR8s/giphy.gif?cid=ecf05e473yocnkptiv6xdbmz8n3m4naiil4o4aiwgw9pudx4&rid=giphy.gif&ct=g" alt="pierresarazin1"  />
</div>

 ___

<div align="center">

## 💥
## ⎯= _**DESCRIPTION**_ =⎯

</div>
Exercices : <br>
1. Une appli Rails : <br>
Crées un model email ayant des attributs object (string), et body (text) + root le projet sur email#index <br>
2. La view index de base <br>
créer un grand tableau sur 2 colonnes : Une colonne "Liste des emails" qui affichera l'objet de chaque email présent en base + Une colonne "Email sélectionné" qui sera vide au chargement de la page mais qui affichera le contenu (à terme) de l'email sélectionné.<br>
3. Premier niveau d'AJAX : l'ajout d'un email<br>
vas créer un bouton "recevoir un email" juste au dessus de ton tableau + ce bouton fera un appel en POST vers une méthode create du controller emails qui va créer un nouvel email en base via Faker + Tout cela doit avoir lieu en AJAX pour que le nouvel email s'affiche, à la suite des autres et sans rechargement<br>
4. Deuxième niveau d'AJAX : afficher un email<br>
changer chaque objet d'email (le texte) en un lien HTML + passer ce lien en AJAX + exécute un fichier JS qui va afficher le contenu de l'email dans la colonne de droite = objet de l'email sera en gros, en haut de la colonne de droite + corps de l'email sera en taille normale, juste en dessous + Sous le corps d'email, il y aura 2 boutons (inactifs pour le moment) : "Supprimer" et "Marquer comme non-lu"<br>
5. Troisième niveau d'AJAX : la suppression d'un email<br>
Il faut tout simplement que le bouton "Supprimer" fonctionne bien en AJAX. L'email doit disparaître des 2 colonnes

 ___
 
<div align="center">

## 🛠
## ⎯= _**INSTALLATION**_ =⎯ 

</div>

- Télécharger les fichiers
- Entrer dans le dossier : <br>
`$ bundle install`<br>
`$ rails db:create db:migrate`<br>
`$ rails s`<br>
- Sur le navigateur : http://localhost:3000/

 ___
<div align="center">

## 🚀
## ⎯= _**UTILISATION**_ =⎯ 

</div>
 


Vérifier que tout marche bien 🥲
 ___
 ___

<p align="center">
❤️‍🔥 Developed by Pierre SARAZIN ❤️‍🔥
</p>

