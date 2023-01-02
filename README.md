
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

- Création d'un fichier docker-compose.yml dans le répertoire de projet avec les services Apache, MySQL et PHP définis et leurs volumes respectifs.
- Démarrage des conteneurs en exécutant la commande docker-compose up -d.
- Précision de la plateforme à exécuter (x86_64, pb compatibilité avec ARM64)
- Accéder à http://localhost sur navigateur redirige sur le contenu du fichier index.php.
- Création dockerfile pour configuration custom de apache et lui permettre d'exécuter du code php
- Fichier de configuration local apache, pour ne pas modifier le fichier de conf global
