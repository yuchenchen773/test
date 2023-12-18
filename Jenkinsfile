pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building the code..."'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying the application..."'
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded! Send notifications or perform additional tasks here.'
        }
        failure {
            echo 'Pipeline failed! Send notifications or perform additional tasks here.'
        }
    }
}
