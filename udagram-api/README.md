# Backend 

## Description:
Server-side made for blogs application which save blogs,registration and logging in the application.

## Installation:
1. there is some important dependencies in order to make the app work such as "node.js" version 14.15.1, "express.js".
2. database used for that application is postgres sql database.
3. to run the application first write in the terminal "npm install" or "yarn"
4. to run the application locally you must make a postgres database and include POSTGRES_USERNAME , POSTGRES_PASSWORD , POSTGRES_HOST , POSTGRES_DB and PORT of database.
5. wirte in the terinmal "npm run dev" and it should start.

## to run the application in aws services:
1. to run the application first write in the terminal "npm install" or "yarn"
2. to run the application  you must make a postgres database using RDS and include POSTGRES_USERNAME , POSTGRES_PASSWORD , POSTGRES_HOST(RDS database url iprovided in aws) , POSTGRES_DB and PORT of database.
<img src="/screenshots/rds/1.PNG">
<img src="/screenshots/rds/2.PNG">
<img src="/screenshots/rds/3.PNG">
<img src="/screenshots/rds/4.PNG">
<img src="/screenshots/rds/5.PNG">

3. for the server-side make a elasticbean stalk enviroment.
<img src="/screenshots/elastic beanstalk/1.PNG">
<img src="/screenshots/elastic beanstalk/2.PNG">

4. write in the terimnal "npm run deploy"
5. make sure that the right name of enivoment is written in the script.

