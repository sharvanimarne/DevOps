pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the project...'
                bat 'javac src/Hello.java'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the project...'
                bat 'java -cp src Hello'
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