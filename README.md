# Jenkins-in-a-Container

A container composition of Jenkins with a reverse Proxy (Nginx) and TLS (Let's Encrypt).

All together in a single command that runs out of the box.

# Run

You need to define a domain name under which Jenkins should be reachable.
An option is to create a .env file [example](.env) or to define an environment variable `export DOMAIN=ci.example.or``

```
docker-compose -f https://raw.githubusercontent.com/8gears/Jenkins-in-a-Container/master/docker-compose.yml up -d 
```

Done!
