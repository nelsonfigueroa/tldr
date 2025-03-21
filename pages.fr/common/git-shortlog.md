# git shortlog

> Récapitule la sortie de `git log`.
> Plus d'informations : <https://git-scm.com/docs/git-shortlog>.

- Afficher un résumé de tous les commits effectués, regroupés par ordre alphabétique par nom d'auteur :

`git shortlog`

- Afficher un résumé de tous les commits effectués, regroupés par le nombre de commits effectués :

`git shortlog {{[-n|--numbered]}}`

- Afficher un résumé de tous les commits effectués, regroupés par le nom et l'email de l'utilisateur :

`git shortlog {{[-c|--committer]}}`

- Afficher un résumé des 5 derniers commits effectués :

`git shortlog HEAD~5..HEAD`

- Afficher tout les utilisateurs, emails et le nombre de commits dans la branche :

`git shortlog {{[-s|--summary]}} {{[-n|--numbered]}} {{[-e|--email]}}`

- Afficher tout les utilisateurs, emails et le nombre de commits dans toutes les branches :

`git shortlog {{[-s|--summary]}} {{[-n|--numbered]}} {{[-e|--email]}} --all`
