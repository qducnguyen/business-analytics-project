# Business Analytics Project Group 05 DSAIK65 

## Introduction 

## Project Structure

## Installation 

### Deployment 
```
docker compose -f deploy/metabase-postgres.docker-compose.yml up -d  // start and run docker compose metabase-postgres
docker compose -f deploy/metabase-postgres.docker-compose.yml down -v // remove docker compose metabase-postgres
docker compose -f deploy/metabase-postgres.docker-compose.yml stop  // stop docker compose metabase-postgres
docker compose -f deploy/metabase-postgres.docker-compose.yml start  // start docker compose metabase-postgres
```
### Metabase Setup

**Sharing Data**: After running docker compose, we got all the metabase data in `db-data/` which indeed postgresql data folder. We could use this folder to share metabase data. (create `db-data/` first before running docker compose).

**Running from scratch**:
- Setup your user information
- Setup database: PostgreSQL with settings: 
    ```
    Display name: PostgreSQL
    Host: postgres
    Port: 5432
    Database name: metabase
    Username: metabase
    Password: metabase
    ```






    






