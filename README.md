# Dripp Vector DB Microservice

## Introduction
Basic kafka backed vectordb service for CNNs, Image searches amongst other things.

## Basic Architecture
Dripp's architecture is event driven, the service consumes from kafka
but can also be called directly using GRPC to talk to other services.

### To set this up
1. Install Docker if you haven't already.
2. Run `./build_and_run.sh`.
