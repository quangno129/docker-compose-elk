pipeline {
    agent {
        label 'linux'
    }
    stages{
        stage('Build') { 
            steps { 
                sh '
                /usr/bin/docker docker-compose up -d
                '
            }
        }
    }
}