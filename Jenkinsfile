pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'master',
                    url: 'https://github.com/michaelrustam/fastapi-michael.git',
                    credentialsId: 'jenkins-private-michael'
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
