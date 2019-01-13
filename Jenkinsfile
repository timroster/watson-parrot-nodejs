pipeline {
    agent { docker { image 'node:6.16' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}