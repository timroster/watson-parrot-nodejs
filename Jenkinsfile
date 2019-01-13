pipeline {
    agent { docker { image 'node:boron-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}