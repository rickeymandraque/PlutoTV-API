# PlutoTV API Reverse Engineering Exploration

## ⚠ Readme en cours d'élaboration ⚠

![PlutoTV Logo](https://theme.zdassets.com/theme_assets/496583/3858e8e3a2863ec7bb974be916d374968f5674d7.png)

**Bienvenue dans le dépôt PlutoTV API Reverse Engineering !**
Ce dépôt vise à fournir une documentation non officielle et des outils pour comprendre et explorer l'API de PlutoTV.  
L'objectif est de comprendre la structure sous-jacente de l'API afin que les développeurs puissent créer leurs propres applications, scripts et outils pour interagir avec le contenu de PlutoTV.

## Contenu du Dépôt

- **Documentation:** Une documentation détaillée sur l'utilisation de l'API de PlutoTV.
- **Utilisation:** Des informations sur la manière d'utiliser les scripts fournis dans le dépôt.
- **Codes d'Erreurs:** Explications sur les codes d'erreurs possibles et leur signification.
- **Exemples de Scripts:** Des exemples de scripts Bash principalement pour interagir avec l'API de PlutoTV.
- **Paramètres:** Une liste complète des paramètres pris en charge par l'API.
- **Liste des Domaines:** Informations sur les domaines utilisés par l'API.
- **Informations:** Autres informations pertinentes sur l'API et son fonctionnement.


## Table des matières

- Introduction
- Motivation
- Structure du dépôt
- Documentation
- Scripts
- Contribution
- Licence

## Introduction

Le dépôt PlutoTV API Reverse Engineering est dédié à l'exploration des points d'extrémité de l'API, des paramètres et des structures de données utilisés par la plateforme PlutoTV. 
PlutoTV est un service de streaming populaire offrant une large gamme de contenus, notamment des chaînes de télévision en direct et des émissions à la demande. 
Ce dépôt sert de ressource pour les développeurs intéressés à comprendre comment accéder et utiliser le contenu de PlutoTV de manière programmatique.

Ce dépôt a été créé dans le but de fournir une documentation non-officielle pour l'API de PlutoTV, une plateforme de streaming de contenu en ligne. 
L'objectif est d'offrir une compréhension plus approfondie de l'API, en particulier pour la création de scripts et de playlists personnalisées pour les flux en direct (live) et les vidéos à la demande (VOD).

L'inspiration pour ce projet est venue d'un script Python trouvé dans le dépôt [Lunatixz/KODI_Addons](https://github.com/Lunatixz/KODI_Addons) et du désir de développer des scripts similaires en utilisant des commandes Bash.

Ce dépôt est dédié à l'ingénierie inversée de l'API de PlutoTV.

J'ai créé cette documentation non officielle car les informations relatives à l'API de PlutoTV sont difficiles à trouver en ligne.

Tout a commencé avec un simple script Python que j'ai découvert [ici](https://github.com/Lunatixz/KODI_Addons/blob/master/plugin.video.plutotv/resources/lib/plutotv.py), ce qui a suscité mon intérêt pour créer mon propre script bash afin de générer des listes de lecture personnalisées pour les flux en direct et les vidéos à la demande (VOD).

Il existe de nombreuses playlists et scripts pour les flux en direct, mais pour les VOD, les options fiables semblent manquer.

Avec l'aide de ChatGPT et de mon terminal, j'ai réalisé que certaines des informations nécessaires pour l'API étaient absentes des sources que j'ai consultées.

J'ai également constaté que la plateforme PlutoTV collectait une quantité considérable d'informations, ce qui est cohérent avec leur modèle économique mais tout de même très dérangeant dans certains cas.

Ce dépôt contiendra également des scripts bash pour faciliter l'utilisation de l'API.


## Motivation

La motivation derrière ce projet est de combler le manque de documentation officielle pour l'API de PlutoTV. Bien que certains scripts et outils existent pour interagir avec le contenu de PlutoTV, une source complète et précise d'informations sur les points d'extrémité de l'API et les paramètres fait souvent défaut. 
Ce dépôt vise à combler cette lacune en fournissant une documentation claire, des exemples et des explications pour l'API de PlutoTV.

## Structure du dépôt

Le dépôt est organisé de la manière suivante :

- `documentation` : Contient des explications détaillées sur les points d'extrémité de l'API, les paramètres de requête et leur signification.
- `scripts` : Comprend des scripts d'exemple écrits dans différents langages de programmation (par exemple, Bash, Python) pour interagir avec l'API de PlutoTV.
- `english` : Contient la documentation et les fichiers en anglais.
- `francais` : Contient la documentation et les fichiers en français.

## Documentation

Le répertoire `documentation` contient des explications détaillées sur les différents points d'extrémité de l'API, les paramètres de requête et leur utilisation prévue. Il inclut des informations sur la manière de construire des requêtes API, d'interpréter les réponses et de tirer le meilleur parti des données disponibles. La documentation est disponible en anglais et en français.

## Scripts

Le répertoire `scripts` contient des scripts d'exemple qui démontrent comment interagir avec l'API de PlutoTV. Ces scripts sont écrits dans différents langages de programmation (mais principalement en bash) et présentent différentes utilisations, telles que la récupération des données des chaînes en direct, la récupération de contenu à la demande et la génération de listes de lecture. Ces scripts peuvent servir de point de départ pour vos propres projets utilisant le contenu de PlutoTV.

## Contribution

Les contributions à ce dépôt sont les bienvenues. 
Si vous avez des connaissances ou des informations supplémentaires sur l'API de PlutoTV, n'hésitez pas à les partager ici. 
Vous pouvez soumettre des pull requests pour ajouter des fonctionnalités, des corrections ou des améliorations à la documentation et aux exemples de scripts.

Les contributions à ce dépôt sont les bienvenues ! 
Si vous avez des idées, des améliorations ou de nouveaux scripts à partager, n'hésitez pas à créer des pull requests. De plus, si vous trouvez des inexactitudes ou des informations manquantes dans la documentation, veuillez nous le faire savoir en ouvrant une issue.

## Travail en Cours (WIP)

Ceci n'est que le début de l'aventure. Je m'efforcerai de mettre à jour et d'enrichir ce dépôt au fur et à mesure de mes découvertes et de mes développements. Vos contributions et suggestions sont les bienvenues.


## Licence

Ce dépôt est destiné à être librement consultable et utilisable par la communauté. Vous êtes encouragé à utiliser les informations et les scripts fournis ici pour vos projets personnels. Si vous utilisez le travail présenté ici, veuillez nous citer et ajouter une référence appropriée à ce dépôt.
Ce dépôt n'est pas sous licence pour le moment, ce qui signifie que vous êtes libre d'utiliser, de modifier et de distribuer le code et la documentation, à condition d'inclure l'avis de licence original.

**Avertissement**: Ce dépôt n'est pas officiellement affilié à PlutoTV. Il s'agit d'un effort communautaire pour comprendre et utiliser l'API de PlutoTV. Utilisez les informations et les scripts fournis de manière responsable et conformément aux conditions d'utilisation et aux politiques de PlutoTV.

**Avertissement:** Ce projet est à des fins éducatives et de recherche. Veuillez respecter les conditions d'utilisation de PlutoTV et n'effectuez aucune action en violation de leurs politiques.
