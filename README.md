# Homelab Infrastructure

Personal infrastracture lab running on Promox with Docker for its services.

## Goals

- Learn Linux administratoin
- Learn Docker and use containers for organization + isolation
- Deploy real applications
- Practice networking and security
- Build portfolio projects

## Current Services

- Nginx web server
- Minecraft server
- PostgreSQL server
- Nginx Proxy Manager

## Hardware 

- Old PC
- 16GB Ram
- 1TB SSD
- Promox VE
- Ubuntu Server VM

## Architecture 

	Internet
	   |
	Router
	   |
	Promox VE Host
	   |
	Ubuntu Server VM
	   |
	Docker
	   |
	Services

Services include Minecraft server, NPM, Nginx web server, etc.
