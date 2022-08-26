pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sudo usermod -a -G docker $USER
                sh 'node --version'
            }
        }
    }
}
