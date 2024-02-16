# lite-camonda-compose
## docker-compose.yml for Camunda Platform (Tomcat) 7

### For setup:

    For setup with PostgreSQL:
    # docker compose up -d
    or with MySQL:
    # docker compose --profile mysql up -d
    or
    # COMPOSE_PROFILES=<prof_type> docker compose up
    
    where <prof_type>:
        mysql -> select profile with DB type MySQL
        pgsql -> select profile with DB type PostgreSQL
