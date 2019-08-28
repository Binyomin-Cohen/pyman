pipeline {
    agent { docker { image 'python:3.7.4' } }
    stages {
        stage('Test') {
            steps {
                sh 'pip install pytest'
                sh 'pytest'
            }
        }
    }
}