# Nginx Proxy Manager Container

## Overview

Reverse proxy service for homelab.

## Technology

- Nginx Proxy Manager
- Docker

## Deployment

docker compose up -d

docker compose down

## Ports

- 80: HTTP traffic
- 81: Admin interface
- 443: HTTPS traffic

## Docker Network

Connected to:

homelab-network

## Test Config

Request: nginx.home

Forwarded to: nginx-web:80

## Architecture

Browser/Internet
|
Nginx Proxy Mangaer
|
Docker container

