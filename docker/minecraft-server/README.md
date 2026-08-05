# Minecraft Server

## Overview

A Minecraft Java Edition server running in Docker using Docker Compose

## Overview

This projects runs a Minecraft server inside a Docker container. The server files, world data, and configuration are stored using a persistant volume so data remains after restarting the container.

## Deployment

Run:

docker compose up -d

Stop:

docker compose down

## Access

publicip:25565

