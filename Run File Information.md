NOTE:
THIS IS A PROTOTYPE OF THE PROJECTS, WE ARE WORKING ON THIS PROJECT TO IMPLEMENT IT COMPLETELY. 

------------------------------------------------------------------------------
                                         To run this project 
-----------------------------------------------------------------------------

First you need the following Component that is require to Run this project.
1)NPM
2)go language
3)docker and docker-composer
-------------------------------------------------------------------------------
                                   How to run the project
-------------------------------------------------------------------------------

1) Start docker  service :
sudo service docker start 

2)load client container 
docker exec -it sawtooth-client-default bash

3)start Framework
docker-compose -f sawtooth-default.yaml up

4)Run the Processor Dependencies
Make sure you are in Processor folder 
npm start 
