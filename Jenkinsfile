pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sudo groupadd docker
              sudo usermod -aG docker $USER

               
                sh 'node --version'
            }
        }
    }
}
