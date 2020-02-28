
### Prerequisites
You need these things installed and ready

* Docker
* Docker Compose
* A domain
* Port 80 and 443 forwarded to your Docker host!

### Setup and configure Traefik with Let’s Encrypt
* create a directory for our containers
```
mkdir -p /opt/containers/{traefik,portainer}
```

```python
import random, string
haystack = string.ascii_letters + string.digits + string.punctuation
print(''.join([random.SystemRandom().choice(haystack) for _ in range(50)]))
```
