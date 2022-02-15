# Patchwork DevOps Assessment
## About
This repository contains a small project designed to enable an engineer to display some fundamental skills around building & deployment. The repo provides everything needed to output a Docker container with the web app included.

Instructions as to what's expected from this assessment are provided separately via a PDF. 

## Requirements for building
- Docker

## Running & Building
### Building
To build your Docker container with the web-app, you can use the following command:
- `docker build . -t webapp`

### Running
To run the container locally, you can use the following command:
- `docker run -p 8080:8080 webapp`

## Restrictions
- The `main.go` file may not be modified for the assessment.
- The `go.mod` file may not be modified for the assessment. 