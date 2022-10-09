# Airflow-101
## What is Airflow?
Apache Airflow is an open-source platform for developing, scheduling, and monitoring batch-oriented workflows. Airflow’s extensible Python framework enables you to build workflows connecting with virtually any technology. A web interface helps manage the state of your workflows. Airflow is deployable in many ways, varying from a single process on your laptop to a distributed setup to support even the biggest workflows.

Workflows as code
The main characteristic of Airflow workflows is that all workflows are defined in Python code. “Workflows as code” serves several purposes:

* Dynamic: Airflow pipelines are configured as Python code, allowing for dynamic pipeline generation.

* Extensible: The Airflow framework contains operators to connect with numerous technologies. All Airflow components are extensible to easily adjust to your environment.

* Flexible: Workflow parameterization is built-in leveraging the Jinja templating engine.

## Why Airflow?

Airflow is a batch workflow orchestration platform. The Airflow framework contains operators to connect with many technologies and is easily extensible to connect with a new technology. If your workflows have a clear start and end, and run at regular intervals, they can be programmed as an Airflow DAG.

If you prefer coding over clicking, Airflow is the tool for you. Workflows are defined as Python code which means:

Workflows can be stored in version control so that you can roll back to previous versions

Workflows can be developed by multiple people simultaneously

Tests can be written to validate functionality

Components are extensible and you can build on a wide collection of existing components

Rich scheduling and execution semantics enable you to easily define complex pipelines, running at regular intervals. Backfilling allows you to (re-)run pipelines on historical data after making changes to your logic. And the ability to rerun partial pipelines after resolving an error helps maximize efficiency.

Airflow’s user interface provides both in-depth views of pipelines and individual tasks, and an overview of pipelines over time. From the interface, you can inspect logs and manage tasks, for example retrying a task in case of failure.

The open-source nature of Airflow ensures you work on components developed, tested, and used by many other companies around the world. In the active community you can find plenty of helpful resources in the form of blogs posts, articles, conferences, books, and more. You can connect with other peers via several channels such as Slack and mailing lists.

Why not Airflow?
Airflow was built for finite batch workflows. While the CLI and REST API do allow triggering workflows, Airflow was not built for infinitely-running event-based workflows. Airflow is not a streaming solution. However, a streaming system such as Apache Kafka is often seen working together with Apache Airflow. Kafka can be used for ingestion and processing in real-time, event data is written to a storage location, and Airflow periodically starts a workflow processing a batch of data.

If you prefer clicking over coding, Airflow is probably not the right solution. The web interface aims to make managing workflows as easy as possible and the Airflow framework is continuously improved to make the developer experience as smooth as possible. However, the philosophy of Airflow is to define workflows as code so coding will always be required.


## This guide !

This guide is done to help you initiate with airflow orchestration for different workloads.
