# bat

> Affiche et concatène le contenu d'un ou plusieurs fichiers.
> Un clone de `cat` avec mise en valeur de la syntaxe et intégration avec Git.
> Plus d'informations : <https://github.com/sharkdp/bat>.

- Affiche le contenu d'un fichier sur la sortie standard :

`bat {{fichier}}`

- Concatène le contenu de plusieurs fichiers vers le fichier de destination :

`bat {{fichier1}} {{fichier2}} > {{fichier_de_destination}}`

- Ajoute le contenu d'un ficher à la fin du fichier de destination :

`bat {{fichier1}} {{fichier2}} >> {{fichier_de_destination}}`

- Numérote toutes les lignes affichées :

`bat {{[-n|--number]}} {{fichier}}`

- Affiche le contenu d'un fichier JSON sur la sortie standard avec mise en valeur de la syntaxe :

`bat {{[-l|--language]}} json {{chemin/vers/fichier.json}}`

- Affiche tous les langages pris en charge :

`bat {{[-L|--list-languages]}}`
