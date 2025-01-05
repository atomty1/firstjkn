pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout code from the repository
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Example build step
                sh 'echo "Building the project..."'
            }
        }
        stage('Test') {
            steps {
                // Example test step
                sh 'echo "Running tests..."'
            }
        }
        stage('Deploy') {
            steps {
                // Example deployment step
                sh 'echo "Deploying the project..."'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed. Please check the logs.'
        }
    }
}
