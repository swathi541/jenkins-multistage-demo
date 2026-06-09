pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Getting Code'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Application'
            }
        }

        stage('Test') {
            steps {
                sh 'exit 1'
    }
}

        stage('Deploy') {
            steps {
                echo 'Deploying Application'
            }
        }
    }
}