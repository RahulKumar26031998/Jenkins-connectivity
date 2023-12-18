pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               bat 'cd C:/Users/nishi/Desktop/Jenkins-connect/Jenkins-connectivity/'
            }
        }
        stage('Build 1') {
            steps {
               bat 'pipenv --version'
            }
        }
        stage('Test') {
            steps {
               bat 'python --version'
            }
        }
    }
}

