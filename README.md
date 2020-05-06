# DevOps-Pipeline
DevOps pipeline for creating development and production deployment using Jenkins and Docker

## Prerequsite
* Installed Jenkins, git and Docker in server
* Setup jenkins for creating new job
* check docker service


## Need Of DevOps
* Shorter Development Cycles, Faster Innovation
* Reduce Implementation Failure, Reflections and Recovery Time
* Better Communication and Cooperation
* Greater Competencies
* Reduce Costs and IT Staff

## Problems In Organizations
* Manually creating staging/devlopment server for testing and final approval for production.
* Then again manually creating production server that is too much time consuming as well as have chances of human mistakes. (Increased Release cycle)
* Configuring server manually consuming too much man power and not efficient
* Every time new feature developed required to manually deploy on development server where manually testing will be done then again all this setup will manually done on production. overall dev team has to depend on operation team and if any bug reported in testing then this process has to be start again after bug fixing.

## Solution to this problems
* We need a job which automatically pulling data whenever developer push to scm(Source code management). After pulling data from scm job should create deployment server, configure it and setup the application automatically.  
* Job will first configure developemt server and It will waits for approval from management or test tool. (It varies in organizations) After approval it will do same configuration in Production server.

## What we need
* One jenkins server and portal (Recommended: Setup on centos8)
* one github repository

# Let's Start
* First We will clone our github repository in our local system
image: ![](./images/clone.jpg) 