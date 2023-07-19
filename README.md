# Iceberg Playground

## Requirement

- Docker and Docker-Compose

## Development Setup

```
docker compose up -d
```

## Services

- Spark Iceberg
    - Spark Master UI ([http://localhost:8080](http://localhost:8080))
    - Notebook ([http://localhost:8888](http://localhost:8888))
- Iceberg REST
    - API ([http://localhost:8081](http://localhost:8081))
- Minio 
    - Web UI ([http://localhost:8000](http://localhost:8000))
- Minio-MC


## Getting Started
### Entering Spark SQL Shell

```
docker compose exec spark-iceberg spark-sql
```