# funWithModernWebApp
ModernWebApp 
In this tutorial we build the first set of components of the modern web app.  To accelerate our application launching we are going to put a lot of material from https://github.com/aws-samples/aws-modern-application-workshop/tree/python into cloudformation.  

# Step one - get all the prerequisites
- https://www.ssh.com/ssh/putty/windows/puttygen

https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/putty.html#putty-private-key
https://aws.amazon.com/premiumsupport/knowledge-center/convert-pem-file-into-ppk/

ami-04b9e92b5572fa0d1 >> Ubuntu 


aws.exe" cloudformation create-stack --stack-name test1 --template-body file://"/Users/goifelda/Desktop/Technical Learning Series/Modules/Reference/stack.yml" --region us-east-1 - test1
