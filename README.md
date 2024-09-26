# Gcloud Command Playgorund

This is a playground for testing gcloud commands.

## Prerequisites

- Docker
- Docker Compose

## Usage

1. Clone this repository
2. Run `docker compose up`
3. Run `docker compose exec gcloud bash` to enter the container

## Examples

```shell
docker compose up -d --build
docker compose exec gcloud bash
gcloud config set project {your-project-id}
gcloud auth login
```
