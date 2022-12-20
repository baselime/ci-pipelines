# CircleCI Pipeline

This directory contains CircleCI workflow.

### Prerequisites
* Add Baselime API key as `BASELIME_API_KEY` environment variable
* Add `.circleci` directory to root of your repository of your observability code repository

![img.png](img.png)

### Pipeline steps
1. Checkout the code
2. Show the changes to be applied
3. Ask for manual confirmation
4. Apply changes
5. Produce alerts reports with the latest changes applied.