pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/michaelrustam/fastapi-michael.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building FastAPI project...'
                sh 'ls -l'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests (if any)...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment step placeholder'
            }
        }
    }
}
