# Networking

## Overview

8/5/2026
- Installed Tailscale
- Connected laptop, pc, and server
- Verified remote SSH access
- Mesh VPNs

## Remote Access

Remote administration handled using Tailscale.

## Networking Architecture

Laptop
|
Tailscale VPN
|
Ubuntu Server
|
Docker Containers

## Services

- SSH: Private via Tailscale
- Docker Management: Private via Tailscale
- PostgreSQL: Internal only
