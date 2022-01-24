pipeline {
    agent {
        docker { image 'sebp/elk:latest' }
    }
    stages {
        stage('Build') { 
            steps { 
                sh 'docker-compose up -d' 
            }
        }

    }
}