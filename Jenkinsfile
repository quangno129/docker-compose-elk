pipeline { 
agent {
         node {
        label 'docker-build'
         }
}
    stages {
        stage('Build') { 
            steps { 
                sh 'make' 
            }
        }

    }
}