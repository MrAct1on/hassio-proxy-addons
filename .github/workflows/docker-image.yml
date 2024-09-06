name: Docker Build Proxies-Action
on:
  push:
    branches: [ "main" ]
jobs:
    build:
      name: push docker image to docker hub
      runs-on: ubuntu-latest
      steps:
        - name: Checkout code
          uses: actions/checkout@v3
        - name: login to docker hub
          uses: docker/login-action@v2
          with:
            username: ${{secrets.DOCKER_ENV_USER}}
            password: ${{secrets.DOCKER_ENV_PASS0}}
        - name: Build and push
          uses: docker/build-push-action@v4
          with:
            context: .
            push: true
            tags: mract1on/proxies-action:latest
