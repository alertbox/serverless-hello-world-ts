# Overview

Serverless Node.js examples using TypeScript are organized into groups and designed to illustrate the techniques needed to build great microservices. To use the samples clone our GitHub repository using Git.

## Build and Run from Source

1. Checkout the code and install dependencies
```shell
sls create --template-url https://github.com/alertbox/serverless-hello-world-ts --path my-hello-world-svc
```
2. Compile and run example
```shell
cd my-hello-world-svc
npm start
```
3. [Play with the serverless]() example

## Packaging and Deploying

With VS Code:

1. Open VS Code Terminal
2. Build and deploy
```shell
npm run build
npm run deploy
```
