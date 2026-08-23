pipeline{
    agent any

    stages{

        stage('Checkout'){
            steps{
                Checkout scm
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