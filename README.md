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

Now you can access Metabase at http://localhost:3000/
### Metabase Setup

**Sharing Data**: After running docker compose, we got all the metabase data in `db-data/` which indeed postgresql data folder. We could use this folder to share metabase data. (create `db-data/`([Download here](https://file.io/M1YBPOXkR3fI)) first before running docker compose).
```
email: example@example.com
password: IloveMetabase123@
```

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






    






