# Docker LAMP
Personal docker LAMP environment for development purpose. All images are based on alpine or debian-slim (php:apache) => 700MB

#### LAMP
- Apache 2.x
- Mariadb 10.x
- Php 7.x
- Phpmyadmin 4.x

#### Configuration
Some environment variables are defined in a .env file. So, the .env file must be created before executing the docker-compose file. (see the .env-default)

#### Running
```
# Run in the foreground
docker-compose up

# Run in the background
docker-compose up -d
```
