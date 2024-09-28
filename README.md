# Gcloud Command Playgorund

This is a playground for testing gcloud commands.

## Prerequisites

We need to have the following tools installed:

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Usage

1. Clone this repository
2. Change directory to the repository
3. Put your gcloud credentials in the `credentials` folder as `credentials/credentials.json`
4. Run `docker compose up`
5. Run `docker compose exec gcloud bash` to enter the container

## Examples

Run the following commands to login to your gcloud account:

```shell
# Change directory to the repository
cd gcloud_playground

# Build and run the container
docker compose up -d --build

# Enter the container
docker compose exec gcloud bash

# Set the project id
gcloud config set project {your-project-id}

# Login to your gcloud account
gcloud auth login
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
