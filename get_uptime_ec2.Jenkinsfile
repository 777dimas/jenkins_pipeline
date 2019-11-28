pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                ssh ubuntu@18.184.227.221 "uptime"
            }
        }
    }
}
