# DjangoLaunchpad

### Automatiser la création et le déploiement de projets Django 🚀


DjangoLaunchpad est un outil CLI qui permet de :

- Générer automatiquement un projet Django préconfiguré.

- Ajouter des apps personnalisées comme `blog`, `api`, etc.

- Déployer le projet sur un serveur distant via SSH ou Docker.

---

## Fonctionnalités principales

1. **Génération automatique de projets Django**

  - Créez un projet Django avec une structure standardisée et des apps préinstallées.


2. **Automatisation du déploiement**

  - Déployez rapidement sur un serveur distant grâce à SSH ou Docker.

3. **Interface en ligne de commande intuitive**

  - Exemple de commandes :

   ```bash

   django-launch create --name my_project --apps blog,auth

   django-launch deploy --host 192.168.1.10 --user root

   ```
---

## Installation

1. Clonez le dépôt GitHub :

  ```bash

  git clone https://github.com/ton_nom/DjangoLaunchpad.git

  cd DjangoLaunchpad

2. nstallez les dépendances :

```bash

pip install -r requirements.txt

```

3.Lancez l’outil :

```bash

python django_launch.py

```