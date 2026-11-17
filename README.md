# Projet de programmation Web

Projet réalisé dans le cadre du cours de Programmation Web (ENSISA, année
2026-2027).

## Présentation

Le projet consiste à développer une application Web avec **Django côté serveur**
et **JavaScript côté client**. Le sujet proposé dans l'énoncé est un chat
centralisé avec des salons de discussion.

L'application doit notamment permettre l'inscription et la connexion des
utilisateurs, gérer les droits et proposer des outils de modération. Les
fonctionnalités complémentaires (par exemple les profils, les émojis ou le mode
jour/nuit) sont à définir par le groupe.

> Le dépôt contient actuellement le squelette initial du projet Django. Les
> fonctionnalités du chat restent à développer.

## Technologies

- Python et Django pour le serveur
- JavaScript pour le client
- JQuery et Bootstrap peuvent être utilisés conformément aux consignes du cours

L'énoncé interdit les autres bibliothèques et frameworks.

## Structure du dépôt

```text
.
├── backend/
│   ├── manage.py
│   └── prog_web/       # Configuration et routes Django
├── frontend/           # Fichiers client à développer
└── Projet.pdf          # Énoncé du projet
```

## Installation et lancement

Initialisez la base de données puis démarrez le serveur de développement :

```bash
cd backend
python manage.py migrate
python manage.py runserver
```

Le site sera accessible à l'adresse [http://127.0.0.1:8000/](http://127.0.0.1:8000/). Pour créer un
compte administrateur Django :

```bash
python manage.py createsuperuser
```

L'interface d'administration est disponible à [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/).

## Travail d'équipe et rendu

Le projet est à réaliser en trinôme. Le rendu demandé comprend le code, un
rapport présentant les fonctionnalités (avec captures d'écran et explications)
et l'adresse du serveur hébergeant l'application. Consultez [Projet.pdf](Projet.pdf)
pour les consignes complètes et les échéances.
