<h1>Hello World program for docker python</h1>

1. clone this repo to ec2 or any machine 

2. aws ecr get-login-password --region eu-central-1 | docker login --username AWS --password-stdin accountID.dkr.ecr.eu-central-1.amazonaws.com
3. docker build -t image name .
4. docker tag reponame:version accountID.dkr.ecr.eu-central-1.amazonaws.com/reponame:version
5. docker push accountID.dkr.ecr.eu-central-1.amazonaws.com/reponame:version
