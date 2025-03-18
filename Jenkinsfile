pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/AfrizalAlka/afrizalalka.github.io.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building project..."'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying application..."'
            }
        }
    }
}
