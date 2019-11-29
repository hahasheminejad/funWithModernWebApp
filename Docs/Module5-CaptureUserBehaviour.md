# Deploy Module 5 - Capture User Behaviour

What are we doing: 

In this tutorial we build the first set of components of the modern web app.  To accelerate our application launching we are going to put a lot of material from 

https://github.com/aws-samples/aws-modern-application-workshop/tree/python/module-5  into cloudformation

Let's see what everyone is doing

# Instructions

1. Go to  https://github.com/AndrewG77/funWithModernWebApp/CloudFormation
2. Download the file Module5-UsersBehave and save it anywhere on your computer
3. Please do the change-set, modify parameters and execute as before. Remember to choose REPLACE current template



# While the stack is creating and the instance is doing it's magic: 


1. Go to AWS Console - have a look at cloud formation stacks window
2. Keep clicking refresh
3. When the new CloudFormation pops up - go to resources and click refresh.


Be aware: 

a) Reference: https://github.com/aws-samples/aws-modern-application-workshop/tree/python/module-5
b) You can face errors
c) Please raise your hand and we will help.  This is hands on and we expect issues. 

# Discussion focus: 

1) Go to the Ec2 Console - see instance replace
2) Go to Code Commit - see new repo - talk about why ? Decouple / Codebase becomes less monolythic 
3) Click on the real-time-streaming.yml - another cloud formation template - HOW did we do that ?
4) Look at https://www.youtube.com/watch?v=1dzihtC5LJ0
5) Look at index.html again. (view source) - have a look at two endpoints - why did we do that ? - why not just one ?



# Hands On:

1. Explore the stack as it is now
2. Find the output in the new s3 bucket - clickstreaming file, see what is there inside that file (new clickstreamingbucket was created)
3. Look at all the different stack you now have - how many resources do you have  all up ? 
