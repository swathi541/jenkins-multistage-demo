pipeline {
    agent any

    environment {
        APP_NAME = "payment-service"
        ENV_NAME = "DEV"
    }

    stages {

        stage('Build') {
            steps {
                echo "Application: ${APP_NAME}"
                echo "Environment: ${ENV_NAME}"
            }
        }

        stage('Test') {
            steps {
                echo "Testing ${APP_NAME}"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying ${APP_NAME} to ${ENV_NAME}"
            }
        }
    }
}