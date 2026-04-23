# MSPR1-Project

Base de données, api, interface admin, ETL
-> Entièrement dockerisé, les .env sont volontairement ajoutés au git pour pouvoir tester rapidement le projet.

Structure technique:
- Base de données PostgreSQL
- API Laravel
- ETL Python -> injection de données depuis des fichiers csv
- Interface admin React -> CRUD des tables principale de la base de données et import des csv pour l'ETL
- Graphiques et stats Grafana
