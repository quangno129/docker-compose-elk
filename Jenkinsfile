pipeline {
    agent {
        label 'linux'
    }
    stages{
        stage('Build') { 
            steps { 
                sh 'docker-compose up -d'
            }
        }
    }
}