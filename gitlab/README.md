# Gitlab CI/CD

This directory contains Gitlab Pipeline.

### Prerequisites
* Add Baselime API key as `BASELIME_API_KEY` environment variable
* Add `.gitlab-ci.yml` to root of your repository of your observability code repository

![img.png](img.png)

### Pipeline steps
1. Checkout the code
2. Ask for manual confirmation
3. Apply changes
4. Produce alerts reports with the latest changes applied.