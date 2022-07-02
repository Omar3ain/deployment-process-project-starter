## config.yml explanation 
### Orbs 
- are a set of instructions created by CircleCi that allow us to configure the pipeline on which we will run our actions. These instructions will instruct the server to setup specific software on the server executing our pipeline. We could use orbs to setup node.js or install the AWS CLI for example. Orbs are not always present in a pipeline.
- The orbs section will be responsible for setting up some basic recipes
IN THIS PROJECT orbs contain basc recipes and reproducible actions (install node, aws, etc.)
### Jobs 
- are groups of commands that we want to run. This is where we will run commands to install, build or deploy our application.
- The jobs section will contain specific actions to take.
IN THIS PROJECT building and deploy the application as it is in the package.json file.
### Workflows 
- are instructions about the order of the jobs. They allow us to create complex flows and specify manual approvals. Workflows are not always present in a pipeline.
- The workflows section will specify how the jobs should be handled
- it handle the process of circle ci at the main/master branch of git repo.


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

<img src="/screenshots/Circle ci diagram.png">

DIAGRAM SHOWS THE WHOlE PROCESS.

<img src="/screenshots/diagram.png">

## Deploying the application

1. clone the project by typing in the terminal `git clone https://github.com/Omar3ain/deployment-process-project-starter.git`.
2. cd to the folder `cd deployment-process-project-starter`.
3. cd to udagram-api and follow the README instractions there.
4. cd to udagram-frontend and and follow the README instractions there.
