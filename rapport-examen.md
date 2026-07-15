# Examen final EDW2

## Identification

- **Prénom** : Joannie 
- **Nom** : Ortega Alvarenga 
- **Groupe** : H26-EDW2

## Liens publics

- `Dépôt GitHub:` https://github.com/joannieoa/edw2-examen-final-joannie-ortega/tree/main
- `Site déployé sur N0C:` https://edw2-examen-final-joannie.e2495411.webdevmaisonneuve.ca/

## Étapes réalisées

1. Je me suis connecter sur la machine a distance WSL.
2. Je me suis assurer d'être sur var/www/
3. Jai fait `git clone <URL> nom_projet` pour pouvoir avoir accès au fichier que je devais modifier en mettant mon nom.
4. J'ai modifier la page d'accueil `index.php` en ajoutant mon nom.
5. J'ai fais `git remote add rendu <URL>` pour créer le remote `rendu` pour pouvoir push sur mon dépôt et non celui du prof.
6. J'ai fais `git remote -v` et mon remote était bien là.
7. J'ai `git add .` et ensuite j'ai `commit`.
8. J'ai ensuite envoyer mon examen vers mon dépôt GitHub avec `git push rendu main`.
9. Je me suis connecter sur N0C
10. J'ai cloner mon dépôt GitHub sur N0C
11. J'ai créer mon sous-domaine sur planethoster et assurer que sa pointer au bon endroit.
12. J'ai vérifier que le site ouvre bien sur le navugateur. c'est validé

## Commandes Git utilisées

-  `git clone:` Sa sert à aller prendre une copie d'un dépôt gitHub pour l'avoir sur ma machine.
- `git remote -v:` Sa sert à savoir vers quels dépôt pointe mon projet. Quand je vais git push ou mon projet sera pousser.
- `git remote add:` Sert à ajouter le dépôt ou je veux push mon projet.
- `git status:` Sert a savoir si il y a des modifications, un ajout d'un fichier. Pour savoir si il y à des fichiers ou dossier a add et commit.
- `git add:` Sert à préparer mes fichiers pour les commits et les push
- `git commit:` Sert à sauvegarder les changements.
- `git push:` Sert à pousser mon projet, mes changements, modifications vers mon dépôt GitHub.

## Déploiement sur N0C

Je me suis connecter sur N0C avec la commande `ssh ton_user@ton_serveur -p 5022`. J'ai placé mon examen dans un dossier nommé examen-final.

Une fois connecté, j'ai cloner mon dépôt Github avec `git clone` pour pouvoir le récupérer.
J'ai créer le sous-dossier avec le nom edw2-examen-final-joannie.e2495411.webdevmaisonneuve.ca et la racine est `/examen-final`.

Une fois que ca c'est fait j'ai tester mon url et je l'ai mis sur le navigateur. La page d'accueil affichait correctement et mon no apparaissait.

## Réponses théoriques

### Question 1

Le client est le logiciel qui demande quelquechose au serveur, comme ouvrir uen page.
Le serveur est un genre de programme qui recoit et renvoit une page web que ce soit html, css.

`Rôle du navigateur:`

- Envoyer requête au serveur
- Recoit la demande
- Affiche ce que le client lui demande

### Question 2

`Adresse IP :` Adresse numérique quiAdresse IP : Adresse numérique qui sert à identifier une machine.

`Domaine :` C'est le nom qu'on donne a notre adresse IP. Comme un surnom.

`Sous-domaine :` 


### Question 3

>
> - Port 80 : HHTP sa sert à afficher les sites qui sont pas sécurisés
>
> - Port 443 : HTTPS sert à afficher les sites sécurisés
>
> - Port 22 : SSH sert à pouvoir se connecter à serveur à distance.
>

### Question 4

Le HTTPS est important pour un site public, car sa sécurise le site. Les données sont chiffrées et c'est plus difficil de pirater.

### Question 5

SSH est un manière de se connecter à un serveur à distance de facon sécurisée.

### Question 6

Parce que on peut tout simplement faire git clone et récupérer le projet. On ne demande aucun mot de passe ou de clé, tokens.
De plus, il est plus facile pour l'enseignant d'y avoir accès.

## Difficultés rencontrées

Honnêtement, je n'ai pas rencontré de difficultés. Par contre il est vrai que j'ai presque oublier de créer un nouveau remote et j'aurais tout envoyer sur le dépôt du prof.
Ici, l'importance d'utiliser les commandes `git remote -v`, par exemple.

Donc, j'ai juste vérifier que tout mes fichier était dans mon dépôt GitHub et que c'était public. Aussi que mon URL sur N0C affichait correctement sur le navigateur. 
