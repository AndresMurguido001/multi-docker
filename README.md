
# Dockerized React Application

Each of these subdirectories (client, server, worker) contains its own development Dockerfile / Production dockerfile.
The goal is to replicate a real enterprise workflow using docker and microservices.

Each development dockerfile should:
 - Copy over package.json
 - Run `npm install`
 - Copy over everything else
 - Docker compose sets up a volume to 'share' files
