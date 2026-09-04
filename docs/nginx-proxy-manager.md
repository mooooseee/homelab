# Nginx Proxy Manager

## Overview

Nginx Proxy Manager acts as the reverse proxy for the homelab services.

## Deployment

Running as a Docker container.

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

