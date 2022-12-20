# Github Action

This directory contains Github Actions pipeline.

### Prerequisites
* Add Baselime API key as `BASELIME_API_KEY` environment variable
* Add `.github` directory to root of your repository of your observability code repository

![img.png](img.png)

### Pipeline steps
1. Checkout the code
2. Apply changes
3. Produce alerts reports with the latest changes applied.