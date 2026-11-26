# Prout'Ours 🍩💨

Des oursons sur une bouée-donut descendent une rivière… et leur seul moteur, ce sont leurs prouts !
Jeu de coopération dans le navigateur, de 1 à 4 joueurs (en ligne avec un code à 5 lettres).

## Jouer

Ouvre la page du jeu, écris ton pseudo puis :
- **JOUER SEUL** pour t'entraîner ;
- **CRÉER UNE PARTIE** pour obtenir un code à donner à tes amis ;
- **REJOINDRE** avec le code d'un ami.

## Commandes

| Touche | Action |
| --- | --- |
| Espace (maintenir) | péter : pousse la bouée depuis l'endroit où tu es assis |
| Z Q S D / flèches | te déplacer autour de la bouée |
| E / clic droit | te retourner (péter dans l'autre sens) |
| Clic gauche + souris | tourner la caméra |
| R | revenir au dernier point de passage |
| M | couper / remettre le son |

## Tester sur son ordinateur

```powershell
powershell -ExecutionPolicy Bypass -File serve.ps1
```
puis ouvrir http://localhost:8090

Fait avec [Three.js](https://threejs.org) et [PeerJS](https://peerjs.com).
