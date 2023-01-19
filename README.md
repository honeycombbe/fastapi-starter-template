# Specifications

1. Dockerize this fastapi app
    - Docker file for running the app (dockerfile)
    - Docker file for running the app tests (dockerfile.test)
2. Create a docker compose file for running the app (docker.compose.yaml)
3. Create a docker compose file for running the tests (docker.compose.test.yaml)
4. Create a github workflow that will trigger the following in the event of a PUSH:
    - Run the tests to make sure they pass (this uses pytest)
    - If the tests pass deploy dockerized api to AWS ECR