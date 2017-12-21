# Development env : how to run


## Prerequisites

Install following tools:

* Node, version 6.9.2 - [link to download](https://nodejs.org/en/download/releases/)
* NPM, version 4.0.3 - [link to download]() 
* Java 1.8u151 - [link to download](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
* Git

Useful article to check installation of NPM and Node - [link](http://blog.teamtreehouse.com/install-node-js-npm-windows)
Please add java to system variables. To check proper installation open CMD and run: ```java -version```

To check **Git** installation run from *cmd*: ```git --version```

## Download sources

`git clone https://github.com/childRon/imshaby-web`

## Install

1. Move to folder *imshaby-web* (let say it's ROOT folder)
2. Run following command: `npm install`

## Run [mock-server](http://wiremock.org/docs/running-standalone/)

1. Navigate to ROOT/mock
2. Run `java -jar wiremock-standalone-2.12.0.jar --port 3000`

Result: ![screen](https://www.screencast.com/t/w5dZb3pXPm4n)

*please note, that port 3000 should be available, in other scenario please run [wiremock](http://wiremock.org/docs/running-standalone/) with --port option*

## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

production: ng build --prod --env=prod
local: ng build --prod



## Other project links

https://travis-ci.org/childRon/imshaby-api/jobs/164624513
https://studio.restlet.com/apis/3d4d9113-390b-489a-b8b1-e6f00cdcd421/resources/~2Fmass~2F%7BmassId%7D/operations/GET

bffe62230a894c7ab79bd64e4ef18c21 - jenkins pass
andrei.misan / 89875956
