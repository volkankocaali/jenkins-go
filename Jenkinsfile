pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Static Code Analysiz') {
            steps {
                echo 'static analysis...'
            }
        }

        stage('Test') {
            steps {
                echo 'test worked...'
            }
        }

        stage('Build') {
            steps {
                echo 'build...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'deploying...'
            }
        }

    }
}
