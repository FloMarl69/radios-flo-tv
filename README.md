# Radios by Le Site de Flo sur Android TV

[![Dernière version](https://img.shields.io/github/v/release/FloMarl69/radios-flo-tv?label=APK)](https://github.com/FloMarl69/radios-flo-tv/releases)
[![Android 7.0+](https://img.shields.io/badge/Android-7.0%2B-3ddc84)](#compatibilité)

Application **Android TV / Google TV** pour écouter **132 radios en direct**, gratuitement et sans inscription, entièrement à la télécommande. Elle donne accès au site web [Radios by Le Site de Flo](https://lesitedeflo.floinfo38.com).

## Ce que permet l'application

132 stations réparties en 11 catégories, à parcourir comme un carrousel :

| Catégorie | Stations |
|---|---|
| Métropolitain M1 et M2 | 26 radios nationales : NRJ, RTL, France Inter, Europe 1, Nostalgie, Skyrock, FIP, RMC… |
| Étendu ou Local (1 et 2) | 19 radios étendues ou locales : Alpes 1, Sud Radio, TSF Jazz, Virgin Radio… |
| Ici (1, 2 et 3) | 45 radios régionales du réseau « Ici » |
| Locales et Autres Pays | 5 radios locales et d'autres pays |
| Webradios | 14 webradios : rock, rap, reggae, classiques… |
| 100 % Artistes (1 et 2) | 23 radios dédiées à un artiste ou un groupe |

- Écoute en direct, lancement d'une radio en un appui sur OK.
- Retour automatique du son après une coupure du réseau.
- La dernière radio écoutée est mémorisée.
- Touches média de la télécommande (lecture, pause, stop).
- L'écran reste allumé pendant l'écoute.
- Le volume se règle avec la télécommande de la TV.

Une connexion Internet est nécessaire. Les flux sont ceux des diffuseurs ; l'application ne les héberge pas.

## Installer

1. Télécharger `radios-flo.apk` depuis la [page des releases](https://github.com/FloMarl69/radios-flo-tv/releases).
2. Sur la TV, activer le mode développeur (`Paramètres > Système > À propos`, 7 appuis sur « Build »), puis le débogage USB/ADB.
3. Depuis un ordinateur sur le même réseau :

```bash
adb connect IP_DE_LA_TV:5555
adb install -r --user 0 radios-flo.apk
```

Sans ordinateur : application « Downloader » sur la TV et lien direct vers l'APK. L'icône **Radios Flo** apparaît ensuite parmi les applications de l'accueil.

## Télécommande

| Zone | Touches |
|---|---|
| Lecteur | flèches pour passer de la radio au bouton Stop, OK pour relancer ou arrêter |
| Titre de catégorie | → déplier, ← replier, ↓ entrer dans le carrousel |
| Carrousel | ←/→ faire tourner, OK écouter, ↑ revenir au titre |
| Retour | replie la catégorie, remonte au lecteur, double appui pour quitter |
| Touches média | lecture/pause, stop |

## Compatibilité

- Android TV / Google TV, Android 7.0 (API 24) ou plus, avec « Android System WebView » à jour.
- Testée sur des TV Xiaomi. Installable aussi sur téléphone, mais conçue pour la TV.

## Avertissement et licence

- **Les noms, logos et flux audio des stations appartiennent à leurs ayants droit.** L'application ne retransmet aucun flux : elle se connecte aux adresses publiques des diffuseurs.
- Application  © 2026 [Flo Info 38](https://www.floinfo38.fr) — tous droits réservés, sauf mention contraire dans un fichier `LICENSE`.
- Politique de confidentialité : <https://www.floinfo38.fr/politique-de-confidentialite>

Un bug, une radio à proposer ? Ouvrez une *issue*.
