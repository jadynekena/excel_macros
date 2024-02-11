# Colonnes communes
Vous avez plusieurs fichiers excel (ou csv) qui ont des colonnes différentes selon les années, et vous aimeriez ne garder que les colonnes communes ? J'ai créé une macro toute faite sur Excel qui permet de le faire, et ce pour n'importe quelles données datées.

# Split text
Il y a 2 onglets :
- `ORIGINAL`: où l'on a les données d'origine
- `FINAL`: où l'on aura le retraitement des données selon la procédure ci-dessous (spliter)

Il y a 3 actions possibles.

## a) effacer_final
Efface le contenu de l'onglet `FINAL`. Attention, l'acion est irréversible.

## b) effacer_original
Efface le contenu de l'onglet `ORIGINAL`. Attention, l'acion est irréversible.

## c) spliter
A partir de l'onglet `ORIGINAL`, une petite fenêtre apparaît. Il faut choisir:
- Le champ de texte à analyser
- Les autres champs à garder pendant le formatage
Les données finales sont ensuite stockées dans l'onglet `FINAL`.

