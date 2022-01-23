pipeline { 
agent {
         node {
        label 'cloudaws'
         }
}
    stages {
        stage('Build') { 
            steps { 
                sh 'docker-compose up' 
            }
        }

    }
}