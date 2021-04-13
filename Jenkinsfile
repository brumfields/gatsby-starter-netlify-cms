pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                nodejs (nodeJSInstallationName: 'node') {
                    sh 'yarn install --network-timeout 100000'
                    sh 'yarn build'
                }
            }
        }
    }
}