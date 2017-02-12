# How To Create Appsthlon Environment From Scratch

You need servers:

- Appsthlon Management Server, which contains:
    - Docker Server
    - Jenkins Server with jobs from `setup-core-cd-pipelines` (dockerized)
- Appsthlon Server, which contains:
    - Docker Server
    - Docker Registry
    - Jenkins Server with jobs from `core-cd-pipelines` (dockerized)
    - Core Web application instance
    - Core Services instances
