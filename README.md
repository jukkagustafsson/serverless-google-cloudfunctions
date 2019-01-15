# Serverless Google Cloud Functions Plugin

[![Coverage Status](https://coveralls.io/repos/github/serverless/serverless-google-cloudfunctions/badge.svg?branch=master)](https://coveralls.io/github/serverless/serverless-google-cloudfunctions?branch=master)

This plugin enables support for [Google Cloud Functions](https://cloud.google.com/functions/) within the [Serverless Framework](https://github.com/serverless/serverless).

## CHANGELOG
- Deployment Manager API updated from v1beta2 to v1. 
- Added support for service account in provider or function config.
- Added support for new function resource type `gcp-types/cloudfunctions-v1:projects.locations.functions` 

## Documentation

The documentation can be found [here](https://serverless.com/framework/docs/providers/google).

---

## Easier development with Docker

You can spin up a Docker container which mounts this code with the following command:

```bash
docker-compose run node bash
```
