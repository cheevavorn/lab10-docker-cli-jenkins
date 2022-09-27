pipeline {
    agent any
    stages {
        stage("Pull") {
            sh 'docker pull hello-world'    
        }
        
        stage("Run container") {
            sh 'docker run hello-world'
        }
    }
}