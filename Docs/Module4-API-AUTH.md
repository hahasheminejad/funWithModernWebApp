# Deploy Module 4 - API and Auth

What are we doing: 

In this tutorial we build the first set of components of the modern web app.  To accelerate our application launching we are going to put a lot of material from 

https://github.com/aws-samples/aws-modern-application-workshop/tree/python/module-4  into cloudformation

You will be adopting a Mysfit. 

# Instructions

1. Go to  https://github.com/AndrewG77/funWithModernWebApp/CloudFormation
2. Download the file Module3-API-AUTH and save it anywhere on your computer
3. Please do the change-set, modify parameters and execute as before. Remember to choose replace



# While the stack is creating and the instance is doing it's magic: 


1. Go to Mysfits Page:
2. Keep clicking refresh


a) Reference: https://github.com/aws-samples/aws-modern-application-workshop/tree/python/module-4
b) You can face errors
c) Please raise your hand and we will help.  This is hands on and we expect issues. 

# Discussion focus: 

1) Ssh into the ec2 instance live and watch it make changes 
2) Go to Code Pipeline
3) While Deploy is happening - show what happens to the Mysfits page
4) Look at the details in the deploy stage of code pipeline, click on events
4) Go to the index page - and show true seperation and creation of microservices


# Hands On:

1. Explore the stack as it is now
2. Register yourself as a user (after the DEPLOY ACTION has completed in code pipeline).  Make sure you try passwords not matching.
3. Once registered - click like /adopt mysfit.  Use the 
4. Go to CodeCommit, Repositories, MythicalMysfitsService-Repository find the python files - have a look how the microservice was created
5. Go to the S3 bucket with the web page - have a look at the new files that are there. 