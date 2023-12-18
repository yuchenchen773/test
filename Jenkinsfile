pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                script {
                    // Use checkout scm to check out code
                    checkout scm
                }
            }
        }

        stage('Build') {
            steps {
                echo 'Building the code...'
                // Add your build steps here
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add your test steps here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add your deployment steps here
            }
        }
    }
}
