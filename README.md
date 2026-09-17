starter_appEm

[![CI Pipeline](https://github.com/Emile943/starter_appEm/actions/workflows/ci.yml/badge.svg)](https://github.com/Emile943/starter_appEm/actions/workflows/ci.yml)

Pipeline CI
Ce dépôt intègre un pipeline d'intégration continue automatisé :
Déclencheurs : exécution automatique sur chaque push vers la branche main et sur chaque pull_request.
Job Lint: analyse statique du code avec flake8.
Job Test: exécution des tests unitaires pytest sur les versions Python 3.10, 3.11 et 3.12 avec mise en cache des dépendances pip et génération d'un rapport de couverture de code HTML conservé en artefact.
