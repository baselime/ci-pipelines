# Github

This directory contains Github Actions pipeline.

### Prerequisites
* Add Baselime API key to credentials as `baselime-api-key`
* Add `Jenkinsfile` to root of your repository storing your observability code

![img.png](img.png)

### Pipeline steps
1. Checkout the code
2. Apply changes
3. Produce alerts reports with the latest changes applied.