pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('build') {
            steps {
                sh 'date'
                sh 'echo success'
                sh 'npm --version'
            }
        }
    }
}
