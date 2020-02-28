
### Prerequisites
You need these things installed and ready

* Docker
* Docker Compose
* A domain
* Port 80 and 443 forwarded to your Docker host!

### Setup and configure Traefik with Let’s Encrypt
* create a directory for our containers:
```
mkdir -p /opt/containers/{traefik,portainer}
```
* create the data folder and config files for Traefik:
```
mkdir -p /opt/containers/traefik/data
touch /opt/containers/traefik/data/acme.json
chmod 600 /opt/containers/traefik/data/acme.json
touch /opt/containers/traefik/data/traefik.yml```

# acme.json stores the HTTPS certificates.

