pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/USERNAME/REPO_NAME.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage running...'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage running...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy stage running...'
            }
        }
    }
}
