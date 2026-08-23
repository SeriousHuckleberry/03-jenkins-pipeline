pipeline{
    agent any

    stages{

        stage('Checkout'){
            steps{
                checkout scm
            }
        }

        stage('Build'){
            steps{
                echo 'Bulding the application...'
            }
        }

        stage('Test'){
            steps{
                echo 'Running tests...'
            }
        }
    }
}