pipeline {
    agent any

    stages {
        stage('Deploy WordPress') {
            steps {
                sh '''
                docker-compose down || true
                docker-compose up -d
                '''
            }
        }
    }
}

