pipeline {
    agent {
        docker {
            image 'node:14.15.0-alpine'
            args '-p 8000:8000'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'yarn'
            }
        }
    }
}