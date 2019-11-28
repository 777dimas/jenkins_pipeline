pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                ssh -i "myubuntukey.pem" ubuntu@ec2-18-184-227-221.eu-central-1.compute.amazonaws.com "uptime"
            }
        }
    }
}
