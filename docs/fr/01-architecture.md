# 1. Architecture — Polymarket Neg Risk CTF Adapter

Ce dépôt rassemble les composants de référence consacrés à l’adaptation des jetons conditionnels aux marchés à risque négatif de Polymarket.
La lecture commence par le README, puis suit les modules de production et leurs interfaces publiques.
Les répertoires séparent le cœur du protocole, les outils d’intégration et les scénarios de vérification.
Chaque couche possède ses propres types, règles d’état et frontières de confiance.
Les entrées externes sont transformées en opérations internes avant de modifier l’état persistant.
Les erreurs et événements rendent visibles les refus et les transitions importantes.
Les bibliothèques partagées évitent de dupliquer les primitives communes entre composants.
Cette architecture doit être lue avec les choix de configuration propres à chaque déploiement.

[Chapitre suivant : Préparation des conditions et marchés](02-preparation-des-conditions-et-marches.md)
