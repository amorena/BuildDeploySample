# BuildDeploySample
Sample application based on Oracle JET for use in showing how Oracle Developer Cloud Service can be used to build and deploy an Oracle JET based application to the Application Container Cloud Service

### Prerequisites
* Node.js (for npm)
* ojet-cli (if you want to use that instead of direct Grunt commands)

## Installation
After cloning the repository, change to the root of the application and type

```
npm install
npm intall -g ojet-cli
```

To build and run the application in a browser type

```
grunt build / ojet build
grunt serve / ojet serve
```

The serve command will provide livereload for any files that are changed under the /src folder.  
If you add or remove files, you will need to run the build again.