# Apache Airflow Docker Compose
Docker Composer utilizado para criação do Apache Airflow Localmente para uso de laboratório.


## Pré Requisitos
- Sistema Operacional Linux ou MacOs
- git               - https://git-scm.com/downloads
- docker            - https://docs.docker.com/get-docker/
- docker compose    - https://docs.docker.com/compose/install/

## Setup
```
git clone https://github.com/danilosousadba/impacta.git
```
```
mkdir -p /opt/airflow/dags /opt/airflow/logs /opt/airflow/plugins /opt/airflow/data
```
```
cd impacta-dataops-airflow
```
```
docker-compose up -d
```
## Default url
http://localhost:8080

## Default Username
airflow

## Default Password
airflow
