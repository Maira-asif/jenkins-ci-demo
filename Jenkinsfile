pipeline {
    agent any

    stages {

        stage('1️⃣ Checkout') {
            steps {
                echo 'Cloning code from GitHub...'
                git url: 'https://github.com/Maira-asif/jenkins-ci-demo.git', branch: 'main'
            }
        }

        stage('2️⃣ Build') {
            steps {
                echo 'Building project...'
                sh 'echo Build completed successfully'
            }
        }

        stage('3️⃣ Test') {
            steps {
                echo 'Running tests...'
                sh 'echo All tests passed'
            }
        }

        stage('4️⃣ Deploy') {
            steps {
                echo 'Deploying application...'
                sh 'echo Deployment successful'
            }
        }

        stage('5️⃣ Notify') {
            steps {
                echo 'Pipeline executed successfully 🎉'
            }
        }
    }
}