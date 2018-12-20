# Docker for local Node.js development

This repo show how to setup Docker for Node.js for local development.
For more info, see [article](https://medium.com/@erzhtor/docker-for-local-node-js-development-164844df5cb6) on medium.

## Getting started
These instructions show how to clone and run the project.

### Prerequisites
- [Docker CE](https://www.docker.com/get-started)

### Clone
`git clone https://github.com/erzhtor/docker-for-local-nodejs-development.git`

### Run
`npm run docker:dev`

No need to `npm i`, because it runs in Docker container and caches until package.json or package-lock.json changes.

That's it! You can edit all contents, nodemon watch mode reruns an app in a docker container on the fly.
