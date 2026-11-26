# Prout'Ours 🛟💨

Une bande de copains descend une rivière sur un radeau gonflable… et leur seul moteur, ce sont leurs prouts !
Jeu de coopération dans le navigateur, de 1 à 4 joueurs (en ligne avec un code à 5 lettres), avec 2 maps : la Vallée et le Canyon.

## Jouer

Ouvre la page du jeu, choisis une map, écris ton pseudo puis :
- **JOUER SEUL** pour t'entraîner ;
- **CRÉER UNE PARTIE** pour obtenir un code à donner à tes amis ;
- **REJOINDRE** avec le code d'un ami.

## Commandes

| Touche | Action |
| --- | --- |
| Espace (maintenir) | prout vers l'avant (là où regarde la caméra) |
| Maj / clic droit | prout vers l'arrière (pour reculer) |
| Z Q S D / flèches | te déplacer sur le radeau (dans ta zone en multijoueur) |
| Clic gauche + souris | tourner la caméra |
| R / bouton ↺ | revenir au dernier point de passage |
| Échap / bouton ☰ | menu pause |
| M | couper / remettre le son |

## Tester sur son ordinateur

```powershell
powershell -ExecutionPolicy Bypass -File serve.ps1
```
puis ouvrir http://localhost:8090

## Crédits

- Fait avec [Three.js](https://threejs.org) et [PeerJS](https://peerjs.com).
- Bruits de prouts (dossier `sounds/`), venant de Wikimedia Commons :
  - `fart2.wav` = « [Human fart.wav](https://commons.wikimedia.org/wiki/File:Human_fart.wav) » par Subhashish Panigrahi, licence [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
  - `fart3.wav` = « [Flatulence.wav](https://commons.wikimedia.org/wiki/File:Flatulence.wav) » par JohnSumisu, licence [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
  - Ces deux fichiers restent sous leur licence d'origine (CC BY-SA).
