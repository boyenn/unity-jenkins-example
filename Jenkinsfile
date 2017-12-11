pipeline {
    agent { dockerfile true }
    stages {
        stage('Run') {
            steps {
                sh 'docker-compose up -d'
            }
        }
    }
}
