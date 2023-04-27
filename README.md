# Psalm Docker

This is the dockerized version of the Psalm CLI. It is forked from the vimeo/psalm-github-actions which is kept up to date and is configured for use with Github Actions. This version eschews that layer and just uses the CLI so that it can be used more easily with Eureka.

## Build
`docker build -t fwdsec/psalm-cli`

I pushed an image to forwardsecurity.azurecr.io/fwdsec/psalm-cli
