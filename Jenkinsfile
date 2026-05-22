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
                echo 'Building application...'
                echo 'Item added: Build started'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                echo 'Item added: Test cases running'
            }
        }

        stage('Items Section') {
            steps {
                echo 'ADDING ITEMS NOW...'
                echo 'Item 1: Login Module'
                echo 'Item 2: API Module'
                echo 'Item 3: Database Module'
            }
        }

        stage('Notify') {
            steps {
                echo 'Pipeline executed successfully 🎉'
            }
        }
    }
}