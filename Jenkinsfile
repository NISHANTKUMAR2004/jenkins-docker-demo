pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                bat 'docker build -t jenkins-demo:v1 .'
            }
        }
    }
}