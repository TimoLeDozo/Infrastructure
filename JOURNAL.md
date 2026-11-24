# Journal

Les étapes datées du dépôt privé, publiées sans topologie. Commits du dépôt privé : <!-- mesure:rythme -->10 en juillet, 52 en août, 220 en septembre, 60 en octobre, 625 en novembre<!-- /mesure -->.

| Date | Ce qui a changé |
|---|---|
| 24/11/2026 | Les scanners de sécurité du sas d'entrée ignorent désormais les liens symboliques d'un clone, et la purge des branches crée par défaut une sauvegarde datée du jour. Deux branches de travail d'agents IA ont aussi été fusionnées (7 fichiers) avec des tests verts. |
| 23/11/2026 | Les sondes de nuit nomment la cause d'un échec au lieu d'un simple rouge. Une sonde signale les routines de sécurité non inscrites, l'audit échoue si la boîte à outils manque, et un 204 sans corps de GitHub n'est plus une panne réseau. |
| 22/11/2026 | Un modèle auto-hébergé résume un long fichier en une commande, sans consommer de quota (20 Ko de journal en 10 s). Sa sortie est plafonnée à 16 384 jetons depuis qu'une génération sans limite l'a bloqué 2 h 40. |
| 21/11/2026 | Le banc de test vérifie qu'un processus tué entraîne la fin de son processus petit-enfant, durée relevée. Les sauvegardes Restic attendent un verrou concurrent et lèvent les verrous périmés avant la rétention. Une ouverture Instagram hors délai est retentée une fois, puis bloque proprement. |
| 20/11/2026 | Une sonde de supervision rend désormais « inconnu » et non « en panne » quand un outil reste muet au-delà du délai. La reprise automatique de Claude après une limite d'usage vise la première minute disponible et évite les doublons. |
| 19/11/2026 | Les sessions Claude reprennent seules la même conversation après une limite d'usage, et une garde protège la copie principale du dépôt git. Les tests de la dernière fusion donnent 4991 réussites et 17 échecs propres à l'environnement de travail isolé. |
| 17/11/2026 | Veille technologique automatisée : le juge des fiches traite 60 fiches par passage au lieu de 10, ne rejuge plus celles déjà tranchées par règle, et une règle écarte les sources stériles avant lui. |
| 16/11/2026 | Deux changements issus de branches nocturnes sont repris, le dossier temporaire racine est exclu de l'instantané quotidien, la vérification à 7 jours d'une extension d'agent de cadrage d'objectifs est passée, et la mise à jour du 15/11 a tourné avec le modèle Opus de secours. |
| 15/11/2026 | Sonde de non-usage à 30 jours : mise en réserve proposée pour un serveur MCP (connecteur d'outils d'IA) inutilisé. Routine d'auto-amélioration claude-update exécutée le 15 novembre, avec repli sur le modèle Opus. |
| 13/11/2026 | Huit branches nocturnes d'agents IA fusionnées automatiquement après tests verts, et un refus du garde-fou de pré-commit ne laisse plus la branche indexée dans l'arbre de travail. Tests de la forge Git auto-hébergée : 11 échecs corrigés, 130 verts. |
| 12/11/2026 | Trois lots fusionnés, dont le routage des jobs et le sas de scanners de sécurité, écrits par un agent IA et relus par un second. Script prêt pour Forgejo (forge Git auto-hébergée), limité à pousser les branches d'agents. |
| 11/11/2026 | Cinq ruptures corrigées dans la chaîne de mise à jour automatique du système de veille, après audit. Le modèle de synthèse vocale Kokoro-82M est admis comme challenger, soit candidat comparé au modèle en place. |
| 10/11/2026 | Recherche documentaire du projet Hub : objectif atteint sur une branche d'essai, MRR (qualité du classement) de 0,861. Le routeur d'outils propose le radar de veille dès trois liens dans un message, et la sonde de la file de décisions humaines suit le vrai lanceur. |
| 09/11/2026 | Le tableau de bord de pilotage de l'infrastructure s'affiche désormais en 16 secondes au lieu de 4 min 40, et les quotas d'usage ainsi que les sondes de santé y sont de nouveau lisibles. |
| 25/10/2026 | Relecture critique des sessions quatre fois par semaine par le juge. Note sur 20 des 244 modules, maison et tiers sur la même grille. Sas d'entrée gradué. Missions confiées à l'exécutant en une commande, avec reçu mesuré |
| 16/10/2026 | Travail de nuit v2. Garde anti-suppression commune au pilote et à l'exécutant, qui refuse aussi quand elle tombe en panne |
| 02/10/2026 | Supervision de disponibilité sur la station GPU, images compilées pour ARM64 |
| 29/09/2026 | Décisions arbitrées par un banc d'options, file de décisions appliquée chaque jour |
| 27/09/2026 | Objectifs de service relus fiche par fiche : 118 annoncés, 12 réels, le reste retiré |
| 12/09/2026 | Veille qui recoupe compétences, plugins, serveurs MCP et hooks déjà en place |
| 11/09/2026 | Pont entre le pilote et l'exécutant, ménage des extensions |
| 07/09/2026 | Première publication de cette vitrine |
| 05/09/2026 | Profils GPU jour et nuit, atelier isolé pour le travail de nuit |
| 02/09/2026 | Miroirs git nus : l'historique existe hors du poste de travail |
