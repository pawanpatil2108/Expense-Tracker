pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Source code checked out successfully.'
            }
        }

        stage('Verify Tools') {
            steps {
                sh 'git --version'
                sh 'node -v'
                sh 'npm -v'
                sh 'docker --version'
            }
        }
    }
}