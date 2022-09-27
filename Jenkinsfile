pipeline {
    agent any
    stages {
        stage("Pull") {
            steps {
                sh 'docker pull hello-world'    
            }
        }
        
        stage("Run container") {
            steps {
                sh 'docker run hello-world'
            }
        }
    }
}