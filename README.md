# kafka-python

This repository shows how to run Kafka (and Zookeeper) using Docker Compose - for local development only - and how to publish and subscribe to topics using Producers and Consumers written in Python.

## Dependencies

Install the Python package requirements:

    pip install -r requirements.txt

Docker and Docker Compose also required (or a native installation of Kafka and Zookeeper).

## Running

Bring up the Kafka and Zookeeper containers using Docker Compose:

    docker-compose up

Open the example notebook using Jupyter Notebook/Lab.
