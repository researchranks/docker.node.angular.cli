# Docker: Alpine | Node 6.9.1 | Angular-Cli: 1.0.0-beta.19-3 | 

### Setup:
 - folder structure for Docker:

 > var/www/app/

 - folder structure for the lite-server:

 > var/www/app/public/index.html

### NPM Installs
 
 - angular-cli
 - lite-server@2.2.2
 
### Example:
```bash

docker run \
-v $PWD/app:/var/www/app \
-p 80:8080 \
-p 8080:8001 \
--name angular.dev \
-it --rm cntmedia/node.angular.cli:dev

```