/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.7.2' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}