# paper

`docker-compose.yml`
```yml
version: '3'

services:

  paper:
    container_name: paper
    image: ghcr.io/takagi-minecraft-lab/paper
    volumes:
      - ./paper:/app
    tty: true
    stdin_open: true
    environment:
      JAVA_OPTS: "-Xms256M -Xmx512M"
```

## LICENSE
MIT License