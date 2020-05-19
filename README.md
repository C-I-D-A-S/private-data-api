# private-data-api

An API component to handle data retrieve and receive

## Getting Started

### Prerequisites

- python 3.7.3
- pipenv 2018.11.26
- docker 18.09.2
- Postgre 11

### Running Development

Installing Packages & Running

```lan=shell

pipenv --python 3.7
pipenv install --dev

pre-commit install

pipenv run data_api/main.py
```

### Running Production

1. update the .env file
2. run docker container

```lan=shell
docker-compose up -d
```
