pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name Test --template-body file://Modified VPC_ALB_NLB.yaml --region 'us-east-1'"
              }
             }
            }
            }
