pipeline {
    agent {
        docker {
            image 'node:16-buster-slim' 
            args '-p 3030:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}