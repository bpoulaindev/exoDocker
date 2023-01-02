
# Exo Docker


```bash
mkdir exo6 && cd exo6
mkdir www
mkdir db_data
touch docker-compose.yml
docker-compose up -d
mkdir www/apache && cd www/apache && touch dockerfile && touch local.apache.conf
```


## Explications

- Création dockerfile pour configuration custom de apache et lui permettre d'exécuter du code php
- Fichier de configuration local apache, pour ne pas modifier le fichier de conf global

