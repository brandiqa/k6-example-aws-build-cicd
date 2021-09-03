# Automated k6 load testing with AWS CodeBuild CI/CD

This is an example repo for how to setup k6 with [AWS CodeBuild](https://aws.amazon.com/codebuild/) CI/CD to build load testing into an automation flow.

The full guide describing how to use this repository is located [here](https://blog.loadimpact.com/).

## Run Local

```bash
# Run locally
k6 run scripts/test.js

# Run via Docker
docker run -i loadimpact/k6 run - <scripts/test.js

# Run via Docker Compose
docker-compose run k6
```
