# Cat-Dog-Classification

## How to Run

1. conda create -n catdog python=3.7 -y
2. conda activate catdog
3. pip install -r requirements.txt
4. python app.py
5. open in browser: http://localhost:8080/

## AWS-CICD-Deployment-with-Github-Actions

### 1. Login to AWS console.

### 2. Create IAM user for deployment

### 3. Create ECR repo to store/save docker image
- Save the URI

### 4. Create EC2 machine (Ubuntu)
EC2 : It is virtual machine

### 5. Open EC2 and Install docker in EC2 Machine:
- optinal
    - sudo apt-get update -y

    - sudo apt-get upgrade

- required

    - curl -fsSL https://get.docker.com -o get-docker.sh

    - sudo sh get-docker.sh

    - sudo usermod -aG docker ubuntu

    - newgrp docker

### 6. Configure EC2 as self-hosted runner
setting->actions->runner->new self hosted runner-> choose os-> then run command one by one

### 7. Setup github secrets
AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = 

ECR_REPOSITORY_NAME = 