# HistoStar

Jeu de révision d'histoire en QCM, chapitre par chapitre. On part de 50 points ; les questions ratées reviennent à chaque passe jusqu'à ce que tout soit réussi, et chaque erreur coûte des points. Étoiles selon le score final, modes d'entraînement par niveau, profils de joueurs, record et classement par chapitre.

Chapitres :
- Histoire, chapitre 1 : les empires de la Méditerranée au Moyen Âge (Empire byzantin, Empire carolingien, califat).

En ligne : https://tekio.org/histostar/ — fait partie d'[EduStar](https://tekio.org/edustar/).

## En local

```
python3 -I outils/chapitres_vers_js.py   # vérifie chapitres/ et génère questions-data.js
```

puis ouvrir `index.html`.

## Documentation

`doc/histostar-documentation.md` : fonctionnement du jeu, ajout d'un chapitre, écriture des questions.

## Licence

MIT, voir `LICENCE`.
