pipeline {
    agent { docker { image 'node:14.5.0' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}