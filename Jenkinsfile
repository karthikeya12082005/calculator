pipeline {

    agent {
        label 'slave1'
    }

    stages {

        stage('Build') {
            steps {
                echo '=============================='
                echo '     JENKINS AGENT BUILD'
                echo '=============================='

                echo 'Running on Jenkins Slave1'
                echo 'Building Calculator Project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Calculator Project...'
            }
        }

        stage('Result') {
            steps {
                echo 'Build and Test Completed Successfully.'
            }
        }
    }
}