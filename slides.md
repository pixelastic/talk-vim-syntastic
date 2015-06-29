# Syntastic & Linters

## C'est quoi Syntastic

Passe le code dans un linter/parser et indique où il trouve des erreurs
utilise les librairies dispo sur la machine
par défaut ne fait rien
se content d'appeller le linter sur le fichier, de parser l'output et d'indiquer
dans vim les lignes avce un problème

Par d"faut se lance à la suavegarde
Mode Opt-in ou Opt-out
Configurable pour ajouter des arguments aux commandes

## Exemples de Linter
Rubocop pour Ruby
Impression d'avoir un pro par dessus l'épule qui explique tout
Super utile quand commence dans un langage pour prendre els bonnes habitudes
conventions patagées par la communauté
edge-cases, méthodes deprecated

ShellCheck pour bash
Scsslint, recess
jshint, jslint, eslint

Peut en ajouter plusieurs, si aucune erreur sur le premier, passe au deuxième,
etc

## Next time, auto-fixer
