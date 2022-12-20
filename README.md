# CI Pipelines

This repository contains CI pipelines for following CIs:
- [Github Actions](github)
- [Jenkins](jenkins)
- [Gitlab](gitlab)
- [CircleCI](circleci)
- [Bitbucket](circleci)

All of the above pipelines utilise [Baselime Docker image](https://hub.docker.com/r/baselime/baselime)
to execute the Baselime CLI.

### Prerequisites
- Adding BASELIME_API_KEY environment variable to your desired CI.