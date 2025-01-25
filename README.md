```
Run a Multi-Container Network
    docker-compose up -d

List running multi-service-containers
    docker-compose ps

List resp. images of a m.s.c network
    docker-compose images

Remove a Multi-Container Network
    docker-compose down

Scaling a service to run multiple containers
    docker-compose scale <service_name>=<num>

Ping Localhost
    Invoke-WebRequest -Uri http://localhost:5000

Set-Alias -Name dc -Value docker-compose
```
