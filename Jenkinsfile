pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Time to Reinvent Yourself'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}