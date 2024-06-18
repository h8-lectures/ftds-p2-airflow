# Airflow

Apache Airflow is an open-source platform for developing, scheduling, and monitoring batch-oriented workflows.

Key features:

- Airflow pipelines are configured as Python code, allowing for dynamic pipeline generation.
- Airflow contains operators to connect with numerous technologies.
- Workflow parameterization is built-in leveraging the Jinja templating engine. ([read more](https://airflow.apache.org/docs/apache-airflow/stable/core-concepts/operators.html#jinja-templating))

## Requirements

- Docker

## Setup

- Clone this repo.
- Make sure docker is already running.
- Run the following command.

    ```bash
    docker-compose -f airflow_lite.yaml up -d
    ```

## References

- Official Documentation <https://airflow.apache.org/docs/apache-airflow/stable/index.html>
- Running Airflow in Docker <https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html>
