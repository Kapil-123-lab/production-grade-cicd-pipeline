pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Kapil-123-lab/production-grade-cicd-pipeline.git'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building...'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Testing...'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploying...'
            }
        }
    }
}
