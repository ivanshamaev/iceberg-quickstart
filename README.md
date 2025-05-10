# iceberg-quickstart
Тестовый проект с iceberg, spark, iceberg-rest

## Предварительная настройка
Source: [https://iceberg.apache.org/spark-quickstart/](https://iceberg.apache.org/spark-quickstart/) - отсюда берем файл docker-compose.yml
В него прописываем локальные креды (логин/пароль и т.д.)

Запускаем установку
```
sudo docker-compose up
```

## Jupyter Server
[http://localhost:8888/tree](http://localhost:8888/tree) - Jupyter скачиваются сюда notebooks:
- Iceberg - An Introduction to the Iceberg Java API.ipynb
- Iceberg - Berlin Buzzwords 2023.ipynb
- Iceberg - Getting Started.ipynb
- Iceberg - Integrated Audits Demo.ipynb
- Iceberg - Table Maintenance Spark Procedures.ipynb
- Iceberg - View Support.ipynb
- Iceberg - Write-Audit-Publish (WAP) with Branches.ipynb
- PyIceberg - Getting Started.ipynb
- PyIceberg - Write support.ipynb

## Minio
- [http://127.0.0.1:9001](http://127.0.0.1:9001) - WebUI