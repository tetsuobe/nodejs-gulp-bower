# Node.js w/ Bower & Gulp runtime Dockerfile

Can be pulled from dockerhub: [tetsuobe/nodejs-gulp-bower](https://hub.docker.com/r/tetsuobe/nodejs-gulp-bower/)

This repository contains **Dockerfile** of [Node.js](http://nodejs.org/) w/ [Bower](http://bower.io/) & [Gulp](http://gulpjs.com/) runtime for [Docker](https://www.docker.com/)'s [automated build](https://hub.docker.com/r/tetsuobe/nodejs-gulp-bower) published to the public [Docker Hub](https://hub.docker.com/).

This image is a base image for easily running [Node.js](http://nodejs.org/) application.

It can automatically bundle a `Node.js` application with its dependencies and set the default command with no additional Dockerfile instructions.

This project heavily borrowed code from monostream's [monostream/nodejs-gulp-bower](https://hub.docker.com/r/monostream/nodejs-gulp-bower/) Docker image.


### Base Docker Image

* [monostream/nodejs-gulp-bower](hhttps://hub.docker.com/r/monostream/nodejs-gulp-bower/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://hub.docker.com/r/tetsuobe/nodejs-gulp-bower) from public [Docker Hub](https://hub.docker.com/): 
```
docker pull tetsuobe/nodejs-gulp-bower
```

   (alternatively, you can build an image from Dockerfile) 
   ```
   docker build -t="tetsuobe/nodejs-gulp-bower" github.com/tetsuobe/nodejs-gulp-bower
   ```