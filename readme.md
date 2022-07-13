## Run with -

`docker run --env LOG_LEVEL=debug RENOVATE_BINARY_SOURCE=docker -it --rm -v "<path>\config.js:/usr/src/app/config.js" -v //var/run/docker.sock:/var/run/docker.sock renovate/renovate:latest`
