pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                nodejs (nodeJSInstallationName: 'node') {
                    sh 'yarn'
                    sh 'yarn build'
                }
            }
        }
    }
}