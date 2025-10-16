# GmailJobParser

Ce projet fournit un script Python capable de récupérer vos emails de candidatures, d’analyser leur contenu et d’extraire les informations essentielles pour suivre vos candidatures : poste, entreprise, date et statut (envoyée, entretien, refusée). Les informations extraites sont ensuite stockées dans une base de données PostgreSQL.

Fonctionnalités:

Connexion sécurisée à Gmail via l’API Google avec OAuth 2.0.

Extraction automatique des informations clés dans l’email : Poste Entreprise Date de réception Statut : envoyée, entretien, refusée, ou en attente.

Utilisation de spaCy pour la reconnaissance d’entités nommées (NER) en français.

Analyse du contenu des emails pour catégoriser automatiquement le statut.

Insertion des informations directement dans une table PostgreSQL (candidatures).

Prérequis

Python 3.8+ Google API Credentials (credentials.json) Bibliothèques Python : pip install google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client spacy psycopg2-binary python -m spacy download fr_core_news_md

Technologies:

Python 3
Google Gmail API
spaCy (NLP en français)
PostgreSQL
Auteur: Rafael BARRETO PANNETIER
