# Format de plan JSON

Un plan décrit une vidéo et une suite de séquences. Les champs proposés ci-dessous forment un format de travail initial pour organiser les intentions ; ils ne prétendent pas être une API native du moteur source tant que le raccordement n’a pas été implémenté.

## Champs
- `project`: nom du projet.
- `output`: paramètres de sortie.
- `clips`: liste ordonnée des séquences.
- `effect`: identifiant canonique de l’effet.
- `params`: paramètres propres à l’effet, à confirmer dans le code.

Voir `exemple_plan.json`.
