# DNAreader — installateurs

Ce dépôt **ne contient aucun code**. Il ne sert qu'à publier les installateurs
de DNAreader, et c'est aussi là que l'application vient voir s'il existe une
version plus récente que la sienne.

**→ [Télécharger la dernière version](../../releases/latest)**

## DNAreader, en deux lignes

Un lecteur de japonais pour jeux vidéo. Il lit le texte à l'écran pendant que
tu joues et affiche la lecture, le sens et le vocabulaire dans une bulle posée
à côté du jeu — sans capture manuelle, sans quitter la partie.

## Installer

Prends `DNAreader-Setup-X.Y.Z.exe` dans la dernière version et lance-le. Aucun
droit administrateur n'est demandé. Windows 10 ou 11, 64 bits.

Windows affichera « Windows a protégé votre ordinateur » tant que l'application
n'est pas signée : **Informations complémentaires → Exécuter quand même**.

## Vérifier ce que tu as téléchargé

Chaque version publie l'empreinte SHA-256 de son installateur, à côté de lui :

```
certutil -hashfile DNAreader-Setup-1.0.0.exe SHA256
```

C'est la même empreinte que l'application vérifie avant d'installer une mise à
jour. Elle attrape un téléchargement tronqué ou un mauvais fichier — elle ne
remplace pas une signature de code.

## Licences

Dictionnaire **JMdict** de l'[EDRDG](https://www.edrdg.org/), sous licence
CC BY-SA 4.0. Le fichier `NOTICE.md` accompagne chaque copie.
