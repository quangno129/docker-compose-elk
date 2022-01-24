pipeline {
    agent none
    stages{
        stage('Build') { 
            agent {
                docker { image 'sebp/elk:latest' }
            }
            steps { 
                sh 'docker-compose up -d' 
            }
        }
    }
}