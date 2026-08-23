pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                sh 'docker build -t jenkins-demo-app:latest ./app'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

    }
}