pipeline {
    agent any

    stages {

        stage('Clone Code') {
            steps {
                git 'https://github.com/username/repository.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building project..."
            }
        }

        stage('Test') {
            steps {
                echo "Testing project..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying project..."
            }
        }

    }
}
