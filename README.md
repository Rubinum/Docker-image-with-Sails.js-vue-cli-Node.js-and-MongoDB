# Docker-image-with-Sails.js-vue-cli-Node.js-and-MongoDB
Docker image with Sails.js, vue-cli, Node.js and MongoDB

## Usage
### Build
```bash
$ docker build -t app .
```

### Run
```bash
$ docker run -d -v $(pwd):/app app
```

### Bash
```bash
$ docker exec -it $(docker ps -q) bash 
```
