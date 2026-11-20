# Vitrine du profil GitHub

README affiché sur la page du profil GitHub. Il présente les projets sans exposer leur code.

## Règle n°1 : ne jamais perdre de données (aucune, zéro)

Le dépôt GitHub **public** `olivierbasile/olivierbasile` est la sauvegarde de ce projet. Le dossier de travail est `C:\Users\olivi\Projets\olivierbasile`. Ne jamais travailler dans un dossier temporaire.

- **Committer et pousser souvent** : après chaque modification qui fonctionne, faire `git add -A`, `git commit` (message clair en français), puis `git push`. Ne jamais finir une session ou un tour de travail avec des modifications non poussées. En cas de doute, pousser.
- **Faire de petits commits** : un commit par changement logique, plutôt qu'un gros commit en fin de journée.
- **Pas d'opération destructrice sans accord explicite de l'utilisateur** : `git push --force`, `git reset --hard`, `git clean`, `git checkout -- <fichier>` ou `git restore` sur des fichiers modifiés, un rebase qui réécrit l'historique déjà poussé, la suppression de branches ou de tags.
- **Avant de supprimer ou d'écraser un fichier**, vérifier qu'il est commité. Préférer renommer ou déplacer dans un dossier `archives/`.
- **Les fichiers produits sont des données** (audio, vidéo, images, PDF, documents) : les committer aussi. GitHub refuse les fichiers de plus de 100 Mo. Au-delà, prévenir l'utilisateur et passer par Git LFS, sans jamais supprimer le fichier.
- **Aucun secret dans le dépôt** (clés d'API, mots de passe, jetons) : ils vont dans `.env` (ignoré par git). Tenir à jour `.env.example` avec les noms des variables, sans valeurs.
- **Si un push échoue** (conflit, réseau), le dire tout de suite à l'utilisateur et régler le problème avant de continuer. Pour un conflit, faire `git pull` (fusion) et ne jamais forcer.
- **Tester en local avant de mettre en ligne** : le serveur local du projet sert à vérifier les changements, il n'y a pas besoin de pousser pour tester.

## Lancer en local

Rien à lancer : c'est un README.

## Mise en ligne

Un push sur `main` met à jour la page du profil immédiatement. **Ce dépôt est public** : rien de privé ici.
