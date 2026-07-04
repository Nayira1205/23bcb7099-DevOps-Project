pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/Nayira1205/Tourism-Website-DevOps.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building Tourism Website..."'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Testing completed successfully."'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deployment completed."'
            }
        }
    }
}