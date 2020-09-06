"# code-deploy-demo" 

Instance Start up Script:

#!/bin/bash -y
yum update -y
yum install ruby wget -y
yum install httpd
cd /home/ec2-user
wget https://aws-codedeploy-us-east-1.s3.amazonaws.com/latest/install
chmod +x ./install
