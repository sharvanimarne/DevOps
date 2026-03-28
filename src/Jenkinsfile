pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the project...'
                bat 'javac Hello.java'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the project...'
                bat 'java Hello'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                echo 'Deployment successful!'
            }
        }

    }
}