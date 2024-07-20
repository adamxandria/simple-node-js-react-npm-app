pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                nodejs(nodeJSInstallationName: 'Default Node') {
                    sh 'npm install'
                }
            }
        }
    }
}
