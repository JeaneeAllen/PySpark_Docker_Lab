# PySpark Docker Lab

## Overview

This project demonstrates how to set up and run PySpark using Docker, Jupyter Notebook, and VS Code.

## Tech Stack

* Docker
* PySpark
* Jupyter Notebook
* VS Code

## Setup Instructions

1. Start the container:

```
docker compose up -d
```

2. Get the Jupyter token:

```
docker logs pyspark-jupyter
```

3. Open the notebook and connect to:

```
http://localhost:8888/?token=...
```

## Key Features

* Runs PySpark in a containerized environment
* Avoids local Java installation
* Uses mounted volumes for persistent storage

## Author

Jen Allen
