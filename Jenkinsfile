pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh 'docker ps'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

    }
}