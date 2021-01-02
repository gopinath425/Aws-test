pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'aws cloudformation create-stack --stack-name myteststack --template-body file:///home/test/Desktop/Project/sample_cfn.json --capabilities CAPABILITY_IAM
'
            }
        }
    }
}
