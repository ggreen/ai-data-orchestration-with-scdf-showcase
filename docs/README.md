# SCDF Hands on Labs

Required Knowledge

- RabbitMQ
- Postgres
- SQL

Pre-requisite

- Mac/Linux
- [Podman Desktop](https://podman-desktop.io/) 1.20 or higher 
  - [Java 17](https://formulae.brew.sh/formula/openjdk@17)
    Example
    ```shell
    brew install openjdk@17
    ```

- Apache Maven 3.9.1 +
    Example
    ```shell
    brew install maven@3.9)
    ```
- [Curl](https://formulae.brew.sh/formula/curl)
    Example
    ```shell
    brew install curl
    ```

- [Wget](https://formulae.brew.sh/formula/wget)
    Example 
  ```shell
  brew install wget
  ```


In preparement for the labs,
please pull the following podman images.

```shell
podman pull rabbitmq:4.2-management
podman pull postgres:15
podman pull valkey/valkey:latest
```

Also, Optional pull the following for the bonus lab

```shell
podman pull ghcr.io/postgresml/postgresml:2.10.0
```


| Lab                                              | Notes                      |
|--------------------------------------------------|----------------------------|
| [Lab 00](00_Install_SCDF.md)                     | Install_SCDF.md            |
| [Lab 01](01_Batching-Task-Intro.md)              | Batching-Task-Intro        |
| [Lab 02](02_Streaming_Intro.md)                  | Streaming Intro            |
| [Lab 03](03_HTTP_API_to_JDBC_insert.md)          | HTTP API to JDBC_insert    |
| [Lab 04](04_HTTP_API_to_Postgres_sink.md)        | HTTP API to Postgres sink  |
| [Lab Bonus](Bonus_HTTP_SQL_AI_SQL_Enrichment.md) | HTTP SQL AI SQL Enrichment |