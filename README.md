# Currency
## Converts the currency based on real-time exchange rates.

## currency (Project Info)
[Website](https://github.com/alexanderepstein/Bash-Snippets)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/currency/)

## Build image
docker build -t macabees/currency:latest .

## Docker Push
`$ docker push -t macabees/currency:latest`

Note: requires `docker login`

## Run image
docker run -it --rm macabees/currency
