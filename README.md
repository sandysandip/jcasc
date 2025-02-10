# Jenkins Configuration as a code #
This repo will help to automate jenkins configurations i.e. Jenkins Configuration as a code this is also called as Jcasc. This Jcasc will do 2 major tasks 

    1. It will create Users
    2. It will create a folder [depndency Folder plughin]
    3. It will create a job [depndency job dsl plughin]

## Prerequisite ##

Before applying this Docker and docker-compose are prerequisite 
To Use this Jcasc follow the below steps-

### Steps to Setup ###
1. Clone this repo and goto jcasc folder
2. Go To jcasc dir using `cd jcasc`
3. docer-compose up -d
4. Docker-compose logs and get admin user password
5. Now try to access [localhost:8080](localhost:8080)
6. Provide password that we got in docker-compose logs
7. install suggested pulgins and 2 more depndency plugins ('folder' and 'job dsl')


