pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sudo usermode -a -G docker jenkins
                
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
