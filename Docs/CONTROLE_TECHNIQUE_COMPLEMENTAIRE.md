# Contrôle technique complémentaire

## Éléments identifiés dans le dépôt source
- `scripts/fx.py` : moteur contenant 51 décorateurs `@effect`.
- `scripts/setup.sh` : script d’installation et de vérification.
- `scripts/words.py` : traitement de mots/transcriptions, avec composants optionnels.
- `requirements.txt` : dépendances Python.
- `models/` : modèles de segmentation et de détection.
- `fonts/` : polices et avis de licence.

## Environnement
Le script d’installation source mentionne Python 3.10+, FFmpeg et FFprobe. Il vérifie notamment des imports comme MediaPipe, OpenCV, Pillow et NumPy.

## Points de vigilance
- `faster-whisper` et `mlx-whisper` sont des composants optionnels liés à `words.py`, pas à supposer installés dans l’environnement minimal.
- Ne pas remplacer aveuglément toutes les occurrences du mot « Claude » : certaines peuvent être du texte d’exemple ou des références historiques.
- Vérifier séparément les licences des modèles et des polices.
- Effectuer les tests sur un environnement réel avant d’annoncer une compatibilité.
