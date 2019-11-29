# Deploy Module 3

What are we doing: 

In this tutorial we build the first set of components of the modern web app.  To accelerate our application launching we are going to put a lot of material from 

https://github.com/aws-samples/aws-modern-application-workshop/tree/python/module-3  into cloudformation

# Instructions

1. Go to  https://github.com/AndrewG77/funWithModernWebApp/CloudFormation
2. Download the file Module3-DDB and save it anywhere on your computer
3. Go to your AWS console, make sure the region is us-east-2
4. Click Services - go to CloudFormation
5. Click into the stack that you have created - MythicalMysfits
6. Click Change Sets
7. Click Create Change set
8. Click Replace Current Template and follow along to get the file you just downloaded
9. Click Next
10. Fill in parameters  - click Next, 
11. Configure Stack Options Screen - Click Next
12. Capabilities section on the bottom - click I acknowledge and click Create Stack
13. Give it a name and click create change set
14. Wait in the console, click refresh a few times
15. Pay attention to changes
16. Click Execute
17. Pay attention to Resources tab


# While the stack is creating : 


1. Go to your mysfits page
2. Keep clicking refresh

a) Reference: https://github.com/aws-samples/aws-modern-application-workshop/tree/python/module-3
b) You can face errors
c) Please raise your hand and we will help.  This is hands on and we expect issues. 

# Discussion focus: 

1) Change-Set
2) Ec2-Instance was replaced
3) DynamoDB and the command to fill the table
4) CiCD Pipeline
5) Fargate  - look at the python code


# Hands On:

1. Explore the stack as it is now
2. Go to the actual instruction in the AWS-Samples Github page and have a read
3. Go to DynamoDB and change Gretta to Bellafontaine, watch it change on your page, change a few things around - have some fun. 
4. Go to CodeCommit, Repositories, MythicalMysfitsService-Repository find the file mythicalMysfitsService.py
