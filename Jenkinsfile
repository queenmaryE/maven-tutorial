pipeline {
    agent any
    triggers {
        pollSCM('*/5 * * * *') // Polls the SCM every 5 minutes
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
        
    }
}
