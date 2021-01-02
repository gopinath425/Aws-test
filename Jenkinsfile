pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'aws configure set aws_access_key_id AKIAQQTXCDLKU5U6ZNTP'
                sh 'aws configure set aws_secret_access_key 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'
                sh 'aws configure set default.region ap-south-1'
                sh 'aws cloudformation create-stack --stack-name myteststack --template-body file:///home/test/Desktop/Project/sample_cfn.json --capabilities CAPABILITY_IAM'      
                       
            }
        }
    }
}
