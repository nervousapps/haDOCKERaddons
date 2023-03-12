# Silabs multiprotocol for HA docker installtion

Basically changed s6-overlay scripts and delete bashio.

Modify the .env to change configuration (ports, enable/disable options).

## Pre-requirements
- docker installed
- docker-compose installed

## Build 
```
docker-compose build --no-cache
```

## Deploy
```
docker-compose up -d
```

## Uninstall
```
docker-compose down
```
