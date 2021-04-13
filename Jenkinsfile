pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                nodejs (nodeJSInstallationName: 'node') {
                    sh 'npm install'
                }
            }
        }
    }
}