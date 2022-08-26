pipeline {
    agent { dockerfile true }
        docker { image 'node:16.13.1-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sudo usermod -a -G docker $USER
                sh 'node --version'
            }
        }
    }
