#### Docker container setup:

```bash

docker run \
-v $PWD/app:/var/www/app \
-p 80:3000 \
--name angular.dev \
-it --rm cntmedia/node.angular.cli

```




### Edge case where lite-server and tsc were not working without the following
 > `npm install --save-dev @types/core-js`

 - `npm install`
 - `npm start`