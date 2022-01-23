pipeline { 
agent {
         node {
        label 'clouldaws'
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