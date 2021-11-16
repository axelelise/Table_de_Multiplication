Elise
Axel
BTS SIO22

# TableDeMulti

## Objectif

Nous permettre de consolider les premiers concepts présentés dans les premiers TD d’introduction à Angular. Je vais pour cela concevoir une application web qui affiche une table de multiplication (1 à 10), selon une valeur soumise par l’utilisateur.

## Partie 1
L’utilisateur doit saisir une valeur pour l’afficher la table de multiplication qui correspond.
![](./src/assets/images/unknown.png)



### Etape I

Pour commencé j'ai crée un projet en utilisant cette ligne de code dans un terminal:
```bash 
ng new TableDeMulti --style=css --routing=false
```
Ensuite on créer un component sur lequel travaillé que l'on vas appelé TableMultiplication:
 ```bash 
ng generate component components/TableMultiplication
```
### Etape II

Créer un code adapté a ce que l'on me demande:
![](./src/assets/images/unknown(1).png)
Ce code sert avant tous pour la version visuel.
![](./src/assets/images/unknown(2).png)
![](./src/assets/images/unknown(3).png)
![](./src/assets/images/unknown(4).png)

Chaque partie est indispenssable pour le bon fonctionnement du programme.

### Etape III

Pour tester le code et voir son rendu, il faut lancé un serveur a partir du terminal.
```bash 
ng serve
```
et se connecté au localhost
http://localhost/4000
![](./src/assets/images/unknown(5).png)

L'utilisateur a choisi son nombre et le programme a écrit la table du nombre choisi.

## Partie 2

L'utilisateur choisi combien de tables il veut voir et notre programme lui montrera les tables de 1 jusqu'à son nombre choisi.

![](./src/assets/images/unknown(12).png)

### Etape I

Il faut créer un autre components que l'on appellera cette fois ci TablesMultiplication.
 ```bash 
ng generate component components/TablesMultiplication
```

### Etape II
Il faudra créer un code qui s'adapte au premier component créer et au parent "app.component.
![](./src/assets/images/unknown(6).png)
![](./src/assets/images/unknown(7).png)
![](./src/assets/images/unknown(8).png)
Pour celui-ci j'ai changer de méthode pour la table afin de montrer une autre façon de faire et d'évité d'etre répetitif.
![](./src/assets/images/unknown(9).png)

### Etape III
Pour tester le code et voir son rendu, il faut relancé un serveur a partir du terminal.
```bash 
ng serve
```
et se reconnecté au localhost
http://localhost/4000
![](./src/assets/images/unknown(10).png)
![](./src/assets/images/unknown(11).png)

L'utilisateur a choisi le nombre de table et le programme lui a proposer les tables qui vont de 1 jusqu'au nombre choisi.

