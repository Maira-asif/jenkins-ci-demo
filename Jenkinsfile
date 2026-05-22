pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Pulling code from GitHub'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Building application...'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Running tests...'
            }
        }

        stage('Notify') {
            steps {
                echo 'Pipeline executed successfully!'
            }
        }
    }
}