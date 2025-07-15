# Déploiement WordPress + MySQL avec Docker Compose

Ce projet permet de déployer facilement une instance WordPress avec une base de données MySQL en utilisant Docker Compose.

## Prérequis

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/)

## Installation

1. **Clonez ce dépôt (si vous l'avez publié sur GitHub)**
   ```bash
   git clone https://https://github.com/phbarbe/wordpress-docker.git
   cd wordpress-docker

## Variables d'environnement (.env)

| Variable                | Description                                         | Exemple                        |
|-------------------------|-----------------------------------------------------|--------------------------------|
| WORDPRESS_DB_HOST       | Hôte et port de la base MySQL (service Docker)      | wordpress_db:3306              |
| WORDPRESS_DB_NAME       | Nom de la base de données WordPress                 | wordpress                      |
| WORDPRESS_DB_USER       | Utilisateur MySQL pour WordPress                    | wordpress                      |
| WORDPRESS_DB_PASSWORD   | Mot de passe pour l’utilisateur MySQL de WordPress  | monbeausapin                   |
| MYSQL_DATABASE          | Nom de la base créée par MySQL                      | wordpress                      |
| MYSQL_USER              | Utilisateur MySQL                                   | wordpress                      |
| MYSQL_PASSWORD          | Mot de passe de l’utilisateur MySQL                 | roidesforets                   |
| MYSQL_ROOT_PASSWORD     | Mot de passe root de MySQL                          | quejaimetaverdure              |
