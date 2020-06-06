pipeline {
    agent {
        docker-slave { image 'node:7-alpine' }
    }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
