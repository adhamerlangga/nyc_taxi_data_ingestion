# NYC taxi data ingestion
getting NYC taxi data from website and transform some data types of column to the correct one, then load it into local postgreSQL

the total data is around 1,369,765 rows, 
postgreSQL is containerized in docker

## Usage
```shell
    python ingest_data.py --user=${your_username} --password=${your_password} --host=localhost --port=5432 --db=${your_db_name} --table_name=${your_table} --url=${url}
```

## Docker Images
docker images can be downloaded on my [docker hub](https://hub.docker.com/repository/docker/harenboy/taxi_ingest/general)
