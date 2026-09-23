# pse-bercy

Révision des stratégies et rapports d'activité de la DGFiP et des directions des ministères économiques et financiers.

25 modules, consultables depuis l'application de révision
https://guiraudjb.github.io/PSE25-27/ (ce dépôt en fournit les données via GitHub Pages).

## Séries

- **02** : Bercy Vert
- **04** : DGFiP : rapport, SDNum, facturation électronique
- **05** : Stratégie DGFiP 2023-2027
- **08** : Directions de Bercy : rapports d'activité

## Contenu par module

Chaque module `<nom>` dispose de : `fiche/<nom>.txt`, `quizz/<nom>.csv`,
`flashcard/<nom>.csv`, éventuellement `tp/<nom>.csv`, et des médias
`podcast/<nom>.m4a`, `infographie/<nom>.png`, `chanson/<nom>.mp3` (+ paroles
`.txt`) et `fiche_audio/<nom>.mp3` (narration de la fiche). La liste des
modules est dans `modules.json`.

## Jeu Batocera

`batocera/pse-bercy/` contient le jeu pygame jouable à la manette, déployé par
`batocera/deploy.py`. Le moteur est commun à tous les dépôts : il se modifie
dans le modèle de l'espace de travail puis se synchronise, jamais ici.
