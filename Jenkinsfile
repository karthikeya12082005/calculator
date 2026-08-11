pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Fetching source code...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building Calculator Application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Calculator Application...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Calculator Application...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully!'
        }

        failure {
            echo 'Pipeline failed!'
        }
    }
}
