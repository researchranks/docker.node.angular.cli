# Docker: Alpine | Node 6.9.1

### Setup:
 - folder structure for docker.alpine:

 > var/www/app/

 - folder structure for the http-server:

 > var/www/app/public/index.html

### NPM Installs
 
 - angular-cli

 - http-server@0.9.0
 
 > small minimal http server for web view

### Example:
```bash

docker run \
-v $PWD/app:/var/www/app \
-p 80:8080 \
-p 8080:8001 \
--name angular.dev \
-it --rm cntmedia/node.angular.cli:dev

```