![mysfits-welcome](/images/module-1/mysfits-welcome.png)

# funWithModernWebApp

What are we doing: 

In this tutorial we build the first set of components of the modern web app.  To accelerate our application launching we are going to put a lot of material from https://github.com/aws-samples/aws-modern-application-workshop/tree/python into cloudformation.  

# Step one - get all the prerequisites

1. Log in to your AWS Account

2. Choose the region Ohio - Us-east-2




- https://www.ssh.com/ssh/putty/windows/puttygen

https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/putty.html#putty-private-key
https://aws.amazon.com/premiumsupport/knowledge-center/convert-pem-file-into-ppk/

ami-04b9e92b5572fa0d1 >> Ubuntu 


aws.exe" cloudformation create-stack --stack-name test1 --template-body file://"/Users/goifelda/Desktop/Technical Learning Series/Modules/Reference/stack.yml" --region us-east-1 - test1


s3 bucket that gets created - what name will it have ? 
  
  
 
1. Create a key called misfits
2. What is elbv2 vs ELB
aws elbv2 describe-load-balancers --region us-east-2 --query 'LoadBalancers[*].DNSName' --output text |grep mysfits



CLEAN UP REQUIREMENTS: 

- 1. delete all images in ECR registry
- 2. Delete artifacts bucket
- 3. Delete app bucket
- 4. Delete the stack. 
