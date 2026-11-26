# Installation du moteur

## Prérequis identifiés
- Python 3.10 ou plus récent.
- FFmpeg et FFprobe accessibles depuis le terminal.
- Dépendances du dépôt (`requirements.txt`).
- Les bibliothèques et modèles nécessaires aux effets utilisés.

## Installation indicative
Depuis la racine du dépôt source, examiner puis exécuter le script prévu par le projet :

```bash
bash scripts/setup.sh
```

Puis vérifier les versions :

```bash
python --version
ffmpeg -version
ffprobe -version
```

Le script et les dépendances doivent être relus dans la version du dépôt réellement copiée avant installation. Ne pas lancer de commandes non vérifiées sur un environnement de production.

## Limite
Cette documentation ne signifie pas que le moteur est installé ou testé. Le rendu vidéo nécessite un ordinateur ou serveur disposant des outils requis.
