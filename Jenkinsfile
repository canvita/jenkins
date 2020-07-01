node('master') {
    checkout scm
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Build') {
            sh 'echo hello world'
        }
    }
} 