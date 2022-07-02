## services (from AWS) that project needs to run
1. AWS DRS service to the database postgres.
2. AWS S3 service to host the frontend application.
3. AWS elastic beanstalk to host the server-side application.

## modules that app depending on
1. you must install node.js version 14.15.1 or higher version with npm version 6.14.8 or higher version in order you can install your dependencies with "npm install"
2. you must include database software and the one used for that application in postgres sql database.

## Pipeline process
1. first initialize git in that dir and fetch the data in your github account.
2. connent circleCi to tour github account.
3. initialize circleCi in the same dir.
4. connent circleCI to your repo in github it will create a folder called ".cricleci" and inside that folder there is a file called "config.yml" follow the doc of circleCI to understand this file.
5. initialize npm in the main folder by typing in the terinaml "npm init"
6. add the necessary script for building and deoplying the app in package.json.
7. add envimoment variables nesscessary for elastic beanstalk in cricleCI as following:
<img src="/screenshots/cricleCI/secret keys.PNG">

8. git commit the changes to the master branch and it and cricleCI will deoply the app for you.

DIAGRAM SHOWS THE PIPLELINE PROCESS.

<img src="/screenshots/cricleCI/diagram.PNG">

## Deploying the application

1. clone the project by typing in the terminal `git clone https://github.com/Omar3ain/deployment-process-project-starter.git`.
2. cd to the folder `cd deployment-process-project-starter`.
3. cd to udagram-api and follow the README instractions there.
4. cd to udagram-frontend and and follow the README instractions there.


### link of the Front-End Application :
    http://omar-udagram.s3-website-us-east-1.amazonaws.com