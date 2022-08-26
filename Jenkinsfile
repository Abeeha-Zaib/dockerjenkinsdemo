pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
            
               @sudo usermod -aG docker $USER
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
