# Explorer Boilerplate

## About

This is a boilerplate project template For using D2KLab Explorer.

## Requirements

* [Docker](https://docs.docker.com/engine/)

## How to run

- Download this repository:

```bash
git clone https://github.com/D2KLab/explorer-boilerplate
cd explorer-boilerplate/
```

- Open the file `.env` and edit the variables based on your environment.

- Start in development mode:

```bash
docker compose -f docker-compose.yml -f docker-compose.dev.yml up
```

- Start in production mode:

```bash
docker compose -f docker-compose.yml -f docker-compose.prod.yml up
```

## License

Explorer Boilerplate is [Apache licensed](https://github.com/D2KLab/explorer-boilerplate/blob/main/LICENSE).
