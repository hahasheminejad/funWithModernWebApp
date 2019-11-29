# Deploy Module 1 and 2

What are we doing: 

In this tutorial we build the first set of components of the modern web app.  To accelerate our application launching we are going to put a lot of material from 

https://github.com/aws-samples/aws-modern-application-workshop/tree/python/module-1  

and 

https://github.com/aws-samples/aws-modern-application-workshop/tree/python/module-2

into cloudformation

# Instructions

1. Go to  https://github.com/AndrewG77/funWithModernWebApp/CloudFormation
2. Download the file Module-2 and save it anywhere on your computer
3. Go to your AWS console, make sure the region is us-east-2
4. Click Services - go to CloudFormation
5. Click Create Stack 
6. Use "Template is Ready" 
7. Click Upload a template file
8. Use the file we just downloaded. 
9. Click Next
10. Give the Stack a name MythicalMysfits
11. Fill in parameters  - click Next
12. Configure Stack Options Screen - Click Next
13. Capabilities section on the bottom - click I acknowledge and click Create Stack. 



# While the stack is creating: 

1. Click the Resources section
2. Click Status and ocassionaly refresh.  The stack will take at least 10 minutes to complete.  Stay on this screen while we discuss what is happening under the hood: 

a) Reference: https://github.com/aws-samples/aws-modern-application-workshop/tree/python/module-2
b) You can face errors
c) Please raise your hand and we will help.  This is hands on and we expect issues. 



# Discussion focus: 

1) First let's agree there is a lot of resources being spun up.  This is our first real example of infrastructure as code
2) Let's look at the s3 bucket.  Please be aware - it is a demo purpose only  - we DO NOT recommend PUBLIC BUCKETS.  In production you would put cloudfront implemented in front of it.  Discuss Permissions and Static website hosting.  (Where is a server ?) - pay attention to the URL. 
3) What is the cf-template??????? 
4) How many resources all up ?
5) Show Evangeline
6) Go to CiCD Pipeline 
7) Find Bellefontaine
8) Show the ModuleMysfitsAutoDemo
9) Show the curl command 
10) Show the Ec2 instance in the console
11) Show the website
12) Show the index.html 


# Hands On 10 minute activity

1. Now its your turn.  Go through the console, look at the resources, ask questions, our team is here to help you. 
2. Do not start the next module.  We will do that together. 





 
