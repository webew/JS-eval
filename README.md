# Evaluation Javascript

## 1 - Mise en oeuvre et manipulations du DOM

### Mise en oeuvre

On utilisera ici le dossier *ex1*.

- Reliez le fichier *main.js* au fichier *index.html*.

- Créez un nouveau fichier *js/utils.js*.

- Dans le fichier *utils.js*, créez une variable **messageUtil** prenant pour valeur la chaîne de caractères **"Je viens d'ailleurs"**.

- Faites en sorte d'afficher la variable **messageUtil** dans le fichier *main.js* avec **console.log** (sans utiliser les modules ;) ).

- Dans le fichier *main.js*, créez une nouvelle variable **messageMain** prenant pour valeur **"N'ayez pas peur :)"**.
  
- Toujours dans le fichier *main.js*, utilisez les variables **messageMain** et **messageUtil** pour afficher dans la console le message **"N'ayez pas peur. Je viens d'ailleurs"**.
Vous procéderez ainsi :
  - afficher les 2 variables dans un console.log
  - concaténer les 2 variables dans un console.log
  - concaténer les 2 variables dans une 3ème variable et afficher celle-ci dans un console.log
  - afficher les 2 variables dans un template de chaîne dans un console.log

### DOM

Toujours dans le dossier *ex1* :

- Avec Javascript, créez une balise h2 et insérez-y le message précédemment affiché dans la console, puis ajoutez cette balise h2 dans body.

---

## 2 - Dynamique vs statique

On utilisera ici le dossier *ex2*.

- Reproduire le code Html du fichier *index.html* en Javascript.

---

## 3 - Un peu d'algo

Utilisez le dossier ex4.

- Créez un tableau contenant les valeurs suivantes : 45,23,12,78,4,10.

- Créez un programme qui affiche chaque valeur du tableau.

- Modifier votre programme pour afficher pour chaque valeur du tableau si celle-ci est paire ou impaire.

- Ajoutez un peu de code pour afficher le nombre de valeurs paires et le nombre de valeurs impaires.

---

## 4 - Afficher des utilisateurs

L'objet de cet exercice est d'afficher une liste d'utilisateurs en chargeant les données de différentes façons.

Utilisez le dossier ex4.

### Etape 1 : données "en dur", tout dans le JS

A partir du tableau *users* dans *main.js*, affichez les utilisateurs (users) dans la page *index.html* sous la forme d'une div contenant :

- une balise h2 pour le prénom et le nom
- une balise p pour l'email
- une balise img pour l'avatar

### Etape 2 : déplacer le code dans une fonction

Isolez le code d'affichage d'un utilisateur dans une fonction qui prendra un user comme argument. Cette fonction doit retourner l'élément généré (la div).

### Etape 4 : ajouter un bouton

Ajoutez un bouton dans la page. Créez un écouteurs d'événement qui charge les données (en appelant la fonction précédemment créée) lorsqu'on clique sur le bouton.

### Etape 3 : utiliser la source de données datas.json

Commentez le code du tableau *users* et récupérez avec fetch dans une variable *users* le contenu du fichier *datas/datas.json*. Votre code doit toujours fonctionner et afficher 10 utilisateurs.

### Etape 4 : déplacer le code de récupération des données dans une fonction

Créez une fonction qui renvoie la liste des utilisateurs sous forme de tableau.

### Etape 5 : créer des modules

Déplacez vos fonctions dans des modules.

pfiou !..
