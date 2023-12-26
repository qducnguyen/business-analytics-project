# Business Analytics Project Group 05 DSAIK65 

## Introduction 

Tourism is one of the fastest-growing industries in the world. With the introduction of hashtags like ‘#wanderlust’, there has been an increasing amount of interest among people of different demographics to explore new places. However, this industry has very fluctuating numbers in terms of sales, and different places have different feelings according to the time of the year. 

Hence, tourism forecasting has become an increasingly important task in planning, improving, and managing the industry. There is a lot of information and insights that are hidden in the data retrieved from the tourism industry. You can use techniques like data clustering to understand when and where tourists prefer to go, what they like at each location, the mode of transportation of tourists while travelling between spots, etc. 

Using insights like the above, we need to forecast the revenue for the upcoming year. We used tourism data from [Thai Official Ministry of Tourism and Sports Statistics](https://www.mots.go.th/news/category/411) for this project.

## Installation 
We use Python 3.10 for this project. To install python environment:
```
pip install requirements.txt
```

### Metabase Deployment 
```
docker compose -f deploy/metabase-postgres.docker-compose.yml up -d  // start and run docker compose metabase-postgres
docker compose -f deploy/metabase-postgres.docker-compose.yml down -v // remove docker compose metabase-postgres
docker compose -f deploy/metabase-postgres.docker-compose.yml stop  // stop docker compose metabase-postgres
docker compose -f deploy/metabase-postgres.docker-compose.yml start  // start docker compose metabase-postgres
```

Now you can access Metabase at http://localhost:3000/
### Metabase Setup

**Using Shared Data**: After running docker compose, we got all the metabase data in `db-data/` which indeed postgresql data folder. We could use this folder to share metabase data. (create `db-data/`([Download here](https://file.io/M1YBPOXkR3fI)) first before running docker compose).
```
email: ducnq.204876@sis.hust.edu.vn
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






    






