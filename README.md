# Hotel VR · escape game d'enquête en réalité virtuelle

Projet de Master Sciences et Technologies du Métavers (INSA Hauts-de-France), en équipe de 3. Le joueur fouille un hôtel, résout des énigmes physiques et reconstitue l'enquête jusqu'à la cinématique de fin.

Dépôt d'origine : [Nic-del/Hotel-repo](https://github.com/Nic-del/Hotel-repo). Cette branche `ziyad` contient ma partie.

## Ma partie : la salle de contrôle

Scripts dans `Assets/Import/control-room/scipt/` :

| Script | Rôle |
|---|---|
| `CassettePlayer.cs` | Insérer une cassette tenue en main dans le lecteur déclenche l'enregistrement audio |
| `ElectricalBoxPuzzle.cs` | Énigme du boîtier électrique |
| `MaterialPuzzle.cs` | Énigme basée sur les matériaux des objets |
| `VentBreaker.cs` | Ouverture de la grille d'aération |
| `EndGameCinematic.cs` | Fondu au noir, téléportation du joueur, apparition du policier et de son dialogue, blocage des déplacements, puis scène suivante |

La salle utilise aussi un digicode VR (`Assets/Keypad/`, toucher des touches avec la main).

## Stack

Unity 6 (6000.3), URP, XR Interaction Toolkit 3, OpenXR, XR Hands, C#.

## Lancer

1. Cloner le dépôt et passer sur la branche `ziyad`.
2. Ouvrir le dossier avec Unity Hub (Unity 6000.3).
3. Casque compatible OpenXR (Quest via Link par exemple), puis Play.
